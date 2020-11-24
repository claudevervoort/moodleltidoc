---
layout: post
title:  "New in 310 part 1 : Context Id History"
date:   2020-11-23 20:11:52 -0500
categories: general
---

Moodle 3.10 comes with nice improvements on the External Tool module, some long awaited like this one: support for the `Context.id.history` substitution variable.

So what is it used for? It's been for a long time the way to support course copy in LTI (see [course copy road to nowhere](https://www.imsglobal.org/lti-course-copy-road-nowhere)) by communicating to the tool the history of the context.

There are other substitution variables in the [LTI Core Specifications](https://www.imsglobal.org/spec/lti/v1p3/impl) and futur releases of Moodle will bring more support for those.

In the meantime, enjoy `Context.id.history`!

<iframe width="560" height="315" src="https://www.youtube.com/embed/c7vt7ClGTRM" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>