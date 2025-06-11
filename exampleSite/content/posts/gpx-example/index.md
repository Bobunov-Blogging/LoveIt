---
weight: 4
title: "GPX Example"
date: 2025-06-10T21:57:40+08:00
draft: false
description: "This article shows the basic usage of GPX shortcode."
images: []
tags: ["GPX", "Leaflet"]
categories: ["Markdown"]

lightgallery: true
---

This article offers a sample of basic Markdown syntax that can be used in Hugo content files.

<!--more-->

Leaflet map only


Leaflet-map with gpx track

{{< leaflet-map >}}
    {{< leaflet-track path="gpx-example/08-06-2025-Gudamakari.gpx" >}}
    {{< leaflet-elevation-profile  >}}
{{< /leaflet-map >}}