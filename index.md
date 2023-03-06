---
layout: default
title: Your Name
---

# Hi, I'm Swagat Bhattacharyya!

I'm a graduate research fellow at Georgia Institute of Technology. Welcome to my website, where I share what all I have been upto!

## Latest Posts

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}

## Contact

You can reach me at sbhattac8@gatech(dot)edu.