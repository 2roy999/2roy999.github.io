---
layout: page
permalink: /teaching/
title: Teaching
<!-- description: Materials for courses you taught. Replace this text with your description. -->
nav: true
---

### Department of Mathematics - Tel-Aviv University

#### *Teaching Assistant*

{% for c in site.data.courses %}
  <p style="text-align:left;">
    <b>{{c.name}}</b>
    <span style="float:right;">
        <i>{{c.semster}}</i>
    </span>
</p>
{% endfor %}
