---
layout: page
title: Projects
permalink: /projects/
---

# Projects

Explore our projects focused on creating better places for humans.

{% for project in site.projects %}
## [{{ project.title }}]({{ project.url }})

{{ project.description }}

{% if project.technologies %}
**Technologies:** {{ project.technologies | join: ", " }}
{% endif %}

[Learn more]({{ project.url }})

---
{% endfor %}
