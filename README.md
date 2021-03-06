[![Build Status](https://travis-ci.org/openops/mom.svg?branch=master)](https://travis-ci.org/openops/mom)

MOM
===

MOM stands for "matter of moments". In short it is a time tracking tool which
understands that you don't want to have to think about how to record your time,
instead you want it to seize the moments of attention that you award it.

MOM is all about building operational software in new and sane ways that will
ready us for the future.

#### Built for the web first

With upwards of five core smart phone platforms and thus five separate
development processes, it no longer makes any sense to build for native. The
arrival of PhoneGap and its continuation as Apache's Cordova has made it
completely reasonable to build for the web first and plan to port to native
after. Working this way allows you to seize the most active and creative
developer market available today.

This is all not to mention the fact that the biggest App producers are busy
trying to [recreate their own webs](http://avc.com/2014/05/app-constellations/)
within the careful confines of our devices just so they can occupy more of our
attention. It won't be long before a savvy companies skip the song and dance
and just offer the web access to the device's core features from the get go.
App stores can be lucrative for profits, but with too many of them for
developers to target they can eventually be a liability towards device sales.

Building native is also plauged by a minefield of hoops and barriers for
developers to deal with. The process is burdened with complex platform specific
SDKs and overbearing certificate signing requests. Apple even goes so far as to
require that developers give them a hundred bucks just to take part. The only
sane appoach is offered by Android in that it lets you build its packages on
Linux with no catch.

MOM will be using [Vagrant](http://vagrantup.com) and a set of
[Salt States](https://github.com/stackstrap/stackstrap-salt) to make localized
builds for native platforms a piece of cake... starting with Android. This will
be on top of all sorts of other DevOps goodies that will enable the
participation of the largest group of contributors possible. We welcome the
addition of any other native platforms that support Linux and don't ask
developers to bend over backwards. We may support IOS when we finish up, but
either way anyone is free to port this project over on their own terms :)

## Philosophy

The goal is to create an application that is completely Decentralized. 
Seperating all our concerns creates an application that
can grow well in the open source community. By using tools that can help us enforce this practice we hope to get a 
better understanding on creating apps that are very clear and readable by someone looking to contribute.

## Tools Being Used

While always keeping our design philosophy in mind, we are going to use tools that help us build a scalable and 
decentralized application.

### BackboneJS

Backbone is being used because of the control it gives us in how we want to create the app. 
It gives us all the tools we need in order to create a scalable application. 
Backbone also gives us access to a large community to help us achieve our goals.

## Activities & Checkups

Activities are going to be the tasks that the user inputs into the app. The application will then *checkup* 
with the user using push notifications. This has to be designed in such a way that is completely modular and decentralized. Since this app is going to be designed in such a way that it can 
grow naturally and clearly, the activities need to be stored in a way that gives the activities the ability to be synched 
across multiple devices and servers. They also need to be designed so the app can resume easily from where it left off
previously.
