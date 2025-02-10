---
layout: home
---

![JHU OSPO Logo](RGB Sheriden Libraries-OSPO Unit Lockup_horizontal.blue.png)

# Free and Open Source Project Fund Playbook

The Free and Open Source Project Fund (FOSSProF) is a grant program run by the Johns Hopkins University Open Source Programs Office (OSPO) that provides funding and support to open source software projects and practitioners at JHU. 

This playbook is provided as a resource for JHU OSPO staff as well as staff at academic OSPOs or similar offices who would like to run a grant program similar to FOSSProF in support of campus open-source software development. 

## Pages

{% if site.posts.size > 0 %}
{% for post in site.posts %}
* [{{ post.title }}]({{ post.url | relative_url }})
{% endfor %}
{% endif %}
