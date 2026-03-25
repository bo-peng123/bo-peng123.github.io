---
layout: about
title: about
permalink: /
subtitle: <a href='#'>Affiliations</a>. ITCS, Shanghai University of Finance and Economics

# profile:
  # align: right
  # image: prof_pic.jpg
  # image_circular: false # crops the image to make it circular
  # more_info: >
  #  <p>555 your office number</p>
  #  <p>123 your address street</p>
  #  <p>Your City, State 12345</p>

selected_papers: false # includes a list of papers marked as "selected={true}"
social: false # includes social icons at the bottom of the page

announcements:
  enabled: false # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

I am Bo Peng (彭博), a final-year Ph.D. student at [Shanghai University of Finance and Economics](https://www.sufe.edu.cn), where I am also a student member of the [Institute for Theoretical Computer Science](https://itcs.sufe.edu.cn). I am fortunate to be advised by [Zhihao Gavin Tang](http://zhihaotang.com). 

My research interests lie in theoretical computer science, with a particular focus on online algorithms and algorithmic game theory. Additionally, I am interested in the intersection of game theory, optimization, and machine learning. 

Prior to my Ph.D., I earned my Bachelor's degree from the School of Mathematical Sciences at Tongji University, and my Master's degree from the Academy of Mathematics and Systems Science, Chinese Academy of Sciences. Recently, I also spent time as a visiting student at [Nanyang Technological University (NTU)](https://www.ntu.edu.sg), working with Prof. [Xiaohui Bei](https://personal.ntu.edu.sg/xhbei/).  

<h2>Selected Publications</h2>
<div class="publications">
  {% bibliography --group_by none --query @*[selected=1]* %}
  {% bibliography --group_by none --query @*[selected=2]* %}
  {% bibliography --group_by none --query @*[selected=3]* %}
  {% bibliography --group_by none --query @*[selected=4]* %}
  {% bibliography --group_by none --query @*[selected=5]* %}
</div>

