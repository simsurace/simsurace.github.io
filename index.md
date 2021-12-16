---
layout: page
title: home
---

<img align="right" class="image-cropper" src="https://avatars3.githubusercontent.com/simsurace?v=3&amp;s=200" alt="simsurace" srcset="https://avatars3.githubusercontent.com/simsurace?v=3&amp;s=200 1x, https://avatars3.githubusercontent.com/simsurace?v=3&amp;s=400 2x, https://avatars3.githubusercontent.com/simsurace?v=3&amp;s=600 3x, https://avatars3.githubusercontent.com/simsurace?v=3&amp;s=800 4x" width="200" height="200" />

# Simone Carlo Surace
### *Data Scientist based in Switzerland*
[Email](mailto:simone.surace@gmail.com) --- [LinkedIn](https://www.linkedin.com/in/simone-carlo-surace/) --- [GitHub](https://github.com/simsurace) --- [Publications](https://scholar.google.com/citations?user=psJEOB0AAAAJ&hl=de&oi=ao) 
<!-- --- [MathOverflow](https://mathoverflow.net/users/69603/s-surace?tab=profile) -->

## Interests
- Time series analysis / stochastic processes
- Reinforcement learning / control problems
- Scientific / high-performance computing 
- Information geometry & optimal transport 

## Experience
*2021--now*: Data / ML Scientist, [Artificialy SA](https://www.artificialy.com/), Lugano  
*2021*: Scientific Advisor, [OLZ AG](https://olz.ch/), Bern  
*2021--2021*: Freelance Researcher, [Booth School of Business](https://www.chicagobooth.edu/), Chicago  
*2018--2021*: Postdoctoral Researcher, University of Bern  
*2016--2017*: Postdoctoral Researcher, [INI](https://www.ini.uzh.ch/en.html), University and ETH Zurich  
*2011--2016*: Doctoral Researcher, University of Bern  
*2008--2011*: Part-time scientific intern/collaborator, [TOFWERK](https://www.tofwerk.com/), Thun  
*2009--2013*: Part-time high school teacher in Math/Physics  

## Education
2016: PhD Neuroscience, University of Bern  
2011: MSc Theoretical Physics, University of Bern  

## Blog posts

<ul>
{% for post in site.posts %}
<li>
  <a href="{{post.url}}">{{post.title}}</a> ({{post.date | date: '%D' }})
</li>
{% endfor %}
</ul>
