---
title: Photo Gallery
summary: A collection of my photographs
date: '2024-10-04'

type: widget_page
---

{{< gallery album="hobby" >}}

---
# This goes in a separate content/hobby/index.md file:

{{< gallery-album 
    album="hobby" 
    images="
      image1.jpg:Caption for image 1
      image2.jpg:A beautiful sunset
      image3.jpg:Mountain landscape
      image4.jpg:Urban photography
      image5.jpg:Portrait shot
      image6.jpg:Nature close-up
      image7.jpg:Black and white composition
      image8.jpg:Street photography
      image9.jpg:Architecture detail
      image10.jpg:Macro photography
    " 
>}}