---
layout: map_page
logo: ismb.svg
title: BioVis at ISMB (BioVis@ISMB)
location: Prague, Czech Republic
date: July 24th 2017
main_venue_rln: Co-located
main_venue: ISMB 2017
main_venue_url: https://www.iscb.org/ismbeccb2017
permalink: /ismb/
---
<br>

<!--<div style="background-color: #f2f2f2; border-style: solid; border-color: #009e9d; padding: 5px;">
<h3> Additional details for BioVis@ISMB 2017 will be announced soon. In the meantime check out last year's event <a href="http://biovis.net/2016/ismb">BioVis@ISMB 2016</a> or our other event co-located with IEEE VIS  <a href="http://biovis.net/2016/ieeevis">BioVis@Vis 2016</a></h3>
</div>
-->
<div class="row center-align">
    <div class="col m4 s12 event-page-menu-block">
     <i class="material-icons large">people</i>
     <h3>Call for Participation</h3>

     <a class="btn waves-effect waves-light" href="{{site.baseurl}}/cfp_ismb" type="submit" name="action">View CfP</a>
    </div>

    <div class="col m4 s12 event-page-menu-block">
     <i class="material-icons large">file_upload</i>
     <h3>Submission Info</h3>
     <a class="btn waves-effect waves-light" href="{{site.baseurl}}/cfp_ismb/#subType" type="submit" name="action">View Submission Info </a>
    </div>

    <div class="col m4 s12 event-page-menu-block">
        <i class="material-icons large">border_color</i>
        <h3>Registration</h3>
        <a class="btn waves-effect waves-light" href="{{site.baseurl}}/registration_ismb" type="submit" name="action">Register</a>
    </div>

    <div class="col m4 s12 event-page-menu-block">
     <i class="material-icons large">list</i>
     <h3>Program</h3>
     <a class="btn waves-effect waves-light disabled" href="{{site.baseurl}}/program_ismb" type="submit" name="action">TBD</a>
    </div>
</div>

<br/>

<br/>

<div class="row left-align">    
      <div class="col s12 m6">
            <h4>Important Dates</h4>
            <p><strong>ISMB Proceedings Paper Submission Deadline:</strong>  {{ site.ismb_paper_submission_deadline }}</p>
            <p><strong>BioVis Proceedings Paper Submission Deadline:</strong>  {{ site.biovis_paper_submission_deadline }}</p>
            <p><strong>Poster Submission Deadline:</strong>  {{ site.ismb_poster_submission_deadline }}</p>
            <p><strong>Highlight Talks Submission Dedaline:</strong> {{ site.ismb_highlights_submission_deadline}}</p>  

      </div>


      <div class="col s12 m6">
          <h4>Latest News</h4>
          <ul class="post-list">
           {% for post in site.posts %}
             {% capture category %}{{post.event}}{% endcapture %}
              {% if category == "ismb" %}
              <li class="post-list-item-event">
                 <span class="date">{{ post.date | date: "%-d %b %Y" }}</span>
                 <span class="post-list-title">
                   <a class="post-list-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
                 </span>
                 <p class="post-list-excerpt">
                   {{ post.excerpt }}
                 </p>              
               </li>
              {% endif %}
             {% endfor %}
           </ul>
      </div>
</div>

<br/>
<br/>
