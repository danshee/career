---
layout: post
title:  "How I Hire: Modeling the Skillset."
date:   2015-09-26 -0700
categories:
---

The best companies that I’ve ever worked for were understaffed.

My reason for saying this is that those companies produced the best opportunities.

One of those understaffed companies had hired me on as a fairly ordinary software developer. I displayed an ability to break large problems down into their component parts and a willingness to help other developers solve problems, so I was quickly promoted into a team leadership position. Initially I had resisted. I didn’t see this as an opportunity. But my manager proved to be very convincing.

One of my duties as team lead was actually building the team. That meant hiring.

I recall one of my early attempts. I was using my managers office to conduct a phone screen interview that was going very poorly. And when I say "very poorly," I mean for me -- the interviewer!  I was very awkward and I could tell that I was confusing the candidate. My manager walked in on the last minute of the interview.

"Well, that could have gone better," I said when the interview was over. It was clear to my manager that I was criticizing myself and not the candidate.

"Don't worry about," he replied. "We're here to learn. Experiment and find out what works for you."

It was good advice. I decided to embrace it.

I started by the thinking about what qualities make a good software developer. I used successful colleagues I had worked with in the past as models. And I also relied heavily upon myself as a model.

I also thought about the few unsuccessful colleagues I had suffered.

How do I filter out the likely-to-succeed from the likely-to-fail?

I thought about the skills needed to do the job at hand.  I thought about some of the weaknesses I had seen. I thought about what strengths would be needed to succeed.

We were building a portable software stack. In terms of hard skills, I needed developers that understood concurrent software implemented in C. That meant basic data structures and problems associated with multithreading. I.e. a solid computer science background.

In terms of softer skills, I needed people who had the initiative to find solutions. The hardware we were writing software for was somewhat obscure and possessed very sparse (and sometimes inaccurate) documentation.

I said to my manager, "I want to hire people who can deal with 'I don't know.'"

By this I meant two different "I"s:

The first "I" was the job candidate. Most of the problems we're assigned we've never solved before.  Problem solving in software development isn't about searching your memory for the time your professor taught you the solution.

Software development is about taking the components that were taught to you by your professor and your various experiences and assembling those components into a solution.

When a candidate experiences that "I don't know" moment, do they give up? Or do they treat it as the first step in solving an interesting problem? 

The second "I" was me.

When another developer came to me for help I could respond in one of three ways:

I could say "I know how to do that" and describe the solution (maybe on graph paper or a whiteboard).
I could say “I know where you can find that” and point them to some documentation or sample code or an algorithm.
Or I could say "sorry, I don't know."
When number 3 happens, I expect the developer to go off and find a solution.

I thought about a previous job I had had writing embedded software. I had never written embedded software prior to that job. I was taught nothing about writing embedded software by my professors or previous employers. And yet I was able to teach myself to write embedded software quite effectively.

So, using my own experiences as a model I came up with my first job interview question:

> The Atmel AT91FR4081 microcontroller has two built in serial ports -- how would you write a device driver for them?

Initially I had imagined asking this question during a job interview. I imagined the candidate responding with "I don't know I've never done that" to which I'd reply "Great! I know the feeling … what would you do next?"

Instead I decided to assign this problem as a homework question. I'd give the candidate the question with a due date at the end of the week. They had to write the device driver. They also had to describe to me how they crafted their solution.

Here’s the thing: *my team didn’t write device drivers*.

So why did I ask this question?

*Because it modeled the skills needed to do the job.*

I wasn’t looking for people who *knew* how to write a serial port device driver. Instead, I was looking for people who *could figure it out*.

Could they locate a design pattern for a serial driver? This could have been done using Google search or a trip to the bookstore (they still had bookstores back then). I found the pattern in a book the first time I tackled this problem.

Could they locate the documentation for the microcontroller? Googling AT91FR4081 produced one very sparse document that didn’t describe the serial ports in any detail. That document did, however, refer to a detailed document on the AT91 microcontroller family. Could they follow this trail to get the information they needed? One candidate sent an email berating me for not providing him with the documentation he needed. He didn’t get the job.

Once they had collected these components (i.e. the design pattern and device specifications) could they assemble a solution? Could they adapt the design pattern to the microcontroller specification? Could they code?

There was more than one potential solution, and the code provided by the candidate didn’t need to be perfect. It was unlikely any of them had an AT91FR4081 to test on, after all. I needed to see that they understood the documentation and were able to translate that into code.

This question tested for another quality that I had not considered: *bravery*. The question appeared to frighten a lot of candidates off. I’d email this question and then never hear from them again. The question was doing it’s job -- albeit in an unexpected way. In my experience, building solutions takes a certain amount of self confidence.

Of course, this wasn’t the only question I asked. We’d do whiteboard problems and discuss data structures and design, as well.

In the end we hired three fantastic software developers who had all passed this question, and with those software developers we built a product.

You can't argue with success!