---
name: Tincan
description: Tincan is a remote recording tool that allows podcasters to record phone conversations that don't sound like phone calls. 
order: 3
type: product
layout: post
languages: 
    - TypeScript
    - HTML & CSS
frameworks:
    - React Native
---

Record remote interviews, without compromises.

## The problem
The main *persona* using tincan is either a podcaster, a journalist or a product manager. In short, someone who wants to record conversations, find new insights *and* share the result with others. 

Tools such as Skype, Hangouts or Zoom make it easy to speak with people and record conversations. However, they are not ideal: typically, the audio quality of these conversations is not great (they have that distinct "conversation over the Internet" sound) and they don't offer a simple way to group conversations. 

Podcasters and radio-journalists typically solve this problem by doing *two-end recording*. In short, each participant records the best possible version on their device and then share it to someone that will stich it together *"in post"*. 

Obviously, this solution does not scale when dealing with a large number of guests or invitess. 

## The idea

*Tincan* wants to solve both of these problems by packaging *two-end recording*in an app, so that "low tech" guests can don't have to think about it. And, organizing conversations in topics so that related conversations stay organized together.  

## The app

The app was designed to be as simple as possible around two clear storues: 

1. As a organizer, I want to create a conversation and invite guests
2. As a guest, I want to join a conversation

***That's it***. Uploading, levelling and stitching are all done automatically. 

And, when the organizer is ready to produce and episode, listen back, annotate or share, the recordings can be accessed through the app or exported to the drive of their choice, as individual tracks or together. 

## Challenges
While Apple allows iPhones to record conversations, it does not allow *phone calls* to be recorded. This is the reason why most "call recording apps" call a third number where the conversation is recorded. To sidestep this issue and be able to record conversations, we had to create VOIP calls between all participants. 

This turned out to be the most challenging part of the development. The documentation for the library was poor and inaccurate, it made use of undocumented APIs in Swift and Objective-C. 

To compound this issue, we had decided to develop the app natively, in Swift, although no one in the team was familiar with the language or the tools. 

Ultimately, after struggling with the technologies and frameworks that were supposed to help us decrease our time to market, we stopped developing our own VOIP solution, relied on an external service to route and record calls and used React Native instead of Swift to develop the first app. 

## Vision and next steps

Tincan is currently in alpha, betas invites are expected to be sent in January 2020. Based on the uptake by the market, there are a couple of features that could be developed: 

* Automatic transcriptions to simplyfing analysis and search
* In browser "app-less" recording flow (as a progressive web app)
* Annotations and feedback on the finised product (send to past guests)
* DAW (Digital Audio Workstation) integration


