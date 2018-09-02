---
layout: blue_page
permalink: /cfp-committee/
title: CFP Committee
---

RustFest {{ site.location.city }} has a dedicated CfP committee. This ensures that voices from outside the conference organisers are heard during the selection process.

{% assign committee = site.people | where_exp: "person", "person.groups contains 'committee'" | sort: 'priority'  %}

<section>
  <h2>CfP Team</h2>
  <ul class="team">
    {% for person in committee %}
        <li>
          {% include cards/cfp-person.html person=person %}
        </li>
    {% endfor %}
  </ul>
</section>
