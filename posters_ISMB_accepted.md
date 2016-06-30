---
layout: page
title: Posters BioVis@ISMB
permalink: /posters_ismbAccepted/
back_title: ISMB 2016
back_url: ismb
---
## Accepted Posters for BioVIS@ISMB

{% for poster in site.data.posters %}
{% if poster.event == "ismb" %}
<div class ="talk">
  <table>
  <tr>
    <td width="200px">
      <a href ="{{ site.baseurl}}/files/{{poster.image}}"> <img style="padding-right: 10px;" src="{{ site.baseurl }}/files/{{poster.image}}" alt="{{poster.title}}" height="150" width="150"></a>
    </td>
  <td>
    <div class="ttitle">Poster: {{poster.title}}</div>
    <div><span class="tspeaker">{{poster.authors}}</span></div>
    <div><span><a href="{{ site.baseurl}}/files/{{poster.abstract}}">Download Full Abstract</a></span></div>
  </td>
  </tr>
  </table>
  <!--
  <div class="clearfix float-my-children">
    <div><img src="{{ site.baseurl }}/files/{{poster.image}}" alt="{{poster.title}}" height="125" width="125"></div>
    <div>
      <div class="ttitle">Poster: {{poster.title}}</div>
      <div><span class="tspeaker">{{poster.authors}}</span></div>
      <div><span><a href="{{ site.baseurl}}/files/{{poster.abstract}}">Download
          Full Abstract</a></span></div>
    </div>
  </div>
  -->
</div>

{% endif %}
{% endfor %}
