---
layout: page
title: Dev.F. blog
tagline: La primera escuela de hackers de México y LatAm
---
{% include JB/setup %}

    
>## Info/Noticias/Avisos sobre el Dev.F.
> &nbsp;  
>
>Entérate de lo que está pasando dentro de la primera escuela de hackers en México y América Latina. Sigue en este blog nuestros avisos, noticias e información sobre el Dev.F. ¿Dudas? Escríbenos a info@devf.mx – y aplica HOY. :)


<ul class="posts">
	{% for post in site.posts %}	
    <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
    <p><small><strong>{{ post.date | date: "%B %e, %Y" }}</strong> . {{ post.category }} . <a href="http://erjjones.github.com{{ post.url }}#disqus_thread"></a></small></p>			
{% endfor %}	

</ul>




