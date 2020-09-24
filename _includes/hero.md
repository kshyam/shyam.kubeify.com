<!-- begin c-hero -->
{%   assign today = site.time | date: '%y' %}
{%   assign start = '01-01-2008 04:00:00' | date: '%y' %}
{%   assign exp = today | minus: start     %}

<div class="hero">
  <div class="container">
    <div class="row">
      <div class="col col-6 col-t-12 last-item">
        <div class="hero__content">
          <h1 class="hero__title">{{ site.data.settings.author.say-hello }}</h1>
          <p class="hero__subtitle">
            I have {{ exp }} + years of experience devloping and delivering web and mobile apps with passion of cloud native DevOps engineeering practices. I love to build and manage large scale IT products using open source tools with scalable architecture. 
          </p>
          <div class="hero__social">
            <span class="hero__social-title">Follow Me - </span>
            {% include contact-link.html %}
          </div>
        </div>
      </div>
      <div class="col col-6 col-t-12">
        <div class="hero__image">
          <img src="{{site.baseurl}}/images/{{ site.data.settings.author.image }}" alt="">
        </div>
      </div>
    </div>
  </div>
</div>
<!-- end hero -->