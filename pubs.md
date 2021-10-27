---
title: "ReGL - Publications"
layout: gridlay
excerpt: "ReGL -- Publications."
---


# **Publications**
<hr>
Here is a sampling of some of the papers that guide our lab's research. You can find the full list on [google scholar](https://scholar.google.com/citations?user=HoeBWvQAAAAJ&hl=en). #: corresponding author; \*: equal contribution. Members in RePL are highlighted in <b>bold</b>.

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
