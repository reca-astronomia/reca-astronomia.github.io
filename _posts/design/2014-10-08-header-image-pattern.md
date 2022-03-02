---
layout: page
title:  "Header Image With Pattern"
subheadline:  "Headers With Style"
teaser: "Feeling Responsive allows you to use all kinds of headers. This example shows a header image in front of a pattern."
categories:
    - design
tags:
    - design
    - pattern
    - header
header:
    image: typewriter.jpg
    pattern: pattern_concrete.jpg
    caption: Image by Florian Klauer
    caption_url: "http://florianklauer.de/"
---
It's so easy to do. Just define in front matter an image and a pattern image. Instead of a pattern you can also use a color. Have a look at the [example with a background color]({{ site.url }}{{ site.baseurl }}/design/header-image-color/).
<!--more-->

## Front Matter Code

~~~
header:
    image: typewriter.jpg
    pattern: pattern_concrete.jpg
    caption: Image by Florian Klauer
    caption_url: "http://florianklauer.de/"
~~~



### All Header-Styles 
{: .t60 }

{% include list-posts tag='header' %}