---
title: Hangouts - Events
layout: events
---

# Hangouts

We run regular (monthly) online hangouts where Labs members get together to discuss and build things.

<iframe width="560" height="315" src="//www.youtube.com/embed/JsC71suLLRo" frameborder="0" allowfullscreen></iframe>

The hangout is an opportunity for folks to present projects and ideas and also to discuss any general Labs items such as improvements to website, events, etc. It is informal and anyone can come along and contribute. If you would like specifically to present something please jump into [the etherpad][etherpad] and add it to the agenda (slots are max 5m).

* When: Thursdays at 1700-1800 BST (1200-1300 EDT, 1800-1900 CEST) [time zone schedule](http://everytimezone.com/#2015-6-18,240,cn3)
* Where: Google Hangouts - we will announce the join link on the day on the [list and IRC (#okfn)][contact]
* Sign up: (optional but recommended) add your name to [the etherpad][etherpad]
* Recordings of previous events are posted to our [YouTube channel][youtube]

[contact]: /contact/
[etherpad]: http://pad.okfn.org/p/labs-hangouts
[youtube]: https://www.youtube.com/channel/UCQe-pXn0XZzmRzvyOMZpfEg

## Humanities Hangout

For people interested in tapping in to the increasing amount of **open cultural data and content** to create **apps and insights**.

<ul>
{% for post in site.categories.blog %}
{% if post.event == 'hangout' %}
  <li>{{post.eventdate}} &ndash; <a href="{{post.url}}">{{post.title}}</a></li>
{% endif %}
{% endfor %}
</ul>
