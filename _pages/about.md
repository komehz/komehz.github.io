---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hi, I am Dr. Martin Esugo, a Research Fellow in Data and Artificial Intelligence at Birmingham City University. I empower healthcare startups through AI/machine learning solutions as part of the West Midlands Health Tech Innovation Accelerator Programme. My expertise includes Python, data science, and deep learning techniques, spanning applications from predictive models to large language models. My doctoral research in traffic flow forecasting refined my data-driven insights and skills, allowing me to adapt these approaches to new challenges. Beyond my professional focus, I am fascinated by physics, computational modelling and the global energy transition. Let's [connect](https://komehz.github.io/contact/) and explore how AI can innovate within your field.

### Highlights:

| Core Technical Skills    | Research Background      | Broader Interests        |
|:-------------------------|:-------------------------|:-------------------------|
| - Python                 | - Traffic Engineering    | - Data Insights          |
| - Data Science           | - Control Engineering    | - Startups               |
| - Machine Learning       | - Predictive Modelling   | - Healthcare             |
| - Deep Learning          | - Simulation Modelling   | - Energy Transition      |
| - LLMs                   | - Physics                | - Future Transport       |
| - Computer Vision        |                          |                          |
| - TensorFlow             |                          |                          |


<h2>Recent Publications</h2>
{% assign sorted_publications = site.publications | sort: 'date' | reverse %}
{% for publication in site.publications limit:3 %}
- "{{ publication.citation }}" [Read more]({{ publication.paperurl }})
{% endfor %}

<h2>Recent Blog Posts</h2>
<ul>
    {% for post in site.posts limit:1 %}
    <li>
        <a href="{{ post.url }}">{{ post.title }}</a> - {{ post.date | date: "%B %d, %Y" }}
        <p>{{ post.excerpt }}</p>
    </li>
    {% endfor %}
</ul>


<!--
## Recent Blog Post

Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over -- just be sure to save the markdown files! Finally, you can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).


Recent Publication
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Example: editing a markdown file for a talk

For more info
------
More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
-->
