---
layout: page
title: Accepted Papers for BioVis@ISMB 2017
permalink: /papers_ismb_accepted/
back_title: ISMB
back_url: ismb
---

{% for paper in site.data.program2017 %}
{% if paper.type == "PAPER" %}
<div class ="talk">
  <table>
  <tr>
    <td width="300px">
      <a href ="{{ site.baseurl}}/files/{{paper.image}}"> <img style="padding-right: 10px;" src="{{ site.baseurl }}/files/{{paper.image}}" alt="{{paper.title}}" height="250" width="250"></a>
    </td>
  <td>
    <div class="ttitle"> {{paper.title}}</div>
    <div>
      <br>
      <span class="tspeaker">{{paper.authors}}</span>
      <p>
      <em>Presentation Info: "{{paper.sessionTitle}}" session  between {{paper.start}} to {{paper.end}}</em>
      </p>
    </div>
    <div>
      <p>{{paper.abstract}}</p>
    </div>
    <div><span><a href="{{ paper.doi }}">Link to Full Paper</a></span></div>

  </td>
  </tr>
  </table>

</div>

{% endif %}
{% endfor %}
