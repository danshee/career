---
layout: post
title:  "Degenerate User Experiences."
date:   2016-03-28 -0700
categories: jekyll update
---

"Idiot proofing."

That's what it was called back when I was in high school learning how to code. I never liked this term. I felt that it characterized the user (paying customer) as someone possessed by [malice and stupidity](https://en.wikipedia.org/wiki/Hanlon%27s_razor).

This concept of "idiot proofing" has matured into what we now call *User Experience*. This concept doesn't just encompass protecting users from themselves. Rather, it strives to design software that isn't just easy but also pleasant to use.

                                        

**Anecdote:** *I booted up my PC the other day. Instead of Windows I saw a solid blue screen with the text "All your files are exactly where you left them." That was it. No progress indicators. No UI controls. Nothing to indicate the source of this screen. I began to panic, thinking that it might be ransom-ware.*

*But it just turned out to be a Windows update.*

                                        

Around the same time that I was in high school our phone system went digital. This was my first experience with voice mail. If someone called and we weren't home to answer, they could leave a message. Later on, we could dial in to the voice mail service and listen to any messages.

The voice mail service instructed us that to end the call we needed to press * and hang up. If we failed to press * and just hung up, the phone would ring a few seconds later and the voice service would be on the other end.

"Are you still there?" the computer woman would ask. Then she would proceed to instruct us that in order to terminate a call with the voice mail service we needed to press * first, and then hang up. I forget what happened if we just hung up at that point.

This is what happens when the concept of idiot proofing is allowed to [metastasize](https://en.wiktionary.org/wiki/metastasize). The telephone had been around for over a century at this point. The paradigm for ending a telephone conversation was to simply hang up. Why did I need to treat a voice mail session differently?

                                        

**Anecdote:** *It used to be that when my Samsung S5 beeped, I could quickly check the lock screen to get an idea of why. A gmail or voice mail notification generally warranted my attention, anything else could be ignored for later. But my device was updated recently, so now instead of a helpful icon it says "Verizon Wireless." I already know I'm using Verizon -- I send them a large payment every month.*

*Now I have to unlock my phone to determine if something requires my attention.*

                                        

I like to think that we now talk about *user experiences* instead of *idiot proofing* because we respect and empathize with our users. After all, software has become ubiquitous. We deal with it everyday, and ordinary people deal with it everyday. Even our grandmothers.

One of my first jobs was writing Windows device drivers. In order to use one of our devices, the user had to set dip switches on the device, and then configure that setting in our Windows configuration tool. This dip switch/software configuration was used to indicate how the device was to communicate with the PC. However, sometimes that particular configuration wouldn't work for that particular PC, so the user would have to try a different dip switch setting. This involved rebooting the PC each time, which was time consuming (and painfully boring). I prototyped a tool that would allow the user to do the inverse of this: the tool would determine the configuration automatically, and then communicate the dip switch settings to the user. It required only one reboot and none of the frustration.

Alas, this idea was shot down. The reason: a lot of [time and effort had already been spent](https://en.wikipedia.org/wiki/Sunk_costs#Loss_aversion_and_the_sunk_cost_fallacy) training customers on how to configure the product.

I did however develop an important professional philosophy from this experience: "*configure*" should be a [four-letter word](https://en.wiktionary.org/wiki/four-letter_word).

Years later I heard this philosophy expressed as "*it should just work*." That's how I've expressed my feelings ever since.

*It should just work* -- what a beautiful phrase.

Years after that I was working on some client-side software and found myself in conflict with our system architect. I brought up an issue with the way dates were being communicated and recommended that we all agree to use the [ISO 8601](https://en.wikipedia.org/wiki/ISO_8601) standard. I was flabbergasted when he said that the users would be required to *configure* the date format in the application settings.

I looked at my manager for help, but he was nodding his head in agreement.

You know how I feel about the word configure.

I started channeling Chef Gordon Ramsay.  "Say that again???"

A date format looks something like this: `yyyy-MM-dd'T'HH:mm:ssZZZZZ`. Or it might look like this: `MMM-dd-yyyy HH:mm:ss`. Or could look like something completely different. The purpose of this format is to allow client code to translate the date it exchanges with the server into its own internal format that it can understand. So if the date format that was configured by the user was incorrect, then any functionality having to do with dates (i.e. displaying and editing) would not work correctly.

In fact it wouldn't work at all.

Requiring the user to *configure* the date format was not a solution. It was an *anti-solution* that would metastasize into a myriad of problems:

1. As a developer I would have to add error handling code to handle the (inevitable) case where a user incorrectly configured the date format. It would be something along the lines of detecting the error and then popping up a dialog notifying the user that their configuration was incorrect and possibly directing them to a *knowledge base article*. I hate it when software directs me to a *knowledge base article*. "*Knowledge base article*" should be a four-letter word.
1. Customers purchasing our product would have to find a way to communicate this configuration point and it's correct value to each of their users. Ideally, a user shouldn't have to do anything beyond entering their username and password. The software *should just work*.
1. It didn't scale. A multitude of users would have to *participate* in solving this problem by filling out the configuration value. This problem could be [stopped before it became a problem](https://en.wiktionary.org/wiki/nip_in_the_bud) if a few people could simply *think about the customer*.
1. Customer support would need to understand this configuration point. They would also need to understand the symptoms of a mis-configuration of this point. Symptoms of this kind aren't the type of knowledge we have when we ship a product. They are the results of customers finding problems with our product. A large list list of symptoms (likely linked to *knowledge base articles*) indicates poorly designed software.
1. How would customers (or potential customers) react if they had to enter some cryptic string into their applications settings in order for their product to work? Keep in mind that this would be [their first interaction](https://en.wikipedia.org/wiki/First_impression_(psychology)) with our product.
1. I could keep going...



*There is a path*. At the end of that path is the *goal*. That *goal* -- **the legitimate goal** -- is the product in the hands of customers. And it needs to be the product that the customers want.

But are you truly building that product? Or are you building something else? Are the decisions that are being made steps towards that goal? Or do those decisions take you off that path?

This is a problem I often see with otherwise intelligent people: **they lose focus on the goal**. Instead of visualizing the completed product, they focus only on the immediate problems before them (like how to communicate dates between a client and server). If those problems are solved badly, they could accumulate into unpleasant user experiences.

The moral of this story: *remember who your master is*.

Your master isn't your boss or your employer or that scary executive down the hall.

Your master is the customer.

***Always focus on the finished product in the hands of customers.***