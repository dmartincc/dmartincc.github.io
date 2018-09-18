---
layout: post
title:  "📈 How to setup a product growth process from scratch for your startup"
date:   2018-09-10 10:00:00 +0200
author: David
keywords: startup, growth process
category: oficina
image: /img/photo-1523875176340-1298db8ee216.jpeg
description: It’s now three months since we launched Zensei, Cherni and me, after some changes in our lives we made the decision to bet on this business idea, which has...
--- 

It’s now three months since we launched Zensei, Cherni and me, after some changes in our lives we made the decision to bet on this business idea, which has a great vision, to help people to have access to cutting edge preventive primary health using data across the globe.

We have a clear roadmap, but we didn’t make the mistake to solve the whole problem at once. Our approach was “Divide and conquer”, and the first objective of these first months was to validate our idea and maximize our learning for the next stage of the product.

## **What did we do?**

Our process is compose of four simple steps, first, user research and design, second, build a prototype, third, test our prototype, and finally, learn from your simple product and marketing acquisition tactics.

### User Research & Design

Ok, we got an idea, but was that idea worth working? The first thing that we did was to read as much as possible on the problem that our idea tries to solve, based on that knowledge, we carried out an online survey with potential users.

We achieved to gather nearly 250 responses, which were very valuable to design our first prototype. We decided to build a simple bot in Messenger, despite the numbers from our survey that told us that we were going to have some problems with that platform, due to it’s not commonly used in Spain.

![User feedback on using Messenger](https://cdn-images-1.medium.com/max/2128/1*lYPQI4gzyMWViDg-6qMsJw.png)*User feedback on using Messenger*

However, that platform and technology was going to give us speed and very valuable feedback thanks to its nature, because users can talk to the bot, and we could afterward analyse those comments and interactions.

So, our design efforts were mainly focus on interaction and UX. No need for fancy designs. Just plain copies which force you to think about the problem instead of colours and shapes.

![User journeys with Zensei](https://cdn-images-1.medium.com/max/3324/1*9zD6ZFBJPV_Jqth2CPctNw.jpeg)*User journeys with Zensei*

### Build

With the bot’s interactions and UX designed, we jumped to code, and less than a month we lauched Zensei Bot in Messenger in May 29.

Here we had the same premise, we needed to use the technology to our benefit and be fast, so Cherni decided to learn the serverless framework, a new paradigm of programming without servers.

Despite a tiny problem with recurrent functions on AWS and to be coding in javascript, this technology helped us to deliver fast and build a prototype which is also going to be the backend of our coming mobile app. We are currently build it.

We also dedicated some time to build a scrapy data collection infrastructure which would help us to learn afterwards. We use Mixpanel for logs collection and Google Analytics for dashboarding, and we made sure that we could trace user between our landing and the prototype.

### Test

Here comes the interesting part. After we launched a digital product, as Andrew Chen says, [“Startups are cheaper to build, but more expensive to grow”](http://andrewchen.co/startups-are-cheaper-to-build-more-expensive-to-grow/), you cannot leave your product alone in the middle of the ocean of internet. If you do that, you are lost.

Therefore, you need to establish a clear set of experiments to acquire users. Our main focus was on macro optimisations, such as these ones:

1. Which are best performing contents, audiences and channels?

1. Which is the audience that performs better?

1. Which is the content that performs better?

1. Which are the keywords that perform better?

With these research questions, we define several experiments, which ranged from doing some emails campaigns, Facebook campaigns, AdWords, youtube, contact specialise journalists, write blog posts and so on.

We also had several coffees with [Álvaro Vila](https://twitter.com/alvarovmz) from [Witei](https://witei.com/es/), he is one of the ones, who knows how to build and growth a Real State CRM and make it viable without any funding. He advised us on how to use digital marketing and to squeeze as much as possible our tiny budget.

In terms of channels, we benchmark several channels in order to prioritise them, as Brain Balfour says on his post [5 Steps To Choose Your Customer Acquisition Channel](https://www.coelevate.com/essays/5-steps-to-choose-your-customer-acquisition-channel). **Using** this approach we came up with this table.

![Channels Benchmark](https://cdn-images-1.medium.com/max/2312/1*bArVPoXiyJeRnwAVZNdQ3g.png)*Channels Benchmark*

After having priotarized our efforts, we started to write some blog posts and marketing campaigns copies with our personas in mind, in our first step in the process we defined clear personas who could be interested on Zensei’s value proposition.

Over a month we tested every channel and we collected very interested learnings that we are incorporating to our current product.

I also met with a friend of mine, [Manuel Cebrian](http://web.media.mit.edu/~cebrian/), a worldwide expert in viral cascades and gimmicks over social networks. With him I discussed several approaches that we could use in order to create some awareness.

From those afternoons came a simple app we build using emojis and word2vec models in order to gimmick people, however, we dismissed that experiment, because it wasn’t align with our vision exactly. Here you can play [EmojiGame](https://zenseiapp.com/game/).

Moreover, we have more gimmicks that we are going to launch in September, Stay tuned!

### Learn

If you like to work with data, as we do. This is your compass for defining your product strategy.

Thanked we build a scrapy data infrastructure, we could analyze our data and learn a lot.

First, we defined our key metric, GROWTH, and what is growth? [This post](http://www.paulgraham.com/growth.html) from Paul Graham defines pretty clear what is growth for a startup.. how can we track our growth? Like this, at least this is how Facebook works it out. You can what [this video](https://www.youtube.com/watch?v=n_yHZ_vKjno) from Alex Schultz from Facebook.

GROWTH = NEW USERS — CHURN USERS + ACTIVATED USERS

Due to recurrence was by default in our designs, we achieved an average weekly recurrence of 43% over 12 weeks since launched and a weekly average growth of 21%, these metrics look promising, but can we explain them? Can we learn from them?

Yes, first plot your data, only data will give you amount of insights. As this chart of our weekly recurrence. Great, nearly product market fit. But we need more.

![Average Weekly Users Retention Over 12 Weeks](https://cdn-images-1.medium.com/max/2004/1*B1pxVe5F2MWcKZ5nYubwQw.png)*Average Weekly Users Retention Over 12 Weeks*

You need to learn much more, so we built some attribution models for each of our key metrics from different points of view of user acquisition channels, such as campaigns, referrals, sources.

![Attribution model result from user sources](https://cdn-images-1.medium.com/max/2000/1*nJEdi2sfIAqqg6sa-0rq9A.png)*Attribution model result from user sources*

This is how it looks like the outcome of one of our attirbution models. We can see that Whatsapp is a strong source of user acquisition. So we will take that into account for our future product design. And, for example, we can say that we know which sources are driving recurrence with a 51% of accuracy. Not bad.

And finally, user feedback, so so valuable to improve your product. People will tell you what they want, like and love. Listen to them.

## Final Words

Growth is the intersection between Engineering, Product Design, Data and Marketing, if you are missing any of them your product is not going to grow. Thankfully, at [Zensei](https://zenseiapp.com) we know some about them.

Some advice, don’t desperate, growth experiments are like scientific experiments, some times work and other no. Just use your learning for minimise the uncertainty.

So reflecting on the first product growth cycle complete, we achieve the following outcomes.

1. Validate our business idea.

1. Set a product growth process.

1. Create some awareness.

We are now in the process of building a brand new mobile app using all our learning from this first phase, we will start to play with viral loops and gimmicks, looking forward to show you our learnings.

We aim to help millions of people world wide to manage their health risks.

🌍📱🏥