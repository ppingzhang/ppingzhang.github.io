<!-- Load icons type -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/jpswalsh/academicons/css/academicons.min.css">
<link rel=stylesheet href=https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css>

<!-- Avatar -->
{% if site.avatar %}  
<a class="image avatar"><img src="{{ site.url }}/{{ site.avatar }}" alt="avatar" /></a>
{% endif %}

<!-- Name -->
<h1>{{ site.title }}</h1>

<!-- Position -->
{% if site.position %}
<position style="font-size:1.10rem;">{{ site.position }}</position>
<br>
{% endif %}

<!-- Affiliation -->
{% if site.affiliation %}
<a href="{{ site.affiliation_link }}" rel="noopener"><autocolor>{{ site.affiliation }}</autocolor></a>
<br>
{% endif %}

<!-- Email -->
{% if site.email %}
<email style="font-size: 14px; font-family: 'Ubuntu Mono';">{{ site.email }}</email>
{% endif %}
<br>
<br>

<!-- Social Icons -->
<div class="social-icons">
  {% if site.google_scholar %}
  <a style="margin: 0 5px 0 0" href="{{ site.google_scholar }}">
    <i class="ai ai-google-scholar" style="font-size:1.2rem"></i>
  </a>  
  {% endif %}

  {% if site.orcid %}
  <a style="margin: 0 5px 0 0" href="{{ site.orcid }}">
    <i class="ai ai-orcid" style="font-size:1.2rem"></i>
  </a>  
  {% endif %}

  {% if site.github_link %}
  <a style="margin: 0 5px 0 0" href="{{ site.github_link }}">
    <i class="fab fa-github"></i>
  </a>
  {% endif %}

  {% if site.linkedin %}
  <a style="margin: 0 5px 0 0" href="{{ site.linkedin }}">
    <i class="fab fa-linkedin"></i>
  </a>
  {% endif %}
</div>

