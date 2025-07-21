---
title: "Contact Dr. Saharnaz Babaei-Balderlou"
date: 2024-12-01
layout: gridlay
sitemap: true
permalink: /contact/
---

## <a href="#contact-icons">Get in Touch</a>

{% for member in site.data.pi %}

<div id="contact-icons" class="jumbotron">
<div class="row">
<div class="col-sm-12 text-center">
  <img src="/images/headshot.png" class="img-fluid" style="max-width:100%" alt="Headshot">
</div>
<div class="col-xs-12 text-center">
  <h3>{{ member.name }}</h3>
  <h4><i style="white-space: nowrap;">{{ member.info }}</i></h4>
   {% if member.email %}<a href="mailto:{{ member.email }}" target="_blank"><i class="fa fa-envelope-square fa-3x"></i></a> {% endif %}
   {% if member.cv %} <a href="https://saharnaz.org/cv/" target="_blank"><i class="ai ai-cv-square ai-3x"></i></a> {% endif %}
   {% if member.scholar %} <a href="{{ member.scholar }}" target="_blank"><i class="ai ai-google-scholar-square ai-3x"></i></a> {% endif %}
   {% if member.github %} <a href="{{ member.github }}" target="_blank"><i class="fab fa-github-square fa-3x"></i></a> {% endif %}
   {% if member.linkedin %} <a href="{{ member.linkedin }}" target="_blank"><i class="fab fa-linkedin fa-3x"></i></a> {% endif %}
   {% if member.orcid %} <a href="{{ member.orcid }}" target="_blank" title="ORCID"><i class="fab fa-orcid fa-3x"></i></a> {% endif %}
   {% if member.youtube %} <a href="{{ member.youtube }}" target="_blank"><i class="fab fa-youtube fa-3x"></i></a> {% endif %}
   {% if member.twitter %} <a href="{{ member.twitter }}" target="_blank"><i class="fa-brands fa-square-x-twitter fa-3x"></i></a> {% endif %}
   {% if member.instagram %} <a href="{{ member.instagram }}" target="_blank"><i class="fa-brands fa-square-instagram fa-3x"></i></a> {% endif %}
   {% if member.facebook %} <a href="{{ member.facebook }}" target="_blank"><i class="fab fa-facebook fa-3x"></i></a> {% endif %}

  <ul style="overflow: hidden">
    {% for education in member.education %}
      <li>{{ education | replace: "-","&#8211;" }}</li>
    {% endfor %}
  </ul>

</div>
</div>
</div>
{% endfor %}


---

<!-- Microsoft Forms Embedded Contact Form -->
<div id="contact-form" style="text-align: center; margin-top: 30px;">
  <iframe width="640px" height="800px" src="https://forms.office.com/r/ELk1cv88fC?embed=true" frameborder="0" marginwidth="0" marginheight="0" style="border: none; max-width:100%; max-height:100vh" allowfullscreen webkitallowfullscreen mozallowfullscreen msallowfullscreen></iframe>
</div>

---

