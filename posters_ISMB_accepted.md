---
layout: page
title: Posters BioVis@ISMB
permalink: /posters_ismbAccepted/
back_title: ISMB
back_url: ismb
---
*TO BE ANNOUNCED SOON*

<!--
**Attention Poster Authors:**
When preparing accepted posters please note that your poster should not exceed the following dimensions: *46 inches wide by 45 inches high*. There will be 2 posters per side on the each poster board. One poster will be an odd number and the other will be an even number. View a diagram of the the poster board in pdf format [here](http://www.iscb.org/images/stories/ismb2016/downloads/ISMB2016-PosterSampler.pdf).


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

</div>

{% endif %}
{% endfor %}
-->
