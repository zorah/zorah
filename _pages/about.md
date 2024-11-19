---
permalink: /
title: "Zorah Lähner - Personal Homepage"
excerpt: "Zorah Lähner - Assistant Professor at the University of Bonn - Geometry in Machine Learning group"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

You can find the homepage of my research group at [geometryinML.cs.uni-bonn.de](https://geometryinml.cs.uni-bonn.de/). This site is not actively maintained anymore.

I am an assistant professor (tenure track) and head of the "Geometry in Machine Learning" group at the University of Bonn, and part of the [Chair for Visual Computing](https://cg.cs.uni-bonn.de/) and the [Lamarr Institute](https://lamarr-institute.org/). I received my PhD from the Technical University of Munich and was a postdoctoral researcher at the University of Siegen. 
I am interested in how geometric properties can be used to form effective priors and guide optimization processes in geometric deep learning and 3D computer vision applications. For example, choosing a different representation can make a huge difference in the capabilities and efficiency of geometric data, particualarly in non-Euclidean domains. 




News
======
  <ul>{% assign items = site.news | sort: 'date' | reverse %}
{% for post in items limit:5 %}
    {% include archive-news.html %}
  {% endfor %}</ul>
