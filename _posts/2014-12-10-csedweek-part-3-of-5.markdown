---
layout: post
title: CSEdWeek (Part 3 of 5)
date: '2014-12-10 20:07:28'
author: Pete Marcano
---

### Struggles of a rusty developer
I know yesterday I promised myself and the few readers of the blog that I would throw some data into the back-end of yesterday's apps... but the reality is that I remembered a few additional things that needed to be done before I can really dive into that code. My apologies, I am a bit rusty.

The last *real* programming I did was about seven months ago when I was writing code for my Master's project (the same one that lead to the formation of this business). Like most languages, if you fail to practice programming, your skills fade.

I spent the majority of today learning a new programming language/environment, configuring my server, and setting up git repositories on [Bitbucket](https://bitbucket.org).

While I still have the code from my Master's project, I'll be rewriting much of the backend code for three reasons: Programming language, server environment, and intellectual property.

#### Programming Language
I had spent the majority of the masters writing code in C#/ASP.NET  MVC. These are Microsoft supported languages and frameworks that I have enjoyed using but, until recently, don't have a lot of open source support.

My desire for open source comes down to price, community based support, and the amount of developers that enjoy programming open sourced languages and frameworks. I decided that I would make the switch from C# and ASP.NET MVC to 100% JavaScript.

JavaScript has been around for ages, and thanks to frameworks like [Node.js](http://nodejs.org/), [Express](http://expressjs.com/), and [AngularJS](https://angularjs.org/), I can use JavaScript everywhere. Not having to learn and switch many programming languages is a huge benefit for a small team, and the cost to develop in these languages is free, unlike the Microsoft environments.

Like most of the introductory learning I do, I spent the programming part of the day with one monitor at my [Brackets](http://brackets.io/) text editor, and the other screen at [Lynda.com](http://www.lynda.com/)'s Node.js Essential Training. This course is longer than I expected, and truthfully a bit dry in the beginning. But I have to learn how Node operates in the back-end before I make any sort of progress.

I warned my readers this week, I have no idea of the progress I will actually make, but I know I will make enough.

#### Server Environment
While programming in Microsoft languages in frameworks costs money and licensing, hosting your applications is also more expensive. Since you have to pay licenses for a Windows Server, IIS, SQL Server, and .NET runtime, hosting your app on Amazon is more expensive than the free linux based competitor.

Startups burn through money quickly. Anything to save me a buck or two will be exercised. Using Linux and open sourced software, I won't have to pay licensing fees for building and hosting my website, just for the electricity and bandwidth.

#### Intellectual Property
While I highly doubt any of the members of my former Master's group would take me to court over Copyright violations, I feel more comfortable not using the code we co-developed as a group. Writing it again in a different language with different functionality, simply makes me feel better.

#### Bitbucket and Server Setup
Like I said earlier, I spent a good chunk of my day actually setting up my git repository and development server.

I used Bitbucket to set up my git repository. Bitbucket allows up to 5 users to manage their software projects in the cloud for the cheap price of free. For those of you ignorant of git, just imagine being able to write multiple versions of the same Word document, and going back in time through each save you completed. For software developers, git makes life easier.

For my server setup, I deployed a [MEAN.JS](http://meanjs.org/) stack through [DigitalOcean](https://www.digitalocean.com/?refcode=2cb06965cad7). DigitalOcean allows developers to quickly deploy Virtual Private Servers and host their code online for $5 a month (and up if you want beefier servers).

For the features and service DigitalOcean provides, you can't beat the price. I've tried.

I am excited for tomorrow. Providing some test data and saving data to the database. But tonight I am getting some sleep.

Cheers,
Pete
