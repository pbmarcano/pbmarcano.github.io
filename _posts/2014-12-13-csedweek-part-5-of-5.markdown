---
layout: post
title: CSEdWeek (Part 5 of 5)
date: '2014-12-13 01:13:39'
author: Pete Marcano
redirect_from:
  - /csedweek-part-5-of-5/
---

### CS for Everyone!
I'd like to share my appreciation with those who write code for a living. After 60 hours of staring at colorful lines of code, I am beginning to lose my mind for all those hours of frustrating errors for those few seconds of successful glory (it's totally worth it, I swear).

Today, I was able to witness a friend get his programming certificate from *Hour of Code*! This individual had no previous intentions of learning computer science, but gave it an hour anyhow. After his *Hour of Code* he became so interested and intrigued that he immediately enrolled in [Harvard College's CS50x](https://www.edx.org/course/introduction-computer-science-harvardx-cs50x) class online, where he is taking a couple hours every week to learn introductory Computer Science. Needless to say, I am proud of him for trying something new. One never knows what they are interested in until they give it a shot.

As for my programming ~~frustrations~~ progress today, I got an in-depth knowledge of the [Express.js](http://expressjs.com/) framework that puts Node.js on the web, and provides a solid structure for the developer.

Express.js handles most things including, but not limited to:

* Routing (Instructions on how to handle URL requests)
* Templating (Help put data into a website structure)
* Single page applications
* Access to MVC pattern

While browsing the web to get a better understanding how Express.js handles these things, I found a [couple](http://theholmesoffice.com/how-to-build-a-simple-webpage-in-node-js/) [tutorials](http://theholmesoffice.com/getting-ready-for-scalability-creating-an-mvc-framework-for-our-node-js-page/) that I thought were insightful and could help me develop the product I needed to make. Since I have experience with ASP.NET MVC patterns, I knew I wanted to learn more about the Express MVC pattern.

### MVC
So what the hell is MVC anyways? MVC is an acronym for "Model - View - Controller" and it is used in most advanced programming environments today. It provides a way for developers to separate their application into three areas of concern.

#### Model
When we look at the Model, what we are really focusing on is the data and logic behind the application. The Model usually handles the structure of data stored on a database (like user accounts) and "DRY" (another three letter acronym... "Don't Repeat Yourself") code that will be used more than once through your application's lifetime.

The NoSQL documents that I spoke about [yesterday](http://blog.pbmarcano.com/csedweek/) are created as "Models" for the application. They simply exist as data and logic, so they possess no visible form.

#### View
The view is typically what is responsible for what we are able to see when we look at a modern website. Back in the day, we programmed what the website looks like, and what data we wanted to present on the same page.

Most modern web apps work very differently. Think of Facebook. Every time you load Facebook, your newsfeed *looks* the same, but the data/posts are always different. This is because the view templates the page, and the data you need is automatically loaded in. If Facebook existed twenty years ago, it would have looked similar to the old MySpace we grew to love. We all made our static profile pages and people would have to deliberately visit you to obtain your recent information (nevermind that horrible boy-band music in the background). Yuck.

#### Controller
Think of the controller like the middleman. When you request to see a web page, the controller goes to the model, asks the database for the information you want to see, structures it, and passes that data to the view. Simon Holmes has a neat little picture describing the process.

![](/images/mvc-diagram2.png)

The controller basically acts as an operator, and it is the developer's job to program it to anticipate the user's need and supply the relevant data back to the user. While ~~bad~~ less experienced developers will write a lot of code into the controllers, more experienced developers will write as much logic as possible into the models, allowing the controller delegate functions. This makes code clean and reusable, a programmer's nirvana.

Together MVC breaks up an application and allows more flexible experiences. Almost every device you use today is programmed with some form of MVC. From your iPhone or Android in your hand, to the blog you are reading from now.

### Closing thoughts of the day
When I decided to dive into the JavaScript stack earlier this week, I thought it would be relatively similar to the .NET stack I was used to. It simply isn't. While the two have similarities, programming for them is different enough that I found myself learning the basics of these frameworks. I have learned a lot this week, and I am looking forward to expanding my knowledge of the MEAN.js stack in the future. I may even become a huge fan in coming weeks!

In terms of my business's product, I didn't break as much ground as I had hoped to, but I still am much further than I was in the beginning of the week, which is something to say for all those learning computer science:

The hardest part of learning a difficult skill is starting. Once you start, you will constantly impress yourself. I've seen experienced developers learn new tricks this week, and I've seen people visibly excited after their first program run, including my president.

Even if you didn't learn any computer science this week, I encourage you to give it a try if you have some free time. Websites like [codecademy](http://www.codecademy.com/learn) allow people to learn programming skills at their own pace for free.

At the rate technology is evolving, the amount of high paying [software development jobs](http://www.bls.gov/ooh/computer-and-information-technology/software-developers.htm) in the US is increasing exponentially. It is never too late for a career change!

I wish you the best on your learning. Thanks for reading, and happy coding.

-Pete
