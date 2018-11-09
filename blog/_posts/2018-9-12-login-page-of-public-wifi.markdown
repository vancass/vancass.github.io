---
layout: post
title: Getting to the login page of public WiFi
date: 2018-09-12 12:30:10 +0300
img: titles/free-wifi.jpg # Add image post (optional)
fig-caption: # Add figcaption (optional)
tags: [Do You Know]
---

When you go to a coffee shop and connect to their public WiFi, chances are your phone / laptop will automatically open a login page of the WiFi. Sometimes you need to fill in your particulars before you can use the WiFi, or maybe there's a huge button "START BROWSING" that you simply need to click before you're connected to the internet.

Sometimes, for whatever reason, your phone / laptop might not open any window. Then you will start to wonder, you're already connected to the WiFi, but how do you connect to internet?

In the case that the login / main page is not showing up automatically? You will need to open it manually.

To give a real world example, I'm going to use Singapore Expo as the context. This happened to me last week during the Industrial Transformation Asia Pacific exhibition. I was already connected to the free public WiFi, but somehow I was not connected to the internet.

In this case, what I do is usually to open a browser and type in the address `1.1.1.1` or `0.0.0.0`.
If you're lucky, the login page might appear.

If you're not lucky, you might need to check the wireless status. Follow the below steps:

![]({{site.baseurl}}/assets/img/post/1-windows.png)
![]({{site.baseurl}}/assets/img/post/2-cp.png)
![]({{site.baseurl}}/assets/img/post/3-adapter.png)
![]({{site.baseurl}}/assets/img/post/4-status.png)

In this example, the default gateway is 10.111.0.1.

In that case, I just need to open my browser, and type in `10.111.0.1` and voila!

# Summary
1. Try `1.1.1.1`
2. Try `0.0.0.0`
3. Find out the gateway IP address and type in the magic number