---
layout: post
title:  "My First 90 Days: What My Uncle Said to Me."
date:   2015-01-24 -0700
categories:
---

When I was a young man and still in university, my Uncle Manfred offered a critique of my character.

“You're the kind of guy that needs someone to tell you what to do,” he said. “I mean you're overly cautious. You don't make decisions. You need someone to tell you that whatever you are doing is OK or else you won't do anything.”

I was rather offended by this. I hadn't asked him for his opinion.

The offensive part was that he was right. Tough love frequently is offensive.

Years later, I took an internship with a startup. There was a lot of expertise at that company and I always had people to walk me through any technical problem that came up, so the personality defect Uncle Manfred had identified wasn't a problem.

The internship was supposed to be four months. I loved what I was doing so much that I dropped out of school and spent an entire year there.

Eventually I decided to leave. I had decided that it was time to finish school. I had also come to the conclusion that our product would not be viable (a victim of Moore's Law – but that's a blog for another time).

Rather than go back to school full-time, I took on a junior level software developer position at a company in the same town as my university. I figured I could finish school part-time.

This new job was quite different than the startup.

Early into my first 90 days, a manager and an architect came to see me. The manager had a network card in his hands (my new company made these). The company needed a Windows device driver for this network card.

They were coming to me for one simple reason: all of the experienced software developers were busy with other assignments, and I was the only developer that was available.

The customer needed it done in three weeks.

“It's ok to say 'no' if you don't feel up to it,” the architect assured me.

I had been hired for my Windows desktop experience. I had never written a device driver. I wasn't even sure what a device driver was.

Also, unlike the startup I had been working for, nobody at this company had any experience with this version of Windows (it was Windows CE, then a new version of Windows targeting small footprint embedded devices).

I'd be in this all alone.

I thought of all the consequences if I was unable to deliver. Embarrassment at best, fired at the worst.

My instincts told me to say 'no.' The architect had assured me that 'no' was option, after all.

I was about to say 'no' when I remembered what my uncle had said to me.

He had been right. I was timid, and my timidness had never served me.

“I'll do it,” I heard myself say.

They smiled, thanked me, and walked away.

My God, what have I done?!?

Later that day I got ahold of our one and only Windows CE device, the device driver developer kit, and the network card. I called the customer and introduced myself. Then I got started.

At the time there was no support for Windows CE development. No books on the subject. No internet community. Just the sample code and documentation that came with the developer kit.

I read. I experimented. I coded.

I determined that there were three major problems I needed to solve to produce this driver: access to the I/O ports, access to memory, and an interrupt service routine implementation. The network card had an LED on it. My first goal was write enough code to toggle that LED. This would prove that I could program the I/O ports.

I spent days on it without success.

Oh my God, I panicked to myself. I can't do this! I'm going to fail!

Late in the afternoon on the Saturday of my first week working on that driver I made the LED turn green.

Wow, I said to myself. I can do this.

At the end of the second week I had a working prototype in the customer's hands.

My uncle would have been pleased.

My new employer was pleased, too. Suddenly I was a somebody rather than a newbie. More opportunities came my way because of the success I had delivered and I rapidly became recognized as one that company's top software developers.

I've been developing software professionally for nearly 18 years now. I've trained new hires, mentored juniors, lead teams, and delivered products. I've been described as “having good judgement” and “being passionate about the quality of my work.” I've also been called "patient," “intimidating,” and “blunt” (I prefer “honest” to “blunt”).

So, people who know me and have worked with me will likely be surprised that I used the word “timid” to describe myself. I confess that it's one of the character flaws I possess. But we don't need to be defined by our character flaws. A good portion of what we are is what we choose to be.

Over the next few years, there were many more instances of oh my God I can't do this followed by wow I can do this before I built a fairly confident software developer out of this pile of raw materials called Dan Pietsch. I learned to ignore my self doubts until they disappeared entirely.

For me and my character flaw, those first 90 days set me on my path. This was the right job at the right time.