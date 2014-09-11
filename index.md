---
layout: page
title: DevF blog
tagline: La escuela de hackers hispanoparlantes
---
{% include JB/setup %}

    
## Sample Posts

This blog contains sample posts which help stage pages and blog data.
When you don't need the samples anymore just delete the `_posts/core-samples` folder.

    $ rm -rf _posts/core-samples

Here's a sample "posts list".

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>


<ul class="posts">
	{% for post in site.posts %}	
    <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
    <p><small><strong>{{ post.date | date: "%B %e, %Y" }}</strong> . {{ post.category }} . <a href="http://erjjones.github.com{{ post.url }}#disqus_thread"></a></small></p>			
{% endfor %}	

</ul>




