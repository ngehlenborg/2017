---
layout: map_page
logo: ieee.svg
title: BioVis at IEEE VIS (BioVis@VIS)
location: Baltimore, Maryland
date: October 23rd, 2016
main_venue: IEEE VIS 2016
main_venue_url: http://ieeevis.org/year/2016/info/vis-welcome/welcome
permalink: /ieeevis/
---
<br>
<div style="background-color: #f2f2f2; border-style: solid; border-color: #009e9d; padding: 5px;">
<p> Attended BioVis@VIS 2016? Please <a href="https://goo.gl/0Z1TiF">fill out our survey</a> and tell us what you thought! </p>
</div>

<div class="row center-align">
    <div class="col m4 s12 event-page-menu-block">
     <i class="material-icons large">people</i>
     <h3>Call for Participation</h3>

     <a class="btn waves-effect waves-light" href="{{site.baseurl}}/cfp_vis" type="submit" name="action">View CfP</a>
    </div>

    <div class="col m4 s12 event-page-menu-block">
     <i class="material-icons large">file_upload</i>
     <h3>Paper Submission Info</h3>
     <a class="btn waves-effect waves-light" href="{{site.baseurl}}/papers" type="submit" name="action">View Submission Info</a>
    </div>


    <div class="col m4 s12 event-page-menu-block">
         <i class="material-icons large">file_upload</i>
         <h3>Poster Submission Info</h3>
         <a class="btn waves-effect waves-light" href="{{site.baseurl}}/posters_ieee" type="submit" name="action">View Submission Info</a>
        </div>

</div>

<div class="row center-align">

    <div class="col m4 s12 event-page-menu-block">
        <i class="material-icons large">create</i>
        <h3>Design Contest</h3>
        <a class="btn waves-effect waves-light" href="{{site.baseurl}}/designContest_vis" type="submit" name="action">Design Contest</a>
    </div>

    <div class="col m4 s12 event-page-menu-block">
        <i class="material-icons large">list</i>
        <h3>Program</h3>
        <!--<a class="btn waves-effect waves-light" href="{{site.baseurl}}/program_ieee" type="submit" name="action">Program</a>-->
        <a class="btn waves-effect waves-light" href="{{site.baseurl}}/program_ieee" type="submit" name="action">Program</a>
    </div>
</div>

<br/>
<br/>

<div class="row left-align">
    <div class="col s12 m6">
        <h4>Important Dates</h4>
        <p><strong>Paper Submission Deadline:</strong><br>{{ site.IEEE_deadline_submission }} </p>
        <p><strong>Author Notification:</strong><br>{{ site.IEEE_deadline_notification }} </p>
        <p><strong>Camera Ready Submission:</strong><br>{{ site.IEEE_deadline_camera }} </p>
        <p><strong>VIS Poster Submission Deadline:</strong><br>{{ site.IEEE_deadline_poster }} </p>
    </div>

    <div class="col s12 m6">
        <h4>Latest News</h4>
        <ul class="post-list">
         {% for post in site.posts %}
           {% capture category %}{{post.event}}{% endcapture %}
            {% if category == "ieee" %}
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
