---
title: "moving to a gallery view"
subtitle: ""
date: 2022-12-05 T10:10:00-04:00
draft: false
author: ""
authorLink: ""
description: "getting to a more graphic, interactive world"
license: ""
images: ["/featured-meeting-1.jpg"]

tags: []
categories: []

---

### A different take....
// {{ partial "image-gallery" (dict "context" . "gallery_dir" "album") }}
{{< image-gallery gallery_dir="album" >}}

{{< mermaid >}}
pie
    "Dogs" : 386
    "Cats" : 85
    "Rats" : 15
{{< /mermaid >}}
