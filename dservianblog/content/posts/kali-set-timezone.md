---
title: "Set the Correct Time Zone on Kali"
date: 2025-12-05T23:03:50+01:00
tags:
  - linux
---

1. Open a terminal and check your current time zone
```
timedatectl
```
2. List available time zones
```
timedatectl list-timezones | grep Europe
```
3. Set the time zone
```
sudo timedatectl set-timezone Europe/Madrid
```

You can enable ntp with the following command
```
sudo timedatectl set-ntp on
```
