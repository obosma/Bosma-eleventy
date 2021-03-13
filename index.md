---
layout: template.html
title: Best Ice Cream Flavours Project
tags: page
---
# This is my {{ title }}
Top Flavours of 2020
    <ul>
        {% for flavour in flavours -%}
            <li> {{ flavour }}</li>
        {% endfor -%}
    </ul>
