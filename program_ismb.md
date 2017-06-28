---
layout: page
title: Program BioVis@ISMB
permalink: /program_ismb_beta/
back_title: ISMB
back_url: ismb
---
<br>
## BioVis@ISMB 2017 Program

### July 24, 2017


### Program

<em>**BioVis will take place in [Hall 4](https://www.iscb.org/cms_addon/conferences/ismbeccb2017/biovis.php) at the Prague Congress Centre**</em>
<br>
<br>

<!-- WELCOME --->
<div>
    <div class="sumTime2">10:00 - 10:15</div>
    <div>
        <div class="sumContent">BioVis Welcome</div>
          <div class="sumDetail" style="padding-left:120px;"><i>Jan and Marc</i></div>
    </div>
</div>

<hr class="style-one">

<!-- SESSION 1 --->

<div>
    <div class="sumTime2"> 10:15 - 12:30</div>
    <div>
        <div class="sumContent">Networks and Spatial Data</div>
    </div>
    <div class="sumDetail" style="padding-left:120px;"><i>Session Chair: TBD</i> </div>
    <div class="sumDetail" style="padding-left:120px;font-size:12px;"><i>(* indicates presenting author)</i> </div>
</div>


<div>
    <div class="sumTime2" style="font-size:15px;color:#21a186;">10:15 - 11:00</div>
    <div>
        <div class="sumContent" style="font-size:15px;color:#21a186;">Keynote</div>
        <div class="sumContent" style="padding-left:120px;font-size:15px;color:#21a186;">Visual analytics for spatial transcriptomics: from single cell to tissue and back</div>
          <div class="sumDetail" style="padding-left:120px;font-size:15px;color:#21a186;"><i> Speaker: <b> Boudewijn Lelieveld</b>, Leiden University Medical Center, Netherlands</i>
          </div>
    </div>
</div>



{% for paper in site.data.program2017%}
{% if paper.session == "session1"%}
  <div>
      <div class="sumTime" style="padding-top:5px;"> {{paper.start}} - {{paper.end}}</div>
      <div>
          <div class="ttile" style="padding-left:120px; padding-top:5px;"><b>{{paper.title}}</b></div>
      </div>
      <div class="sumDetail" style="padding-left:120px;"> <em>Authors:</em> {{paper.authors}}</div>
  </div>
{% endif %}
{% endfor %}

<!-- SESSION 2 --->
<hr class="style-one">

<div>
    <div class="sumTime2"> 14:00 - 16:00</div>
    <div>
        <div class="sumContent">Mutations and Next Generation Sequencing</div>
    </div>
    <div class="sumDetail" style="padding-left:120px;"><i>Session Chair: TBD</i> </div>
    <div class="sumDetail" style="padding-left:120px;font-size:12px;"><i>(* indicates presenting author)</i> </div>
</div>


<div>
    <div class="sumTime2" style="font-size:15px;color:#21a186;">14:00 - 14:45</div>
    <div>
        <div class="sumContent" style="font-size:15px;color:#21a186;">Keynote</div>
        <div class="sumContent" style="padding-left:120px;font-size:15px;color:#21a186;">Just a tool, or a science? The role of visualization in biology</div>
          <div class="sumDetail" style="padding-left:120px;font-size:15px;color:#21a186;"><i> Speaker: <b> Miriah Meyer </b>, University of Utah, USA</i>
          </div>
    </div>
</div>

{% for paper in site.data.program2017%}
{% if paper.session == "session2"%}
  <div>
      <div class="sumTime" style="padding-top:5px;"> {{paper.start}} - {{paper.end}}</div>
      <div>
          <div class="ttile" style="padding-left:120px; padding-top:5px;"><b>{{paper.title}}</b></div>
      </div>
      <div class="sumDetail" style="padding-left:120px;"> <em>Authors:</em>  {{paper.authors}}</div>
  </div>
{% endif %}
{% endfor %}


<!-- SESSION 3 --->
<hr class="style-one">

<div>
    <div class="sumTime2"> 16:30 - 17:40</div>
    <div>
        <div class="sumContent">Machine Learning and Medicine</div>
    </div>
    <div class="sumDetail" style="padding-left:120px;"><i>Session Chair: TBD</i> </div>
    <div class="sumDetail" style="padding-left:120px;font-size:12px;"><i>(* indicates presenting author)</i> </div>
</div>


{% for paper in site.data.program2017%}
{% if paper.session == "session3"%}
  <div>
      <div class="sumTime" style="padding-top:5px;"> {{paper.start}} - {{paper.end}}</div>
      <div>
          <div class="ttile" style="padding-left:120px; padding-top:5px;"><b>{{paper.title}}</b></div>
      </div>
      <div class="sumDetail" style="padding-left:120px;"> <em>Authors:</em>  {{paper.authors}}</div>
  </div>
{% endif %}
{% endfor %}

<!-- CLOSING REMARKS AND POSTER SESSION -->
<hr class="style-one">
<div>
    <div class="sumTime2">17:40 - 18:00</div>
    <div>
        <div class="sumContent">Closing Remarks</div>
          <div class="sumDetail" style="padding-left:120px;"><i>Jan and Marc</i></div>
    </div>
</div>

<hr class="style-one">


<div>
    <div class="sumTime2">18:00 - 19:00</div>
    <div>
        <div class="sumContent">Poster Session</div>
          <div class="sumDetail" style="padding-left:120px;"><i>Details to be announced</i></div>
    </div>
</div>
