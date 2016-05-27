---
layout: map_page
logo: ismb.svg
title: BioVis at ISMB (BioVis@ISMB)
location: Orlando, Florida
date: July 8th, 2016
main_venue: ISMB 2016
main_venue_url: http://www.iscb.org/ismb2016
permalink: /ismb/
---

<div class="row center-align">
    <div class="col m4 s12 event-page-menu-block">
     <i class="material-icons large">people</i>
     <h3>Call for Participation</h3>
     
     <a class="btn waves-effect waves-light" href="{{site.baseurl}}/cfp_ismb" type="submit" name="action">View CfP</a>
    </div>
    
    <div class="col m4 s12 event-page-menu-block">
     <i class="material-icons large">file_upload</i>
     <h3>Submission Info</h3>
     <a class="btn waves-effect waves-light" href="{{site.baseurl}}/submission_ismb" type="submit" name="action">View Submission Info</a>
    </div>
    
    <div class="col m4 s12 event-page-menu-block">
        <i class="material-icons large">border_color</i>
        <h3>Registration</h3>
        <a class="btn waves-effect waves-light" href="{{site.baseurl}}/registration_ismb" type="submit" name="action">Register</a>
    </div>

    <div class="col m4 s12 event-page-menu-block">
     <i class="material-icons large">list</i>
     <h3>Program</h3>
     <a class="btn waves-effect waves-light" href="{{site.baseurl}}/program_ismb" type="submit" name="action">View Program Details</a>
    </div>
</div>

<br/>

<br/>

<div class="row left-align">    
      <div class="col s12 m6">
            <h4>Important Dates</h4>
            <p><strong>Highlights and New Research Submission:</strong><br>
            <emph>EXTENDED</emph> {{ site.ISMB_hl_and_nresearch_submission }}</p>
            <p><strong>ISMB Poster Submission Deadline:</strong><br>{{ site.ISMB_deadline_poster }} </p>
            <p><strong>Highlights, New Research and Poster Notification:</strong><br>
            {{ site.ISMB_hl_and_nresearch_notiication }} </p>
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

