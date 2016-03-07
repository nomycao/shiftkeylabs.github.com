---
layout: post
category : Reflective blog
tagline: "SuperPowered SDK"
author: Brian Yip
tags : [SuperPowered Audio Engine iOS Android]
---
# SuperPowered

This week, I felt the need to catch up in my schoolwork. I mostly needed to catch up in my **Mobile Computing** course to research an audio processing framework to make my group's app come to life. So far, my group and I were already familiar with the **Swift** programming language, but this framework used **Objective-C++** (not Objective-C). The SDK used Objective-C++ because it must allow its user to process audio (low level interfacing) for both Android AND iOS. You can think of Objective-C++ as a hybrid between Objective-C and C++.

Below are some key concepts that I learned when bridging C/C++ headers and source code into our project:

- All .a files (**archive library files**) will depend on some sort of iOS framework. These frameworks must be added to the project build in order for the project to compile properly.
- You cannot include pure C++ properties in an Objective-C header file. They are only allowed in the source file. I do not recommend hacking around this by writing shims as C++ code should not be exposed to pure Objective-C and Swift code anyways.
- Objective-C++ can use Objective-C headers.
- Swift must use a **bridging header** in order to interface with the lower level Objective-C++ implementation.
- When learning a new framework that appears to have little documentation, take a look at example projects that were built with that framework.

      ![SuperPowered](https://yt3.ggpht.com/-YjfZVyQAW7Y/AAAAAAAAAAI/AAAAAAAAAAA/YZ8iQ_zY2bo/s900-c-k-no/photo.jpg)


From this, I have further familiarized myself with Objective-C and low level audio processing code.

For more information on the SuperPowered SDK, click [here](http://superpowered.com/)
