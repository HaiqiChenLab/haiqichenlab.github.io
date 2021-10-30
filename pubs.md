---
title: "RGL - Publications"
layout: gridlay
excerpt: "RGL -- Publications."
---


# **Publications**
<hr>
Here is a list of some representative publications. The full list can be found on [Google Scholar](https://scholar.google.com/citations?user=HoeBWvQAAAAJ&hl=en). #: corresponding author; \*: equal contribution. RGL members are highlighted in <b>bold</b>.

<div class="wrapper row3">
  <div id="container">
    <div class="full_width clear">
      <ol>
        {% for publication in site.data.publist %}
          <li>
            {{publication.authors}}. "{{publication.title}}." <i>{{publication.journal}}</i>; {{publication.date}}; PMID: {{publication.pmid}}; <a href="{{publication.pdf}}">[pdf]</a>
          </li>
          <br>
        {% endfor %}
      </ol>
    </div>
  </div>
</div>
