---
layout: post
title:      "GETTING STARTED ON YOUR RAILS PROJECT"
date:       2020-03-05 20:18:22 -0500
permalink:  getting_started_on_your_rails_project
---


Recently I just created my first Rails web application. It was very challenging but I learned a lot through it all and overall became more comfortable with Ruby on Rails by the end of it. But at the beginning of my journey I realized something problematic. I had no clue how to begin what started to feel like an overwhelming task.

The app I designed allowed users to create matches (as in games) and add players to them with a few simple details like adding match dates, player names and numbers. It seemed like a super simple idea, so no problem is what I thought. But after getting started by generating all of the models and controllers I was going to need, I realized I had no clue on what to do next. All I knew was the idea of what I wanted and the associations between my models since I was creating a has-many, belongs-to and has many through relationship. So after realizing I was stuck I approached my instructor with the question, how should I start or what should I do next?

**A Users Story**
That's when my instructor explained to me an easy way to go about is following the users story your trying to create. 
Now looking back it was a pretty simple idea, but at the time I had no clue what that meant so he explained further. Basically all a users story is the perspective of an end user or a user of a system. Which knowing that made a world of a difference in the process of creating my app. So I decided the first thing a user would see after booting up my web application would be the login and sign up page. And that's what I ended up creating first, the login username and password functionalities and the proper validations so not just anyone would be able to get in without the correct login credentials. 

After that I decided once a user has an account and is logged in, next thing he/she would see is a page welcoming them with options on what to do next. Which for the sake of this project was only creating a match with players. That included making sure all proper routes where in place, controllers with proper crud functionality were made and proper nested forms were in place for the players to be created within the creation of a match.

Once that was done I had to create all of the buttons such as the edit, delete with working functionailites. And after getting rid of all the app shattering bugs, my app was complete. I definetely wouldn't say it was an easy processs, I spent well over forty hours debugging and re-routing when something had changed, constantly researching new things on google and asking a million and one questions. But torwards the end it didn't feel so daunting anymore since I knew what I had already done and what I had left to do. 

I don't have that much experience when it comes to rails or programming really and I still have a ton to learn, but one thing I do know for sure is, in order to make a great app it helps to put yourself in the users shoes from the very start.
