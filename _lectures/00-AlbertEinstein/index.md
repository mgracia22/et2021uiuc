---
layout: default
usemathjax: true
title: On special relativity
author: Albert Einstein
institution: Swiss patent office
slides: slides.pdf
files:
  - file1.pdf
  - file2.ipynb
  - file3.mp4
recording: ""
---
{% include base.html %}

{%-capture abstract-%}
The abstract describing the lecture. In this lecture we will learn about

* ham
* spam
* eggs

and use $$\LaTeX$$ to display

$$\begin{equation}E = m c^2\end{equation}$$
{%-endcapture-%}

{% include lecture.md author=page.author institution=page.institution title=page.title abstract=abstract slides=page.slides files=page.files recording=page.recording%}

Anything else that should appear after the "front matter" stuff above.
