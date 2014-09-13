---
layout: post
title: "Bitcoin Alert"
description: ""
category: Android Apps
tags: [android, bitcoin, alert]
---
{% include JB/setup %}

##Bitcoin Price Alert

It is currently very basic. Developed in less than 24 hours. Currently it only connects to Coinbase.com to retrieve the Bitcoin price. It also only can do static interval. Target price alert will be added in future release.


##Update 
It was updated to version 1.2 back in May. I have never update this blog since. But go check it out!
[Bitcoin Price Alert v2](https://play.google.com/store/apps/details?id=com.mark.law.bitcoinpricealert)
### Android Usage
I incorporated a few basic android components:
1. Asynctask - to grab the price in the background.
2. Jsoup - to parse the website 
3. Google Play Services - to display advertisements.
4. Spinner - to show dropdown box
5. Alarm Manager - to setup an alarm to call the service in intervals

##Download Link
[Bitcoin Price Alert v1](https://play.google.com/store/apps/details?id=com.mark.law.bitcoinpricealert)
