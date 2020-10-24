---
layout: post
title: Systems Thinking
excerpt: "Systems are all around us."
---

## Introduction

During a recent meeting I was sharing the typical age of workarounds we use to support digital order flow with an audience of senior leaders.  I wanted to bring visibility to the issue and build enthusiasm to eliminate these longstanding workarounds.  Unfortunately, the discussion went sideways into a discussion about organizational staffing levels.  Not only wasn't I successful in conveying why workarounds are so damaging, I also didn't do a great job of introducing systems thinking to these leaders.  This blog post is my "do-over" for why systems thinking matters and how it can help to make you a better engineer or leader.  Ultimately I'm hoping that this blog post will make you curious enough to explore systems thinking on your own.

## Reasons to learn about systems thinking 
1) Systems Thinking can be seen in many other movements such as: OKRs, Chaos Engineering, DevOps, Theory of Constraints, and Just culture
   * ***Objectives and key results (OKR)*** is a goal-setting framework for defining and tracking objectives and their outcomes.  Because Systems Thinking is concerned with the outcomes and behaviors of systems via the pursuit of goals and purposes, Systems thinking may be a powerful tool in your toolbox to help you establish and achieve your OKRs.
  
   * ***Chaos Engineering*** acknowleges that our systems are complex and ever-changing and we likely don't really know how these systems will behave under a variety of circumstances. With chaos engineering we can build experiments to gain insights into how our systems behave as well as create confidence that our systems can withstand unexpected conditions.  Netflix made chaos engineering famous via their [simian army](https://netflixtechblog.com/the-netflix-simian-army-16e57fbab116). 
  
   * ***DevOps*** has many definitions and many of strong opinions. For the purposes of this post we'll focus on the [three ways of DevOps](https://itrevolution.com/the-three-ways-principles-underpinning-devops/) popularlized by Gene Kim in the Phoenix Project.   
        * *"The First Way emphasizes the performance of the entire system, as opposed to the performance of a specific silo of work or department — this as can be as large a division (e.g., Development or IT Operations) or as small as an individual contributor (e.g., a developer, system administrator)." Gene Kim, August 22, 2012* 

        * *"The Second Way is about creating the right to left feedback loops. The goal of almost any process improvement initiative is to shorten and amplify feedback loops so necessary corrections can be continually made." Gene Kim, August 22, 2012*

        * *"The Third Way is about creating a culture that fosters two things: continual experimentation, taking risks and learning from failure; and understanding that repetition and practice is the prerequisite to mastery." Gene Kim, August 22, 2012*
   * ***Theory of Constraints (TOC)*** is the management practice that is looking to optimize throughput of a system using 5 focusing steps to alleviate temporary production issues upstream of the proscribed bottleneck.  Both Systems Thinking and TOC require analysts to spend considerable time observing the whole system and the system's behavior to form hypotheses about what changes to make. 
  
   * ***Just culture*** is part of a growing movement that is related to safety culture or high reliability organizatons that see the systems that we build as being primarily culpable for failures.  Practicitoners are applying systems thinking to identify latent factors that may be undermining system's behvior or outcomes.  
2) Systems (and systems of systems) are all around us.  If you are interested in better understanding the things your care about (or perhaps want to change), the [basics of systems thinking](http://www.systems-thinking.org/intst/int.htm) will help you to be more successful on this journey.
3) Understanding the role that ***hierarchies*** play within the overall system. For example, If subsystems dominate, we may encounter "local optimization" and the overall system may not achieve it's purpose.  If the overall system dominates, then subsystems may not be able to evolve to meet changing circumstances. A balance between the two perspectives is necessary as noted here:
   * *"Keeping sub-purposes and overall system purposes in harmony is an essential function of successful systems" Meadows, Donella H.. Thinking in Systems*

   * *"To be a highly functional system, hierarchy must balance the welfare, freedoms, and responsibilities of the subsystems and total system—there must be enough central control to achieve coordination toward the large-system goal, and enough autonomy to keep all subsystems flourishing, functioning, and self-organizing." Meadows, Donella H.. Thinking in Systems* 

4) Nearly all system issues can be explained by one or more "archetypes". You'll find about dozen archetypes with classic examples such as: 
   * *Tragedy of the commons* - consuming too much of shared resources due to poor incentives or lack of information
   * *Success to the successful* - the winners become more successful with every win as the winnings can be reinvested in the next loop
   * *Shifting the burden* - decision makers or actors don't feel the full consequences of their actions
   * *Escalation* - typically found where multiple parties are involved in "one-upping" each other due to lack of common goals

5) Our systems are becoming more complex as new vendors, technologies, architectures, and practices are being introduced. We should expect new failure domains / modes and we design, build, implement, operate, improve, maintain, and decommission our solutions. Systems thinking provides a great starting point to think through these implications.
   
6) Systems Thinking can help architects, engineers, and leaders understand and anticipate system design issues. With the expectation that issues will likely occur at system / domain / team boundaries, the involved parties can brainstorm and implement policies to monitor and mitigate the most undesired outcomes/behaviors. 
   
7) Systems Thinking provides the vocabulary and insights to discuss the impact of workarounds system/process outcomes.  Workarounds are typically pursued with the best of intentions but have a tendency to become permanent scaffolding because they may dampen feedback loops or system actors may not have visibility to workaround usage or frequency. These workarounds may eventually become another form of technical debt that inhibits flow and throughput.  

## Applied example : Shifting the Burden to the intervener - the danger of workarounds
* 

## Resources
* I really like this very brief [introduction to Systems Thinking](https://youtu.be/Miy9uQcwo3U) that compares the study of decomposed parts (analysis) with the study of interconnections and interactions to understand the whole (synethesis). 

* This blog post on [Theory of Organization Success](https://thesystemsthinker.com/what-is-your-organizations-core-theory-of-success/) by Daniel Kim is a though provoking essay and may help to provoke some deeper thinking in your team or organization.

* I have the classic Thinking in Systems by Donella Meadows in every format (print, kindle, audiobook) and I generally recommend the [audiobook](https://www.audible.com/pd/Thinking-in-Systems-Audiobook/B07FWBN4Q5) to newcomers

* One of my family's favorite movies is the Biggest Little Farm that tells the story of a couple looking to build a thriving farm with many many species versus the monoculture that is so prevalent in the world.  This [trailer](https://youtu.be/E0SsZIDJ0O0) should give you an appreciation for the story and the challenges encoutered on the journey.  As you will discover if you watch the movie, this is a real world application of systems thinking and the how they had to find the equilibrium in the system versus optimizing the parts.

* The High Velocity Edge by Dr. Steven Spear applies many of the ideas of Systems Thinking to describe how the best organizations continue to improve with examples from the Navy, Healthcare, Manufacturing, Services, etc. Here's a great [book review by Gene Kim](https://itrevolution.com/devops-book-review-the-high-velocity-edge-by-dr-steven-spear/).  I've been lucky enough to catch Dr. Spear sharing his ideas, including this recent [talk from the 2015 DevOps Enterprise Summit](https://www.youtube.com/watch?v=onwhZwroQHs) by Dr. Spear. 
