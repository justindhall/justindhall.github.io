---
layout: post
title:      "My Ruby CLI Gem or: how I learned to love the struggle"
date:       2019-04-04 15:58:17 -0400
permalink:  my_ruby_cli_gem_or_how_i_learned_to_love_the_struggle
---


Don'ts: Spend 2 years away from Ruby, skip reading links in Learn lessons, tell yourself you aren't good enough

Do's: Learn to ask for help, create solutions for things you are interested in, strain every day to become better

Hi! My name is Justin and I spent 2 years wasting my time and talents and efforts and heart by not knowing how to deal with setbacks. And I can tell you, that isn't a very fun experience. In the last couple of weeks, I've started to turn things around; this CLI Gem Project is the [eating of that pudding, or whatever.](https://www.npr.org/2012/08/24/159975466/corrections-and-comments-to-stories) Let me tell you a little bit about how it taught me to appreciate the struggle as opposed to run from it.

[Go ahead and check what people think of Learn's CLI Gem Project.](http://) I'll wait. A cursury glance through student blogs will tell you that it's tough! This is really the first time that the program let's you try to walk on your own and that is scary. You've been cruising through lessons ([or at least a responsible student would have been](https://media.giphy.com/media/apowQdwqKcKPK/giphy.gif)) and suddenly arrive at a page without one of those nice "Launch IDE" buttons. Eek! You are given a list of requirements, some resources to [git](https://media.giphy.com/media/10UUe8ZsLnaqwo/giphy.gif) started, and told to figure it out. And that is the best part. Nobody can be a quitter and finish this project. It's a sign that you have learned how to struggle. How to figure things out. And that is just as important a skill for a future developer as knowing any language!

Being somewhat rusty with my Ruby and Git skills, the start of my project was a bit of shiggle-fest. I wrestled with getting [Bundler](https://bundler.io/v1.12/bundler_setup.html) working, figuring out how to tell my program what I needed it to know how to do, and even getting my Github repo set up. At this early point, I was already feeling aprehension about getting back to programming. After all, this wasn't even the difficult part of the project! But nevertheless, I kept pushing and looking up documentation and finally had the bones of my project ready to work.

After what I would estimate was over 20 hours of programming, googling, programming, googling, breaking things, googling, and programming some more, I had a big chunk of my gem completed. I felt really good about what I had! It didn't work, but my code looked nice at least! It looked like something that could work if I fixed a couple of things. But those couple things were majorly holding me back and I was struggling hard to figure them out. My two holdups: my scrape method wasn't returning as an array and the object that I was getting was one giant list of information as opposed to a number of individual episodes of the podcast. This was super frustrating! I could feel myself slipping into the place where I was going to think about giving up again when a friend helped me out with two critical pieces of advice.

1. [The Ruby .map method](https://www.rubyguides.com/2018/10/ruby-map-method/). Unlike .each, the .map method will return a new array with the results of your block. This was super helpful! Hearing about .map again felt like snow melting in my brain, uncovering a piece of knowledge I had forgotten about and needed to be reminded of. I took some time to implement .map and started running into new problems. That's a success in any programmers book!

2. [CSS Selectors](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Selectors). It turned out that I was blowing what should have been one of the easier parts of the project! I had been misusing a couple of CSS selectors resulting in grabbing every single episode all at once as opposed to creating new objects for each podcast. While it's always frustrating to find out you've spent so much time on something that was a quick fix, the relief of having a working project was totally worth it!

By the end of my project, I felt significantly better about both myself and the prospect of getting to keep working on the Learn curriculum. Having something tangible to point to (well, as tangible as code can be) and say, "I did that. That is all my work." inspires a lot of confidence that I didn't have before. I have something to be proud of! What a great feeling.

If you want to check out my CLI Project, you can find it on my [Github](https://github.com/justindhall/pod_scraper).

-Justin


