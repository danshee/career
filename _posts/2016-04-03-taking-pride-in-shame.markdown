---
layout: post
title:  "Taking Pride in Shame."
date:   2016-04-03 -0700
categories:
---

I had a job interview once.



It was with a gaming startup. They wanted developers with C and Java experience. I had C so I gave it a shot.



I was interviewed by lots of different people over a period of two days. Most of those people and the questions they asked left no mark on my memory. But one interviewer in particular did – let's call him Samuel.



Samuel wanted to know the following: **“Tell me about a really big mistake you made.”**



I was a little taken aback by this question. I was expecting technical questions (I had reviewed my data structures and algorithms from Computer Science) and the usual HR type questions. This question was a little different.



And it was going to be a painful one … because I did have an answer for it. I gave that answer to Samuel, and now I give that answer here:

> In a previous job I had been a firmware developer for embedded devices. I wrote the boot-loader, the device drivers, and much of the OS. When a new prototype device came in, it was handed over to me. I would then run a battery of tests, and when I was satisfied that it was working correctly I would flash our custom firmware onto the device. This testing phase was necessary in order to avoid the possibility of [bricking](https://en.wikipedia.org/wiki/Brick_(electronics)) the device. Two prototype devices arrived but only one was working. So we had only a single prototype. However, on this particular day I had a vacation flight booked and I was looking forward to leaving early. Also, this prototype was a mature revision (revision E or F IIRC) so I assumed it wouldn't have any major problems. 
> 
> So I skipped the usual tests and flashed the firmware onto the device. 
> 
> And I bricked our one and only prototype.  



Then Samuel hit me with his followup question: **“How did making that mistake make you feel?”**



Now I was a lot taken aback. In fact, I was angry and offended that this man was making me relive a very embarrassing incident (an incident in I was completely at fault). But I answered his question (hopefully without showing my feelings):

> Well, I felt terrible, I said to Samuel. A mistake like that could be absolutely devastating to my company. It's not just my employment that could be at stake, but my reputation with the people I worked with. I had to stand in front of them and explain myself. Never again will I make that mistake.



I didn't get an offer from this company (largely because of my lack of Java), so I never found out what Samuel thought of my answers.


## Darryl and Darryl
Some time later I found myself working for another technology company. Let's call them ACME Consumer Tech (ACT). ACT was producing a software product that targeted a variety of third-party consumer devices. My team was responsible for a particular brand of consumer devices – let's call them Omni Consumer Products (OCP). This is how I encountered Darryl and Darryl.



Darryl (not his real name) provided developer support (i.e. working with us software developers to take bug reports and provide help on their APIs) for OCP customers – or at least that's what we expected him to do.



We had a shared email group with OCP that any of us at ACT could post questions to. We did this with the expectation that they would be answered quickly and accurately. We also had a telephone conference with Darryl once a week at a fixed time.



But the emails would frequently go unanswered or simply result in more questions from Darryl.



Our telephone conferences were of no help either. Often we would get an email from Darryl five or ten minutes before the meeting started asking if he could cancel.  **“NO”** would be our reply because we always had critical issues we needed his help to solve.



“Did you see that email about XYZ?” we would ask Darryl.



“No, I haven't seen that email yet,” would be his response. **SERIOUSLY!?!** Were these guys using carrier pigeons to deliver their emails???



It typically took three or four weeks for Darryl just to acknowledge that we had reported a problem or asked a question. By “acknowledge” I mean saying “yes I read your email about XYZ and I have entered the issue into our tracking system, here is the tracking number.” Rarely did Darryl produce an actual solution for us.



One might think that we could have appealed to a higher power. One would be wrong. Sometimes Darryl was unavailable, so we had to deal with Darryl's boss Uber-Darryl (not his real name).



When we would remind Uber-Darryl of a problem we had reported, his typical response was “let's say we fix that bug – how many OCP devices will that sell?” **WHAT!?!** As a software developer, there's often a customer-facing component to my job. I would be ashamed to say something like that to a customer. In my value system – and the value systems of the type of people I'm used to working with – that type of response is **absolutely disgraceful**.



But we needed these guys. Despite the slow trickle of information, we needed the information they could give us. 


## Optimizing the Darryls

So, I redesigned how we dealt with them. I talked to leadership (i.e. software managers and program managers) and came up with the following rules to deal with OCP:

1. We couldn't trust Darryl to solve the problems we reported. Frequently we would report ten or twelve issues, and Darryl would solve one issue and apparently think he was finished (i.e. the remaining problems would remain untouched). We had expected Darryl to solve these problems quickly and enthusiastically (because that's what we would do) and we were wrong. So I concluded that we needed to manage his workload from ACT. So rule #1 was that *individual ACT software developers could no longer post questions to the OCP email group*. Instead, management and the software leads (I was one of these) would prioritize the issues we were having and send Darryl the top three.
1. Darryl always asked lots of questions in response to reporting a bug. Questions about the model of the device and the version of the OS. These questions were reasonable, but the back and forth could be very time consuming. So I collected all the questions he had ever asked with respect to a bug report and made rule #2: *this list of questions must be answered and placed into the email sent to OCP*.
1. Often, Uber-Darryl's response to a complaint was to blame our app – usually something along the lines of “your app is just trying to do too much.” So we needed a way to prove to OCP that the problem was in their product and not ours. This resulted in rule #3: *reproduce the problem in OCP sample code (possibly though modification) provided in their SDK*.

These rules worked to optimize our relationship with OCP developer support, but it never became a pleasant relationship. Many of the critical bugs I had reported during my first few weeks working for ACT were still open during my last few weeks working for ACT. 


## The Lesson

The point however is the conclusion I came to about the Darryls: ***they had no shame***. Or in other words, ***they took no pride in the quality of their work***. I've worked with customers and I've done developer support. I can't imagine behaving in a manner even remotely similar to the Darryls.



Since then I've encountered other Darryls. They are rare but they do exist. At a minimum, they can reduce (if not destroy) my enjoyment of a job. At a maximum, someone like Darryl could have a devastating impact on a small company, especially one that's still working towards profitability (in a small company, everybody counts).



So I think I understand now where Samuel was coming from when he asked me about the time I messed up. It wasn't the mistake he wanted to hear about, but how I felt about it. And it's a question I now ask when I interview potential candidates.



After all, one of my career first-principals is that I enjoy myself – and how could I do that with a Darryl tied around my neck?