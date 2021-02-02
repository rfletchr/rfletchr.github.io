---
layout: post
title:  Make Neatvideo fail rather than watermarking renders
categories: [nuke, neatvideo, rlm]
excerpt: Save render time by causing neatvideo to fail, rather than watermarking renders
---

```
neatlab_CHECKOUT_CRASH_ON_ERROR=1
```

This will cause neatvideo to crash if it cant acquire a license, rather than spending the time rendering then watermarking it.
