---
layout: page
title: home
---

<img align="right" class="image-cropper" src="{{site.url}}/assets/portrait.jpg" width="33%" />

# Simone Carlo Surace
### *Data Scientist based in Switzerland*
[Email](mailto:simone.surace@gmail.com) | [LinkedIn](https://www.linkedin.com/in/simone-carlo-surace/) | [GitHub](https://github.com/simsurace) | [Publications](https://scholar.google.com/citations?user=psJEOB0AAAAJ&hl=de&oi=ao) 
<!-- --- [MathOverflow](https://mathoverflow.net/users/69603/s-surace?tab=profile) -->

## Interests
- Time series analysis / stochastic processes
- Reinforcement learning / control problems
- Scientific / high-performance computing 
- Information geometry & optimal transport 

## Experience
*2021--now*: Data / ML scientist, [Artificialy SA](https://www.artificialy.com/), Lugano  
*2021*: Scientific advisor, [OLZ AG](https://olz.ch/), Bern  
*2021--2021*: Freelance researcher, [Booth School of Business](https://www.chicagobooth.edu/), Chicago (remote)  
*2018--2021*: Postdoctoral researcher, University of Bern  
*2016--2017*: Postdoctoral researcher, [INI](https://www.ini.uzh.ch/en.html), University and ETH Zurich  
*2011--2016*: Doctoral researcher, University of Bern  
*2009--2013*: Part-time high school teacher in Math/Physics  
*2008--2011*: Part-time scientific intern/collaborator, [TOFWERK](https://www.tofwerk.com/), Thun  

## Education
2016: PhD Computational Neuroscience, University of Bern  
2011: MSc Theoretical Physics, University of Bern  

<!-- ## Blog posts -->

<ul>
{% for post in site.posts %}
<li>
  <a href="{{post.url}}">{{post.title}}</a> ({{post.date | date: '%D' }})
</li>
{% endfor %}
</ul>
