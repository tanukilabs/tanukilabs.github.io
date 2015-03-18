---
layout: post
title: "Adding new functionality"
author: copykatt
date: 2015-03-18 08:04
categories: news
comments: true
---

Yesterday I updated the site to include [Disqus](https://disqus.com/) for commenting on blog posts
and implemented the form validation for the Contact Form (feel free to drop by and
leave a comment sometime!). So far everything is working great.

I decided to use [formspree](http://formspree.io/) to forward the messages to my mail account, as it's
the most fitting solution for myself to be used with static sites I've found. The whole magic
basically happens in these 5 lines of code:

{%highlight html%}
<form action="//formspree.io/you@email.com">
   <input type="text" name="name">
   <input type="email" name="_replyto">
   <input type="submit" value="Send">
</form>
{%endhighlight%}

That's it. No registering. Formspree relies on the Mailgun API to deliver the messages, so
should you find yourself using formspree yourself and have privacy related concerns, read
[this](http://www.mailgun.com/privacy "Privacy policy effective 3/31/2014").

Today I plan to work on the Games page, where some of our games will be introduced
in the future. For completed projects there could be descriptions, snapshots and
other cool stuff and for works in progress I plan to add a status bar with Bootstrap
and maybe some implementation ideas (or link it to the appropriate issues/wiki
page on bitbucket or github, we'll see!).

Also, sometime I'd like to add a gallery/wallpaper site to include some snapshots
or wallpapers from one of our games.

Next to all that, I'd like to write some tutorials articles in the future, on cool stuff I've found
and how they work, or maybe just about basics on SQL, Unity, ... basically about
whatever I see fit.
