---
title: "Contact Dr. Saharnaz Babaei-Balderlou"
date: 2024-12-01
layout: gridlay
sitemap: true
permalink: /contact/
---

<style> :root { --shb-maroon: #6d2144; --shb-navy: #04144c; --shb-rule: #d9dee6; --shb-field: #fbfbfc; } .shb-section-label { font-size: 0.78rem; letter-spacing: 0.13em; text-transform: uppercase; color: var(--shb-maroon); font-weight: 700; margin: 38px 0 4px; } .shb-section-note { color: #55607a; margin-bottom: 18px; } /* Two scheduling routes */ .shb-book { display: grid; grid-template-columns: repeat(auto-fit, minmax(240px, 1fr)); gap: 16px; margin-bottom: 10px; } .shb-book a { display: block; padding: 22px 20px; border: 1px solid var(--shb-rule); border-left: 5px solid var(--shb-maroon); border-radius: 6px; background: #fff; color: var(--shb-navy); text-decoration: none; transition: transform 0.15s ease, box-shadow 0.15s ease; } .shb-book a:hover, .shb-book a:focus { transform: translateY(-2px); box-shadow: 0 4px 14px rgba(4, 20, 76, 0.12); text-decoration: none; color: var(--shb-navy); } .shb-book strong { display: block; font-size: 1.12rem; margin-bottom: 3px; } .shb-book span { font-size: 0.9rem; color: #55607a; } .shb-book i { color: var(--shb-maroon); margin-right: 8px; } /* Message form */ .shb-form { border: 1px solid var(--shb-rule); border-radius: 6px; padding: 26px; background: #fff; } .shb-form label { display: block; font-weight: 600; color: var(--shb-navy); margin-bottom: 5px; font-size: 0.95rem; } .shb-form .shb-optional { font-weight: 400; color: #7b8494; font-size: 0.85rem; } .shb-form input, .shb-form select, .shb-form textarea { width: 100%; padding: 10px 12px; margin-bottom: 18px; border: 1px solid #c6ccd8; border-radius: 4px; background: var(--shb-field); font-size: 1rem; color: #1b2233; } .shb-form input:focus, .shb-form select:focus, .shb-form textarea:focus { outline: 3px solid rgba(109, 33, 68, 0.35); outline-offset: 1px; border-color: var(--shb-maroon); background: #fff; } .shb-form textarea { min-height: 150px; resize: vertical; } .shb-form button { background: var(--shb-maroon); color: #fff; border: none; border-radius: 4px; padding: 12px 30px; font-size: 1rem; font-weight: 600; cursor: pointer; } .shb-form button:hover { background: #55182f; } .shb-privacy { font-size: 0.88rem; color: #55607a; border-top: 1px solid var(--shb-rule); margin-top: 6px; padding-top: 14px; } .shb-hp { position: absolute; left: -9999px; } @media (prefers-reduced-motion: reduce) { .shb-book a { transition: none; } } </style>

## Let's get in touch

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

<!-- Google Forms Embedded Contact Form -->
<div id="contact-form" style="text-align: center; margin-top: 30px;">
  <iframe src="https://docs.google.com/forms/d/e/1FAIpQLSe63XzX9lzUBdukcZN6LdVDhOBaMNdSWHtnP_tHjAMySzZTZg/viewform?embedded=true" width="640" height="1063" frameborder="0" marginheight="0" marginwidth="0">Loading…</iframe>
</div>

---

