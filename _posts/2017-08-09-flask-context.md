---
layout: post
title: Out of Context
---

I've been bumming around with Flask recently and came across
  an issue that took me quite a while to find the workaround for
  so figured I'd share it here.

As I found out, Flask has two context stacks while it is running,
 the app context and the request context.  Occasionally an odd error can pop up in your code complaining about "working outside of application context".




 --solution, pass the app context object into the function, then use with app_obj.app_context()
