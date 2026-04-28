---
layout: home
author_profile: true
---

## Welcome

I am an Assistant Professor in the Department of Statistics at Brigham Young University. My research focuses on 

- Bayesian hierarchical modeling,
- Clinical trial design, and 
- Spatial and time-series methods.
- Medical and environmental applications  


## Recent Posts

{% raw %}
{% for post in site.posts limit:5 %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}
{% endraw %}