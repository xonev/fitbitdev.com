---
layout: post
title:  "Getting Ready for Your First Fitbit App"
date:   2017-09-18 08:00:00 -0700
categories: guides
---

The Fitbit Ionic is coming! It will ship soon - as of this writing the
preorder form still says it could be three to four weeks - and when it
does we will be ready to create some apps. I have done
quite a bit of research already to get a head start, and, while I have not
found many ready-made tools (Fitbit studio is not available yet, no
emulator will be shipping, we don't have our watches, etc.), with a bit of creativity there is still
plenty to learn and plenty to do.

## Required Reading

First off, to start learning what we need to know to create apps, it's
helpful to have some idea of the Ionic's capabilities
out of the box. You can find out by reading up on the watch at
[the Fitbit store](https://www.fitbit.com/uk/shop/ionic) and then acquire even
more detailed information by perusing
[the Ionic user manual](https://staticcs.fitbit.com/content/assets/help/manuals/manual_ionic_en_US.pdf).

After that, you will most likely want to start reading up on the
development side of things. The first stop on that path would be the
[Fitbit SDK announcement](https://dev.fitbit.com/blog/2017-08-28-announcing-the-fitbit-sdk/)
closely followed by the SDK documentation. Unfortunately, Fitbit
Studio is not available yet, so you will probably want to start by
reading [the SDK guides](https://dev.fitbit.com/guides/application/).

Once you have gotten through all that, I also found
[this blogpost by Lawson Kight](http://www.lawsonkight.com/fitbit_ionic.html)
helpful when considering how to go about designing the aesthetics and
UX of a Fitbit app.

## Getting Involved

Once you have read up on some of this stuff yourself, you will most
likely have some ideas and some questions. To get those question
answered or get feedback on your ideas there are a couple of great places you can turn:
[the official Fitbit SDK development forum](https://community.fitbit.com/t5/SDK-Development/bd-p/sdk)
and
[the unofficial Fitbit discord chat server](https://discord.gg/4ujeheG). You
may also want to follow [@FitbitDev](https://twitter.com/fitbitdev) on
Twitter.

## Start Creating

Finally, not having all the tools we need to actually
test our apps on a Fitbit device does not imply that we cannot start
designing, creating prototypes, and even writing some code.

I have
already started playing around with drawing ideas on paper and
creating rough paper prototypes in
[invision](https://www.invisionapp.com/). This method can be effective
for revealing design flaws and helping refine ideas. You can learn
more about that
[here](https://www.usability.gov/how-to-and-tools/methods/prototyping.html).

It's also possible to start playing around with code now. NiVZ on the
SDK forum converted one of the
[SDK examples](https://github.com/Fitbit/sdk-lcd-clock) to
[a JSBin](https://community.fitbit.com/t5/SDK-Development/How-to-simulate-image-based-clock-face-in-JSBin/m-p/2174744#M124). If
you want to get working on some UI, then that is probably the best
place to start. If you are already pretty sure about what app you want
to build, you can use your Software Craftsmanship skills - including
knowledge of
[hexagonal architecture](http://alistair.cockburn.us/Hexagonal+architecture)
(a.k.a. the ports and adapters pattern) to write your domain
logic and core behavior. Then, when you have access to
[Fitbit Studio](https://studio.fitbit.com/) and your new smart watch,
you will only need to write the UI and I/O code (which may be
substantial, but at least you already got started).

## Let's Get Started

We hope it's clear by now that you already have plenty to do to get
started with planning for and even creating your first app. Don't
hesitate; you can start creating now! If you
found this helpful, be sure to follow me
[on Twitter](https://twitter.com/xonev) for further updates.
