---
title: "Programmers Path"
date: 2020-09-06T16:16:31-07:00
draft: false
---

I'm curious to know if there is interest in this. It is kind of an amusing thing to think about. How could engineers have anything to contribute to the conversation of waking up to a bigger consciousness? And yet I think we do.

Post a message if you might be interested in me writing this up. Right now I am focused on the main path and this is definitely not that.

Here is the outline of what I would want to cover:

- Software engineer path
  - Radical truth
    - Running in debug mode
    - Embrace when you are wrong
    - Measuring
  - Learning to be wrong
    - It is a practice
    - Needs to be supported
    - OK to aspire to excellence anyways
  - Check your assumptions
    - debugging leads to this
    - examine sources of truth
  - Dealing with complexity
    - simplify
    - layers
    - scrum
      - negotiating complexity
      - not everyone has to be a software expert
  - Deep dive
    - Five whys
    - Failure without blame
    - Factoring in that humans are failable
  - Flow
    - Cure for sensitivity
      -hiding out in the crystalline, beautiful forests of reason
    - Teaches possibility of joy
      - joy based life
  - Request For Comments (RFC)
    - Courageous asks that can change the world
  - Models
  - Open source
    - Shared libraries
    - Forking
    - Not all opinions are equal

### Five Whys

Software engineers truly hate getting woken up at 3am to solve a service outage. We especially don't like having to report to senior management why we personally cost the company many hundreds of thousands of dollars in lost revenue. This has happened to me. So I was highly motivated to do whatever it took to make sure it did not happen again. At my company whenever a bad outage happens we initiate an inquiry process called "The Five Whys". This process simply asks "why" five times, but each time the "why" is at a deeper level. We first look at the very topmost "why". Why did we have the outage? Maybe a specific sub-system stopped working which cascaded into the whole system going down. OK, simple enough, but then we ask "why" again. Maybe a node in that sub-system went down. Getting a little deeper now, but again we ask "why". Why did just one node going down ultimately bring down the whole site? It turns out no one thought to test what happens when that particular node goes down. Now we are deeper yet, but again we ask "why". Why did we not do the testing? Maybe we did not have a properly thought out testing plan. Getting close now, but there is still another "why" to ask. Why did we not have a proper test plan? It turns out that many software developers like myself are secretly loathe to do proper testing. It is hard enough to get the dumb thing working, and we unconsciously resist deliberately breaking our beautiful sofware. So we suck at testing. But it turns out there are some deeply sick individuals (testers) who actually love to break software. They delight in it. Put those guys in charge of the testing plan and everything runs much smoother.
