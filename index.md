---
layout: default
title: "Our Collab Homepage"
author: "ur"
---

{% include navigation.html %}

# Building websites with GitHub

## Description

{{ site.descrition }}

Add a new section ‘Description’ to file index.md and add some description.

    From the GitHub interface, edit file index.md and add a new section called Description to it, with some text about the project.
    View the changes on the website.

[About this website](about.md)

This page was rendered at {{ site.time }} Author: {{ page.author }}

Have any questions [Please contact us via email](mailto:{{ site.email }})

{% include footer.html %}
