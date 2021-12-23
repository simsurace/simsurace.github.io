---
layout: page
title: home
---

<img align="right" class="image-cropper" src="{{site.url}}/assets/portrait.jpg" width="33%" />

# Simone Carlo Surace
### *Data Scientist based in Switzerland*
[Email](mailto:simone.surace@gmail.com) | [LinkedIn](https://www.linkedin.com/in/simone-carlo-surace/){:target="_blank"} | [GitHub](https://github.com/simsurace){:target="_blank"} | [Publications](https://scholar.google.com/citations?user=psJEOB0AAAAJ&hl=de&oi=ao){:target="_blank"} 
<!-- --- [MathOverflow](https://mathoverflow.net/users/69603/s-surace?tab=profile) -->

## Interests
- Time series analysis / stochastic processes
- Reinforcement learning / control problems
- Scientific / high-performance computing 
- Information geometry & optimal transport 

## Experience
*2021--now*: [Data / ML scientist](cv/artificialy.html), [Artificialy SA](https://www.artificialy.com/){:target="_blank"}, Lugano  
*2021*: [Scientific advisor](cv/olz.html), [OLZ AG](https://olz.ch/){:target="_blank"}, Bern  
*2021--2021*: [Freelance researcher](cv/booth.html), [Booth School of Business](https://www.chicagobooth.edu/){:target="_blank"}, Chicago (remote)  
*2018--2021*: [Postdoctoral researcher](cv/postdoc2.html), University of Bern  
*2016--2017*: [Postdoctoral researcher](cv/postdoc1.html), [INI](https://www.ini.uzh.ch/en.html){:target="_blank"}, University and ETH Zurich  
*2011--2016*: [Doctoral researcher](cv/doc.html), University of Bern  
<!-- *2011--2015*: Tutor for secondary and high-school students in Math/Physics  
*2009--2013*: Part-time high school teacher in Math/Physics  
*2008--2011*: Part-time scientific intern/collaborator, [TOFWERK](https://www.tofwerk.com/){:target="_blank"}, Thun   -->
[more details...](cv.html)

## Education
2016: [PhD Neuroscience](assets/phd-thesis-surace.pdf), University of Bern  
2011: [MSc Theoretical Physics](assets/master-thesis-surace.pdf){:target="_blank"}, University of Bern  
2009: BSc Physics/Mathematics, University of Bern

<!-- ## Blog posts -->

<ul>
{% for post in site.posts %}
<li>
  <a href="{{post.url}}">{{post.title}}</a> ({{post.date | date: '%D' }})
</li>
{% endfor %}
</ul>
