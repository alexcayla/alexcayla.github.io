---
name: czekpass
title: Czekpass
description: Czekpass is a frictionless purchase verification platform that allowed merchants to confidently offer perks to specific sets of customers 
order: 1
type: product
layout: post
languages: 
    - Ruby
    - HTML & CSS
    - JavaScript
frameworks:
    - Rails
    - Bootstrap
---

Painless personal business 

## The problem
To attract new customers, businesses want to be able to offer perks and discounts. They want to target specific types of customers based on the type of purchases they make or their membership to certain organizations. For example, offering discounts to college students.

Yet, there is no simple and scalable solution to do this. Business owners will have to integrate their systems with each other or with a third party; a costly, complicated, lengthy, proposition.

Or they will just require prospective customers to provide proofs of purchase. Such as asking our college students to bring a school statement to the store.
Obviously, this is not ideal. It’s manual, prone to error and fraud, and is generally difficult to track.
 

## The idea
The idea for Czekpass came from a student encountering this problem: as a Le Wagon student, he was learning how to code 10 hours a day. But he still wanted to maintain an active lifestyle.

He approached a couple of businesses to see if they could offer him (and his fellow students) a special discount as they would only be using the facilities in off-peak hours (after 8p.m.).

As a “proof of membership,” Le Wagon agreed to share its list of students to the businesses that wanted to offer these perks to its students. To maintain the deal, it would have to do so again, and again, and again, for every incoming class.

The idea was to create an app that could track purchases as seamlessly as possible, thereby making the verification process trivial. That a prospective customer could just walk up to the front desk, flash a QR code or tap an NFC reader, and get a discount.

# The app

The app itself is quite simple, but quite complex as it had to serve two types of users with different types of devices.

For users, the main flow is connecting to the website and looks for perks available to them. If they found a perk they wanted to redeem, they only needed to walk up to the front desk and flash a QR code.

For the business owner, creating perks was also easy. After having created an account and added some products, she only needed to find the business she wanted to connect to select the product she wanted to use to “unlock perks” and save.

As the platform would take care of logging the purchases, perks would be shown and unlocked automatically once the set-up was completed.
The process is shown in the video below.

<div class="embed-responsive embed-responsive-16by9">
<iframe width="560" height="315" src="https://www.youtube.com/embed/6fIASbNv_Yg?start=1940" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

## Challenges

On the design side, one of the most challenging aspects of the app was creating a frictionless experience. For example, purchases should be added automatically whenever possible. 

This had to be a principle of our designs because, as the benefits of using the service were deferred in the future (when I want to make another purchase), any "ask" would risk being "too much" and discourage users from getting value from our offering. 

On the technical side, there were quite a few challenges related to implementing that vision. Most notably, how does the verification process work? How does a customer "unlock" and "see" new perks? 

As the user and the business do not "know" each other before trying to transact and a certain level of confidentiality is to be expected, this can be tricky. 

After all, as a user, I do not want to put all of my purchases on the Internet for the off chance of getting perks in the future. 

## Solutions and innovations
In the end, the solution was not too complicated: as both the user and the business need to be connected to claim or approve a perk, the only information the user needed to provide was the ID the perk he wanted to claim. 

The system would then look to see if he met the conditions (had made the required purchases) and allow the business owner to complete the transaction, the new transaction would then be automatically logged to the user's profile. 


<img src="/assets/pictures/czekpass/Czekpass core flow.png" alt="Czekpass core validation flow" class="img-fluid">


## Vision and next steps

As the project progressed, one of the most interesting discoveries is how it could be applied to create a new type of "loyalty" platform. 

Traditionally, loyalty platforms were built around attracting and retaining customers. The value of these customers was done over long periods of time through qualification and nurturing. 

Czekpass, by contrast, would allow business owners to offer perks to "prequalified" customers through their past purchases at other businesses. For example, Body Factory Bali could offer perks to gym goes from Chang Mai or even New York before they have even landed in Canggu! 

However, as the success of such a network depends on the number of businesses taking part, the main challenge is to refine the experience and onboard more businesses. At the present time, these activities would be done in markets in which critical mass can be attained quickly, most notably in South-East Asia. 


