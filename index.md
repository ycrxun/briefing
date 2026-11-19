---
layout: default
title: Morning Briefing
---

# 每日简报

{% assign reports = site.pages
  | where_exp: "p", "p.path contains 'data/daily_briefings/'"
  | where_exp: "p", "p.path contains '.md'"
  | sort: "path"
  | reverse %}

<ul>
{% for report in reports %}
  {% assign report_date = report.name
    | remove: "Morning_Report_"
    | remove: ".md" %}

  <li>
    <a href="{{ report.url | relative_url }}">
      {{ report_date }}
    </a>
  </li>
{% endfor %}
</ul>
