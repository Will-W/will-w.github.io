---
layout: post
title: "Software Engineering vs coding vs Computer Science"
description: ""
category: software
tags: []
---
{% include JB/setup %}

#### Software Engineering vs Coding vs Computer Science

A few weeks ago, as part of the backlash to Lottie Dexter trying to get everyone to learn to code while having no idea what that actually meant, a couple of interesting articles cropped up on Hacker News.

Terence Eden argued that in the rush to get everyone coding, we're forgetting Computer Science
([Learning to Code vs Learning Computer Science](http://shkspr.mobi/blog/2014/02/learning-to-code-vs-learning-computer-science/)).
> It's not just about learning which buttons to press in order to make an app - it's about a deeper understanding ...   
> Learning to code is merely teaching people to spell.

The response from Quinn Rohlf ([Learn to code then learn CS](http://qrohlf.com/posts/learn-to-code-then-learn-cs/)) highlights the fact that actually a lot of CS graduates aren't strong programmers, and can have trouble with some basic tasks.

> Without an understanding of whats happening at a low level, my peers ran into
> issues like C segfaults and Java NPEs and had no idea what to do to debug them. This is a problem that stems from teaching people computer science but not
> teaching them how to code.

These two articles are two sides of a fairly common *Coding* vs *CS* debate, but
what this debate always seems to miss is that there is a third strand to working in software. A third side to this (rather unusual) coin: Software Engineering. Or at least, that's the term I ascribe to those skills to producing software that aren't just coding, and aren't the algorithms and theory.

Coding is great, and if not the foundation on which everything else is built, then it is at least the gateway drug. Most programmers I know got into it from hacking some website together aged 12, or writing a program in VB that made fish swim around and bounce off walls. That sort of tinkering is where the easy access fun is.  It takes a special sort of person to discover Lambda Calculus to start with and *then* decide to program.

This is the whole purpose behind the Learn to Code movement, at least as I see it. Not everyone should be a professional, or wants to be, but a little extra ability to make a computer do your bidding is never going to be a bad thing. The wonderful side effect of this is that more people will discover that they enjoy it, that they're good at it and will follow that path more seriously.

If they're lucky they'll find a good CS course and get taught the theory required to solve the difficult problems. They probably won't get taught to use any programming language properly but, again, if they're lucky, their own interest will have meant that they've learnt independently. Then they'll get a job, and whether or not they consciously realise it, they'll discover that there's a whole extra set of skills required to produce quality work in a complex project.

We're really talking about process I suppose. The steps you go through to build something that's actually useful. Off the top of my head they include:

1. Requirements Capture, User Stories, just talking to the users. Whatever you call it.
2. Design and architecture
3. Development
3. Debugging
4. Testing
5. Verification
6. Documentation

Of those only development is really taught as a core skill, and even that isn't fully covered. Yes you might be taught about the algorithms you need and you might have taught yourself the syntax you need, but no one will have hammered into your head the relentless refactoring you need to do as every new function goes in. That every time you add something new you should revisit what's there already, pull out the common stuff, provide a generic interface, adjust your APIs. Those things that you need to do so that as your project hits 10 000 lines, 100 000 lines, 1 000 000 lines it's still something that you can work with and isn't a fragile unintelligible mess.

Does anyone teach that you need to test your work as you go along? That whether you're doing full on TDD unit testing, or you just have a decent system test suite, you need to make sure that you're catching bugs as you create them. That you don't break things every time you fix things.

Who teaches you what a good requirement looks like, how you write one, and how you justify you've fulfilled it at delivery?

Debugging is the big one here. There are some simple logical processes you can use that are far more effective than continual stabbing around in the dark at possibilities. Depending on the sort of projects you work on, you may spend far more time debugging code than writing new stuff.

A lot of this can't be taught. Some of it can be, should be, and rarely is. The important thing is for people to recognise that these skills are core to the job and that they are at least as important as the CS stuff at elevating you above being just a code monkey.

I mean it when I say "at least as important". I work on some fairly challenging things, but I almost never have a hard Computer Science type problem to deal with. There is some basic stuff that's important day to day like knowing that I want a linked list rather than an array due to the constant insertions and deletions. More than that though, is much rarer. Yes, on those days knowing that a [Bloom filter](http://en.wikipedia.org/wiki/Bloom_filter) is what you need for the problem is where I really add my value, but mostly I'm in demand because I can start from a hand wavy statement of a problem, investigate it, specify it, design a solution, implement it, demonstrate that it works and hand it over. And sometimes I even write documentation.

