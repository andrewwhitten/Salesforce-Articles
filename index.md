---
layout: page
title: Salesforce Blog Archive
---

{% for tag in site.tags %}
  <h3>{{ tag[0] }}</h3>
  <ul>
    {% for post in tag[1] %}
      <li><a href="{{ post.url }}">{{ post.date | date: "%B %Y" }} - {{ post.title }}</a></li>
    {% endfor %}
  </ul>
{% endfor %}


## Salesforce articles by Andrew Whitten


### Blog Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>


### Older Posts

I wrote a number of articles at Wordpress - https://andrewwhitten.wordpress.com/ . Some that may be of interest are:

1) Things to know about Permissions before starting Salesforce Functions - https://andrewwhitten.wordpress.com/2021/11/25/things-to-know-about-permissions-before-starting-salesforce-functions/
2) Salesforce LWC inheritance and code sharing - https://andrewwhitten.wordpress.com/2021/05/12/salesforce-lwc-inheritance-and-code-sharing/
3) Data Quality Analysis in Salesforce files with MuleSoft Anypoint - https://andrewwhitten.wordpress.com/2021/02/13/analyze-files-in-salesforce-with-mulesoft-anypoint/
4) Creating a Salesforce Permission Set subset from multiple Profiles - https://andrewwhitten.wordpress.com/2020/12/29/creating-a-salesforce-permission-set-subset-from-multiple-profiles/


### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/andrewwhitten/Salesforce-Articles/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.
