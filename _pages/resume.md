---
layout: default
permalink: /resume/
title: resume
nav: true
nav_order: 4
description: This is a description of the page. You can modify it in '_pages/cv.md'. You can also change or remove the top pdf download button.
---

{% assign pdf_path = "assets/pdf/Anh_Vu_Resume.pdf" | relative_url %}

<h1> resume </h1> [<a target="_blank" rel="noopener noreferrer" href="{{ pdf_path | relative_url }}"> pdf </a>]

<object style="width: 100%; height: 800px;" data="{{pdf_path | relative_url}}" type="application/pdf"></object>
