---
layout: default
title: Archive
---
# Archive of Projects & Blog

## Projects
- [DigiNext-Final-Data-Challenge](https://github.com/AA-2003/BaSalam-Project)
- [Travel Purpose & Cancellation Prediction](https://github.com/AA-2003/ML-/tree/main/mrbilit%20dataset)
- [Rule-Based Search Suggestion System](https://github.com/AA-2003/ML-/tree/main/search_suggestion)
- [Hand Gesture Mouse Control](https://github.com/AA-2003/Mouse-control-by-hand)

## Blog
{% for post in site.posts %}
<h3>{{ post.title }}</h3>
<p>{{ post.date | date: "%B %d, %Y" }} - <a href="{{site.baseurl}}/{{ post.url }}">Read more</a></p>
{% endfor %}
