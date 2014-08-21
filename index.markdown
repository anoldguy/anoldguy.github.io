---
layout: default
title: Nathan Anderson
---

I love coding Ruby, and I'm learning Swift.  I'm a Solaris/Linux Admin from 1997, web development since 1998, and have been hacking with Ruby/Rails since 2008.

This last year, I started working with the great people at [Basecamp](https://basecamp.com/) ([\*wave\*](https://signalvnoise.com/writers/nathan)), and have enjoying digging deeper into rails, chef, elasticsearch, mysql, docker, and so many other awesome projects!

I also run the [OpenHack meetup in Louisville, KY](http://openhack.github.io/louisville/).

{% unless site.posts.size == 0 %}
### Blog Posts
{% for post in site.posts %}
 * <span>{{ post.date | date_to_string }}</span> &raquo; [{{ post.title }}]({{ post.url }}) {% endfor %}
 {% endunless %}