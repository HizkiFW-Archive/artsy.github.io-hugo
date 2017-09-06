---
author: orta
categories:
- mobile
- ios
- review
- video
- energy
- folio
- oss
date: 2016-02-12T00:00:00Z
series: iOS Code Review
title: 'Code Review: Energy Sync'
url: /2016/02/12/Code-Review-Energy-Sync/
---

We are slowly trying to do high-level code-review views for all of our iOS apps. So far, we've covered [Eidolon](/blog/2016/01/14/eidolon-code-review/) and [Emergence](/blog/2015/11/05/Emergence-Code-Review/) and now [Energy](/blog/2016/02/11/Code-Review-Energy/). This is the second part of the Energy code review. The [first part](/blog/2016/02/11/Code-Review-Energy/) covers the the critical codepaths that go from the App's launch to sending an email, which is the main use-case for the app. This video covers how Folio does sync between the Artsy API and the app.

Sync is a complex problem. This video covers our old techniques, how we changed them, the underlying abstractions we use now and how we can test each component individually. It's an hour long, and it's a little computer-sciencey. So I think people who have shipped some small apps would get a lot out of it.

Jump [to YouTube](https://www.youtube.com/watch?v=05HaKChPe_g) for the video, or click more for a smaller inline preview.

<!--more-->

{% youtube 05HaKChPe_g %}
