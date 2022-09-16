---
layout: post
title: SMSForward-to-Pushover-by-android-phone
---
{{ page.title }}
1. add Flow

<img src="{{site.baseurl}}/assets/posts/{{ page.title }}/markup_394.png" style="width:50%">
2. Sms Recieve

<img src="{{site.baseurl}}/assets/posts/{{ page.title }}/markup_395.png" style="width:50%">
3. Post to Pushover

Request URL

`https://api.pushover.net/1/messages.json`

Request content body
```
{
    "token": "abc123",
    "user": "user123",
    "device": "divice1,divice2",
    "message": smsbody
}
```
<img src="{{site.baseurl}}/assets/posts/{{ page.title }}/markup_396.png" style="width:50%">
