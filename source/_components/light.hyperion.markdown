---
layout: page
title: "Hyperion"
description: "Instructions how to integrate Hyperion into Home Assistant."
date: 2015-10-25 22:43
sidebar: true
comments: false
sharing: true
footer: true
logo: hyperion.png
ha_category: Light
ha_release: 0.7.6
---

This platform allows you to integrate your [Hyperion](https://hyperion-project.org/wiki) into Home Assistant.

Hyperion is an opensource Ambilight implementation which runs on many platforms.

```yaml
# Example configuration.yaml entry
light:
  platform: hyperion
  host: 192.168.1.98
  # Optional
  port: 19444
```
