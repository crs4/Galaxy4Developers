---
layout: default
title: Home
---

## Welcome to the documentation site of the           
## [Training Course on Galaxy for Bioinformatics tool developers](https://elixir-iib-training.github.io/website/2017/07/03/Galaxy-Cagliari.html)

___

#### Here you can find a tutorials collection to support the course.

{::nomarkdown}

{% assign pages_list = site.pages | sort:"url" %}
    {% for node in pages_list %}
      {% if node.title != null %}
        {% if node.layout == "page" %}
          <a class="sidebar-nav-item{% if page.url == node.url %} active{% endif %}" href="{{site.url}}{{ node.url }}">{{ node.title }}
          <p class="note">{{node.summary}}</p></a>
        {% endif %}
      {% endif %}
    {% endfor %}
{:/}


### Authors and Contributors

 * [Rossano Atzeni](http://www.crs4.it/peopledetails/357/rossano-atzeni)
 * [Gianmauro Cuccuru](http://www.crs4.it/peopledetails/195/gianmauro-cuccuru)
 * [Marco Tangaro](https://elixir-iib-training.github.io/website/instructors/marco_tangaro.html)
 * [Paolo Uva](http://www.crs4.it/peopledetails/183/paolo-uva)


### Contributing

If you've found mistakes or any other kind of material you think should be shared through this repository you can:

1. Fork this repository.
2. Add your content on the appropriate page.
3. Commit your changes.
4. Submit a pull request.
