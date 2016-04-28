---
layout: home
---

<div class="row">

        <div class="home-info-container col s12">
              <p>The BioVis meetings are intended to educate, inspire, and engage visualization researchers in problems in biological data visualization, as well as bioinformatics and biology researchers in state-of-the-art visualization research.</p>
        </div>

        <div class="blue-section col s12">
        <div class="container">
              <p class="hide-on-small-only">The BioVis Interest Group organizes the annual BioVis conference. In its first five years, these BioVis
              conferences were organized as 2-day SIGs (Special Interest Groups) alternating each year between
              <a href="http://ieeevis.org" target="_new">IEEE VIS</a> and <a href="https://www.iscb.org/about-ismb" target="_new">ISMB</a>.
              <br/><br/>In 2016, however, there will be two meetings; a symposium with IEEE VIS (BioVis@VIS), and a SIG meeting with ISMB (BioVis@ISMB)
              </p>


            <div class="row ">
                <a href="{{site.baseurl}}/ieeevis">
                <div class="col s12 m4">
                    <div class="row event center-align">
                      <div class="col s12">
                        <img src="{{ site.baseurl }}/images/logos/ieee.svg" width="40%">
                      </div>
                      <div class="col s12 event-details">
                        <div class="event-name">IEEE VIS 2016</div>
                        <div class="event-subtitle">Symposium</div>
                        <div class="event-location">Baltimore, USA</div>
                        <div class="event-date">October 23rd 2016</div>
                      </div>
                    </div>
                </div>
                </a>

                <a href="{{site.baseurl}}/ismb">
                <div class="col s12 m4">
                    <div class="row event center-align">
                        <div class="col s12">
                            <img src="{{ site.baseurl }}/images/logos/ismb.svg" width="40%">
                        </div>

                        <div class="col s12 event-details">
                            <div class="event-name">ISMB 2016</div>
                            <div class="event-subtitle">SIG Meeting</div>
                            <div class="event-location">Orlando, Florida</div>
                            <div class="event-date">July 8th 2016</div>
                        </div>
                    </div>
                  </div>
                  </a>

                  <a href="{{site.baseurl}}/dataContest_dream">
                  <div class="col s12 m4">
                      <div class="row event center-align">
                          <div class="col s12">
                              <img src="{{ site.baseurl }}/images/logos/dream.svg" width="40%">
                          </div>

                          <div class="col s12 event-details">
                              <div class="event-name">Dream 2016</div>
                              <div class="event-subtitle">Data Analysis Contest</div>

                          </div>
                      </div>
                    </div>
                    </a>

                </div>



                <p class="hide-on-small-only">The BioVis meetings are intended to educate, inspire, and engage visualization
                  researchers in problems in biological data visualization, as well as bioinformatics
                  and biology researchers in state-of-the-art visualization research. The symposiums
                  serve as a platform for researchers from these fields to increase the impact
                  of data visualization approaches in biology, and to initiate interdisciplinary
                  collaborations.</p>

                </div>
                </div>

                <div class="row grey-section center-align">
                    <div class="container">

                        <div class="col s12 m12 center-align">
                            <h4><i class="material-icons" style="font-size: .9em">date_range</i> Important Dates</h4>
                        </div>
                          <div class="col s12 m6">
                             <h4><a href="{{site.baseurl}}/ieeevis">BioVis@VIS</a></h4>
                                <p><strong>Paper Submission Deadline:</strong><br>{{ site.IEEE_deadline_submission }} </p>
                                <p><strong>Author Notification:</strong><br>{{ site.IEEE_deadline_notification }} </p>
                                <p><strong>Camera Ready Submission:</strong><br>{{ site.IEEE_deadline_camera }} </p>
                                <p><strong>VIS Poster Submission Deadline:</strong><br>{{ site.IEEE_deadline_poster }} </p>

                          </div>
                          <div class="col s12 m6">
                             <h4><a href="{{site.baseurl}}/ismb">BioVis@ISMB</a></h4>
                                <p><strong>Highlights and New Research Submission:</strong><br>
                                <emph>EXTENDED</emph> {{ site.ISMB_hl_and_nresearch_submission }}</p>
                                <p><strong>ISMB Poster Submission Deadline:</strong><br>{{ site.ISMB_deadline_poster }} </p>
                                <p><strong>Highlights, New Research and Poster Notification:</strong><br>
                                {{ site.ISMB_hl_and_nresearch_notiication }} </p>

                          </div>
                    </div>
                </div>

                <!-- ADDING A NEWS FEED -->
                <div class="row lightgrey-section center-align">
                    <div class="container">

                        <div class="col s12 m12 center-align">
                            <!-- <h4><i class="material-icons" style="font-size: .9em">announcement</i> News</h4> -->
                            <h4> News </h4>
                        </div>
                          <div class="col s12 m4">
                             <h4><a href="{{site.baseurl}}/ieeevis">BioVis@VIS</a></h4>

                             {% for post in site.posts %}
                               {% capture category %}{{post.event}}{% endcapture %}
                               {% if category == "ieee" %}
                                   <ul>
                                   <li><a href="{{ post.url }}">{{ post.title }}</a></li>
                                   </ul>
                               {% endif %}
                             {% endfor %}

                          </div>
                          <div class="col s12 m4">
                             <h4><a href="{{site.baseurl}}/ismb">BioVis@ISMB</a></h4>
                             <ul class="post-list">
                             {% for post in site.posts %}
                               {% capture category %}{{post.event}}{% endcapture %}
                                {% if category == "ismb" %}
                                <li class="post-list-item">
                                   <span class="post-list-title">
                                     {{ post.date | date: "%-d %b %Y" }} | {{ post.title }}
                                   </span>
                                   <span class="post-list-excerpt">
                                     {{ post.excerpt }}
                                     <a class="post-list-link" href="{{ post.url | prepend: site.baseurl }}">More...</a>
                                   </span>              
                                 </li>
                                {% endif %}
                               {% endfor %}
                             </ul>

                          </div>

                          <div class="col s12 m4">
                             <h4><a href="{{site.baseurl}}/dream">BioVis@DREAM</a></h4>

                             {% for post in site.posts %}
                               {% capture category %}{{post.event}}{% endcapture %}
                               {% if category == "dream" %}
                                   <ul>
                                   <li><a href="{{ post.url }}">{{ post.title }}</a></li>
                                   </ul>
                               {% endif %}
                             {% endfor %}

                          </div>
                    </div>
                </div>

                <!-- END ADDING A NEWS FEED -->

                    <div class="row center-align">
                    <div class="container">
                        <div class="col s12 m6">

                            <h4>Affiliates</h4>
                            <p> BioVis 2016 is an official SIG of <a href="https://www.iscb.org/ismb2016"> ISMB 2016</a></p>
                                <a href="https://www.iscb.org">
                                    <img src="{{site.baseurl}}/images/sponsors/ISCB.jpg" alt="ISCB"/>
                                </a>
                             </p>
                             <br/>
                             <p>

                             We also acknowledge the support of BMC:<br/>

                             <img src="{{site.baseurl}}/images/sponsors/publications_BMC.jpg" alt="BMC"> <br/>
                             Please check out our <a href="http://www.biomedcentral.com/bmcbioinformatics/series/BioVis2014">thematic series</a>
                                    in conjunction with BioVis 2014 and the
                             <a href="http://www.biomedcentral.com/bmcproc/supplements/8/S2">proceedings</a> in conjunction with BioVis 2013.
                             <br/>
                             </p>
                        </div>
                        <div class="col s12 m6">
                            <h4>Sponsors</h4>
                            <p>We are grateful to our invaluable sponsors who contribute to prizes and the running costs of BioVis!

                            <br/><br/>
                            <a href="https://www.rstudio.com/" target="_new">
                            <img src="{{site.baseurl}}/images/sponsors/RStudio.png" width="140px">
                            </a><br/><br/>
                            <a href="https://www.sbgenomics.com/" target="_new">
                            <img src="{{site.baseurl}}/images/sponsors/sbg.png" width="250px">
                            </a><br/><br/>
                            <a href="http://www.nvidia.com/content/global/global.php" target="_new">
                            <img src="{{site.baseurl}}/images/sponsors/NVIDIA.png" width="80px">
                            </a>

                        </div>
                    </div>
                </div>
        </div>
