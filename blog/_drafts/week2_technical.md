---
layout: post
title:  "Trial!"
date:   2013-05-24 18:34:38
categories:
---

Alright, folks--time to talk about something near and dear to my heart (The part of my heart that curses a lot).

THE BOX MODEL! All the cool kids are into it--and don't you want to be one of the cool kids? Sure you do! They're cool! And they're kids! Kids always know what's up.

All joking aside (At least for now) the Box Model is _stupidly_ important if you intend to ever do anything even kind of related to web development. Designers need to understand it, especially when communicating to developers who have to go under the hood. Developers, well...you're gonna deal with this stuff constantly when laying out a site and trying to make it look as awesome as it did in your head. (I'm sure it was awesome--I believe in you).

So let's dive in, shall we? We shall. [Allons-y](https://www.youtube.com/watch?v=hBNH8qub_vI)!

![](http://guistuff.com/css/images/boxmodel.png)
The Box Model is broken up into various areas--And everything starts at the Content. That's your text, your image, etc. And it has this structure surrounding it--I was never super great at science, but I kind of think of those surrounding structures like the layers of atmosphere surrounding little ol' [Planet Earth](https://www.youtube.com/watch?v=OfPWpEKhgfk).

![](http://jacobsapes.wikispaces.com/file/view/atmosphere.gif/226858740/416x272/atmosphere.gif)
If the Content is Earth, the next layer, your Padding, is a buffer between the content and the Border (the ozone layer). The Padding isn't going to change ANYTHING but where your Content is hanging inside of the Border. So, if you want that text to hang out a little higher, closer to the border? Play with those Padding settings.

The Border--this is the ozone layer of your planet--is a defined line--you can make that line bigger, and you don't have to even show that line, but it's always there. Either way--you don't really mess with Border in relation to keeping different elements of your page close or far away from each other--this is more of a presentational choice. (I just heard all of the designers cheer. You guys need to get a hobby.) The Margin and the Padding are measurements of actual space--the Border is a wall.

And, finally, we have the Margin. The margin is the ionosphere (or, as I like to call it, the Big Black Stuff That's All Around Our Little Ball of Blue and Green). But ionosphere is a little shorter. A little.

The Margin, like padding, is a buffer space--and you dictate the size of your padding based upon how far or near you want other elements to be to a piece of content. The Margin will not change anything about how far your Content is from your Border--that's Padding's job. Play with Margin when you want to loosen or tighten up things on your page.

This is a basic summary of the Box Model--hopefully, if you'd never heard of or didn't understand it before, you do now. Or you at least got to see a really entertaining Doctor Who clip. Feel free to hit me up on Twitter if you've got a question or would like to shower me with compliments about how your brain matter has been irrevocably shifted by this article!