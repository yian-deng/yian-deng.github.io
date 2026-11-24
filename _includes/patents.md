<h2 id="patents">Patents</h2>

<ol>
{% for patent in site.data.patents.main %}
  <li>
    <strong>{{ patent.title }}</strong><br>
    {{ patent.inventors }}<br>
    <em>{{ patent.patent_number }}</em>
    · {{ patent.status }}
    · {{ patent.year }}
  </li>
{% endfor %}
</ol>
