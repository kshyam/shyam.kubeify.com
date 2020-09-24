---
layout: default
title: About
permalink: /about/
image: kubernetes-developer.jpeg
---
<!-- begin c-hero -->
<div class="hero">
  <div class="container">
    <div class="row">
      <div class="col col-7 col-t-12 last-item">
        <div class="hero__content">
          <h1 class="hero__title">{{ site.data.settings.author.say-hello }}</h1>
          {%   assign today = site.time | date: '%y'      %}
          {%   assign start = '20-01-2008 04:00:00' | date: '%y'  %}
          {%   assign exp = today | minus: start     %}
          <p class="hero__subtitle"> I have {{ exp }} + years of experience devloping and delivering web and mobile apps with passion of cloud native DevOps engineeering practices. I love to build and manage large scale IT products using open source tools with scalable architecture. 
          <br>
          <br>
           I'm using 
           golang, 
           ruby, 
           python, 
           reactjs, 
           ruby on rails, 
           go buffalo,
           Relational DB like mysql/postgres, 
           NoSql DB like mongodb,
           Cloud and Orchitaration tools like
           Amazon cloud, Google Cloud, Azure Cloud, Digital Ocean and many more.
           Kubernetes, 
           Docker, 
           CircleCI, 
           Razorops CI/CD, 
           Github, Gitlab etc.</p>
        </div>
      </div>
      <div class="col col-5 col-t-12">
        <div class="hero__image">
          <img src="{{site.baseurl}}/images/{{ site.data.settings.author.image }}" alt="{{ site.data.settings.author.image }}">
        </div>
        <br>
         <div class="hero__social">
            {% include contact-link.html %}
          </div>
      </div>
    </div>
  </div>
</div>
<!-- end hero -->

