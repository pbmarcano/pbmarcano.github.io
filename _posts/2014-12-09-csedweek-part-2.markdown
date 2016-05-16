---
layout: post
title: CSEdWeek (Part 2 of 5)
date: '2014-12-09 21:52:30'
author: Pete Marcano
redirect_from:
  - /csedweek-part-2/
---

### Putting ideas on screen
[Yesterday](/2014/12/08/cs-education-week.html), we left off with basic functionality and ideas on paper. Today's mission was to get the ideas off paper and onto our computer and phone screens.

Unfortunately, the amount of work actually accomplished today was rather low, and I blame some good ol' cardboard for distracting me.

---

#### Cardboard delay

As I walked into the office, I found a package on my desk. After opening the package, I found a bunch of cardboard, two little lenses, and two little magnets in a bag. I quickly realized that I was holding [Google's Cardboard](https://cardboard.withgoogle.com). For the small price of about $2.50, I was the proud owner of Google's virtual reality headset... made from cardboard.

Assembling it took a few minutes, but then I loaded the app onto my Nexus 7 tablet, and members of the office immersed ourselves into virtual reality for the better half of the morning.

I even managed to grab a photo of my friend John "exploring" the wonderful city of Chicago (more like a foot from his desk, facing a wall).

![John in Chicago](/images/2014-12-09-14-43-40.jpg)

Either way, we wasted more time than I'd like to publicly admit, but I eventually got around to work.

---

#### The Web Front-End
Some of the many joys of doing web design is showing off ideas, getting feedback, and feeling proud of how awesome you are at making HTML do your bidding. Now, just because I learned HTML at a young age doesn't make me a "Web Designer". In fact, I am the furthest thing from it. I can always appreciate good design, but creating it isn't exactly my strongest talent. To quickly prototype my "designs", I used [Bootstrap](http://getbootstrap.com/).

Bootstrap is a front-end framework started by Twitter a few years ago. Because most of the CSS and JavaScript is already written, all you have to do is write HTML in Bootstrap's constraints, which are documented wonderfully on their website.

Without spending a lot of time, I was able to build a simple and usable website that looks professional enough. Perfect for this kind of task.

##### The layout
Millennials love to customize their gadgets and they tend to love their options. It's why most of us are comfortable with Facebook's layout and typically can untag a picture in under a minute.

Since **Key** is being developed for [Digital Immigrants](http://www.techopedia.com/definition/28139/digital-immigrant), I am making sure my designs are intuitive and familiar. The "devices" page (the one that lets you deactive your phone if you lose it) is currently looking like this (more work needs to be done, I know):

![Devices Page](/images/Screenshot-2014-12-09-21-00-52.png)

* One small navigation column under the logo
* One main content column to the right hand side.
* Log out button is right where you would expect it, top left.

Simple, usable, and *hopefully* intutitive. As of this writing, I am sending out a URL to my mother and going to ask her to perform certain actions (nothing is working, just testing the UI), just to see if she can figure out how to navigate around. All of this was written with bootstrap snippets found on their website, and very little customization has gone into it. If my mother can use it, anyone can use it (sorry mom!)

#### The iPhone App
Apple has a way of doing everything different. This even extends as far as programming for their devices. If you have learned one language, usually learning another isn't difficult... that is... unless you are programming for iOS or OS X, and are using Objective-C.

The reason I started writing C at 17 was because I was trying to learn the foundation of Objective-C. This programming language was incredibly difficult and even deterred developers like me from getting into iOS in the first place. But as of this year, Apple released a new programming language called [Swift](http://www.apple.com/swift/).

If the thought of programming iOS scared you, I am encouraging you to jump back in and try it again. Learn Swift. Swift is easy to learn and easy to use no matter what your experience level is. Personally, to learn Swift, I took [lynda.com](http://lynda.com)'s [Swift Essential Training](http://www.lynda.com/Swift-tutorials/Swift-Essential-Training/180105-2.html) course and was able to learn Apple's new language in the course of an hour or two. Swift turns iOS developing from a nightmare into a dream.

#### Passwords should be like phone numbers
In [Ignite](http://ignite.ucc.ie), the director of the program made an observation about **Key**. He recalled a time when he had to remember everyone's phone numbers, but today, we collect phone numbers, use them all the time, but never have to remember them. They could be twice as long and it wouldn't make a difference to us 99% of the time.

Basically, "Key" will do to passwords what "Contacts" did to our phone numbers... Make them only exist in the background.

When planning the design on paper, I did my best to replicate the simple apps on our phone, like Contacts and Messages. The first version of this is app intended to be familiar to any iPhone user, and should be once again welcomed by people like my mother (sorry to picking on you, I'll make it up at Christmas!)

Sneak peak:

![Screen](/images/2014-12-09-21-27-45.png)

Not flashy? Good! It isn't meant to be flashy, it's meant to get you from point A, to point B, as quickly as possible. If I can't make logging in as simple as possible I will be failing my future users.

Accounts are layed out vertically and if you need more information, you can just tap an account and access what you need.

My goal is to do as much as possible without users ever having to pull the phone out of their pockets. But more on that later...

#### Adding Data
Tomorrow's goal is to set up a back-end server, and start loading it with the data models necissary for users to save and sync their passwords across devices, securely.

A lot of the coming work is hard, and I will have to overcome a big learning curve since I will be using a [MEAN.JS](http://meanjs.org/) stack (never tried this before), but after some research I am confident that the learning curve will prove itself more than useful in the future.

Happy coding and hope for distraction-free progress tomorrow!
