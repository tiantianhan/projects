---
layout: post
title: "Undergrad thesis: matching skin tone"
date: 2015-05-01
categories:
- research
tags:
- research
photos:
- /assets/posts/images/undergrad_thesis.png

---
**University of Toronto**  
**Platforms:** C++, OpenCV

I wrote a program that changes human skin colour to match another’s.

<!-- more -->

The motivation here is that we have a nail polish try-on app that uses a model hand to demonstrate the appearance of nail polish - we want to be able to adjust the skin colour of the model hand to whatever the user’s skin colour is. That way, the user has a better idea how the nail polish will look on themselves.

This sort of skin colour matching and correcting is actually a pretty common task for people who edit photos. The challenge here is to do it automatically, without the help of a human making judgments about how to adjust the colours. It’s not as simple as adjusting brightness - for it to look natural we had to do things like avoiding dark lines and bright spots.

It still needs work for big colour changes! One of the things I learned was how unforgiving changes to skin colour can be - unless you get it just right, it can look very unnatural.