---
layout: post
title: Fake it before you make it
image: /assets/pictures/posts/mechanical-turk.png
---

A couple of days ago I attended an interesting meetup that reminded me of the importance of “testing” and that “lean” is not synonymous to doing “test-driven” development. 

The speaker had a very eclectic background spanning from engineering to music. She had worked at MIT, with the Red Sox and, more recently, on Project Soli at Google.  (You might have heard of it as the “Motion Sense” feature on the Google Pixel 4.)

Through her _quite_ technical talk, she spoke about building products with algorithms, motion sensors; she spoke about the challenges of getting and training data; but, she mostly stressed the importance of testing. 

Because she felt that engineers are quite prone to in love with the solution they are building, of optimizing for quality and fidelity, often at the expense of considering the value they are providing or the implications of the technology they are building. 

![Red Sox Pitcher](/assets/pictures/posts/redsox.png){:.img-fluid.rounded.mx-auto.d-block}


For example, in the case of the Red Sox, they were developing a system that could detect pitcher injury from motion at the joints (I am paraphrasing). 

When they were already quite far along, they realized that because of the nature of the movement, their tech could only work with certain players (with low BMI) and that it wasn’t clear what the team should conclude from the results. To wit, should a player with an invisible micro-injury be put on the bench for 6 months? What about the impact on their career? Those were certainly not engineering questions. 

What I found fascinating with her experience was that even if people designing interfaces all day felt that throwing their designs online or showing them to users was “testing”, it often wasn’t.

Since she and her team were dealing with sensors and invisible interfaces, they had to be much more forthright about what they were trying to test and had to devise ways to test before actually building. As early as possible, possibly with “fake” tech. 

![mechanical turk](/assets/pictures/posts/mechanical-turk.png){:.img-fluid.rounded.mx-auto.d-block}

For example, with Soli, a little bit like a Mechanical Turk, they made people believe that they were interacting with motion-sensing interfaces. The participant would swipe their hands from right to left to skip songs, or move up and down to increase the volume. 

The participants thought they were experiencing some magical tech, but the truth was that there was an intern changing the songs on Spotify as the participants were waving their hands around! 

The reason why this example left an impression on me was not because it was truly novel - it wasn’t - but because it reminded me of how different “testing” can be from “lean” approaches. 

“Testing” is about having a clear set of assumptions about what you are trying to validate while “lean” can often become pushing the smallest piece of software to see what sticks. Learnings come from making observations rather than “tests”. And so, they can feel much less clear-cut. 

As she said, quoting Richard Feynman, “If it [your idea] disagrees with experiment, it’s wrong”. The good thing is that if it was a test, you can progress to the next hypothesis. 
