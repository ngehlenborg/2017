---
layout: page
title: Program BioVis@Vis
permalink: /program_ieee/
back_title: IEEE VIS 2016
back_url: ieeevis
---
## BioVis@Vis 2016 Program

### October 23rd, 2016

<hr class="style-one">
<div>
    <div class="sumTime2">08:30 - 08:35</div>
    <div>
        <div class="sumContent">BioVis Welcome</div>
          <div class="sumDetail" style="padding-left:120px;"><i> Liz Marai</i></div>
           <div style="padding-left:120px;"><a href= "{{site.baseurl}}/posters_ieeevis_Accepted"><i>List of Accepted Posters</i></a></div>
    </div>
</div>

<hr class="style-one">

<div>
    <div class="sumTime2">08:35 - 09:35</div>
    <div>
        <div class="sumContent">Keynote Lecture</div>
        <div class="sumContent" style="padding-left:120px;">Visualization: The power of alternate representations</div>
          <div class="sumDetail" style="padding-left:120px;"><i> Speaker: <b> Sheelagh Carpendale</b>, University of Calgary, Canada</i>
          <a href="#carpendale"> (Abstract and Speaker Bio)</a></div>
    </div>
</div>

<div>
    <div class="sumTime2">09:35 - 10:15</div>
    <div>
        <div class="sumContent">Primer</div>
        <div class="sumContent" style="padding-left:120px;">Statistical dances: why no statistical analysis is reliable and
        what to do about it</div>

        <div class="sumDetail" style="padding-left:120px;"><i>Session Chair: Eamonn Maguire</i></div>

        <div class="sumDetail" style="padding-left:120px;"><i>Speaker: <b>Pierre Dragicevic</b>, Inria, France</i>
        <a href="#dragicevic"> (Abstract and Speaker Bio)</a></div>
    </div>
</div>

<!--------------- COFFEE BREAK------------------->
<hr class="style-one">
<div>
    <div class="sumTime2">10:15 - 10:30</div>
    <div>
        <div class="sumContent">Coffee / Tea Break</div>
    </div>
</div>

<hr class="style-one">

<!--------------- Papers Session 1 ------------------->


<div>
    <div class="sumTime2"> 10:30 - 12:10</div>
    <div>
        <div class="sumContent">BioVis Papers: Abstract Data and Pathway Visualization </div>
    </div>
    <div class="sumDetail" style="padding-left:120px;"><i>Session Chair: Michel Westenberg</i> </div>
    <div class="sumDetail" style="padding-left:120px;font-size:12px;"><i>(* indicates presenting author)</i> </div>
</div>

<!-- Load Papers automatically from spreadsheet -->
{% for paper in site.data.papers%}
{% if paper.session == "Papers-01"%}
  <div>
      <div class="sumTime" style="padding-top:5px;"> {{paper.start}} - {{paper.end}}</div>
      <div>
          <div class="ttile" style="padding-left:120px; padding-top:5px;"><b>{{paper.title}}</b></div>
      </div>
      <div class="sumDetail" style="padding-left:120px;"> {{paper.authors}}</div>
  </div>
{% endif %}
{% endfor %}

<!--------------- LUNCH BREAK------------------->
<hr class="style-one">
<div>
    <div class="sumTime2">12:10 - 14:00</div>
    <div>
        <div class="sumContent">Lunch Break</div>
    </div>
</div>
<hr class="style-one">

<!--------------- Papers Session 2 ------------------->


<div>
    <div class="sumTime2"> 14:00 - 14:50</div>
    <div>
        <div class="sumContent">BioVis Papers: Protein and Microscopy Data Visualization</div>
    </div>
    <div class="sumDetail" style="padding-left:120px;"><i>Session Chair: Carsten Goerg</i> </div>
    <div class="sumDetail" style="padding-left:120px;font-size:12px;"><i>(* indicates presenting author)</i> </div>
</div>


<!-- Load Papers automatically from spreadsheet -->
{% for paper in site.data.papers%}
{% if paper.session == "Papers-02"%}
  <div>
      <div class="sumTime" style="padding-top:5px;"> {{paper.start}} - {{paper.end}}</div>
      <div>
          <div class="ttile" style="padding-left:120px; padding-top:5px;"><b>{{paper.title}}</b></div>
      </div>
      <div class="sumDetail" style="padding-left:120px;"> {{paper.authors}}</div>
  </div>
{% endif %}
{% endfor %}

<!--------------- COFFEE BREAK------------------->
<hr class="style-one">
<div>
    <div class="sumTime2">15:40 - 16:00</div>
    <div>
        <div class="sumContent">Coffee / Tea Break</div>
    </div>
</div>

<hr class="style-one">

<!--------------- CHALLENGE AND DESIGN CONTEST ------------------->
<div>
    <div class="sumTime2">16:00 - 16:45</div>
    <div>
        <div class="sumContent">Challenges Session</div>
        <div class="sumDetail" style="padding-left:120px;"><i>Session Chair:  Nils Gehlenborg </i></div>

        <div class="sumDetail" style="padding-left:120px;"><i>Challenge: <b> An introduction to Microbiome Data Visualization</b> </i></div>

        <div class="sumDetail" style="padding-left:120px;"><i>Speaker: <b> Eric Franzosa</b>, Harvard School of Public Health</i>   <a href="#franzosa"> (Abstract and Speaker Bio)</a></div>
    </div>
</div>

<div>
    <div class="sumTime2">16:45 - 17:15</div>
    <div>
        <div class="sumContent">Design Contest Presentations </div>
        <div class="sumDetail" style="padding-left:120px;"><i>Session Chair:  Eamonn Maguire </i></div>
        <div class="sumDetail" style="padding-left:120px;">Contestant 1: Hamid Younesy (presented by Torsten Möller), <i>Simon Fraser University</i></div>
        <div class="sumDetail" style="padding-left:120px;">Contestant 2: Christian Stolte, <i>New York Genome Center</i></div>
    </div>
</div>

<hr class="style-one">

<!--------------- LAST STUFF ------------------->
<div>
    <div class="sumTime2">17:15 - 17:25</div>
    <div>
        <div class="sumContent">Poster Fast Forward</div>
        <div class="sumDetail" style="padding-left:120px;"><i>Session Chair: Michel Westenberg </i></div>
        <div style="padding-left:120px;"><a href= "{{site.baseurl}}/posters_ieeevis_Accepted"><i>List of Accepted Posters</i></a></div>
    </div>
</div>

<div>
    <div class="sumTime2">17:25 - 17:35</div>
    <div>
        <div class="sumContent">BioVis Data Contest </div>
        <div class="sumDetail" style="padding-left:120px;"><i>Speaker: Raghu Machiraju </i></div>
    </div>
</div>

<div>
    <div class="sumTime2">17:35 - 17:55</div>
    <div>
        <div class="sumContent">Awards Ceremony and Closing Remarks </div>
        <div class="sumDetail" style="padding-left:120px;"><i> Jan Aerts </i></div>
    </div>
</div>
<hr class="style-one">

<!--------------- Poster Sessions ------------------->
<div>
    <div class="sumTime2">19:00 - 21:00</div>
    <div>
        <div class="sumContent">Poster Reception @ VIS Opening Reception</div>
        <div class="sumDetail" style="padding-left:120px;"><i>Key Blrm 7-12 + South Foyer </i></div>
        <div style="padding-left:120px;"><a href= "{{site.baseurl}}/posters_ieeevis_Accepted"><i>List of Accepted Posters</i></a></div>
    </div>
</div>
<hr class="style-one">


<h3>Keynote Speaker</h3>

<a name="carpendale"></a>
<div class="talk">
    <div class="ttitle">Visualization: The power of alternate representations
        <!--{% if talk.slides %}
        <span class="tspeaker" style="float: right;"><a href="{{ site.baseurl }}/files/{{talk.slides}}">Download
            Slides</a></span>
        {% endif %}-->
    </div>
    <div><span class="tspeaker"><a href="http://pages.cpsc.ucalgary.ca/~sheelagh/wiki/pmwiki.php">Sheelagh Carpendale</a></span>, <span>University of Calgary</span></div>

    <div class="tportrait"><img src="{{ site.baseurl}}/images/speakers/sCarpendale.jpg" style="width: 250px;" alt="S.Carpendale">
    </div>

    <div class="tbioabstract">

        <div class="tabstract"><b>Abstract:</b>
        To visualize data one of the first steps is to develop a visual representation. This representation is a result of a mapping by which the data can be specified. Much has been said of about the power of these visual representations. Simon (1981) said that solving a problem is simply a matter of representing so as to make the solution transparent – implying that finding the right representation solves the problem. Card et al. (1998) said that interactive visual representations can amplify our cognition – can in effect make us smarter.  In spite of this, the small box in the visualization creation pipeline that signifies the development of the visual representation remains one of the least unpacked. Through examples from my own work and others’, I will discuss the power and potential of alternate visual representations.
        </div>

        <div class="tbio"><b>Bio:</b>
        Sheelagh Carpendale is a Professor in Computer Science at the University of Calgary where she holds a Canada Research Chair in Information Visualization and NSERC/AITF/SMART Technologies Industrial Research Chair in Interactive Technologies. She has many received awards including the E.W.R. NSERC STEACIE Memorial Fellowship; a BAFTA (British Academy of Film & Television Arts Interactive Awards); an ASTech Innovations in Technology award; and the CHCCS Achievement Award, which is presented periodically to a Canadian researcher who has made a substantial contribution to the fields of computer graphics, visualization, or human-computer interaction. She has served in such roles as Papers, Program, or Conference Chair for IEEE InfoVis, ACM Interaction Tabletops and Surfaces, and Computational Aesthetics and has received both the IEEE and ACM recognition of service awards. She is a co-director of the Interactions Lab and leads the Innovations in Visualization (InnoVis) research group and initiated the interdisciplinary graduate program, Computational Media Design. Her research on information visualization, large interactive displays, and new media draws on her dual background in Computer Science and Visual Arts.</div>
    </div>
</div>



<h3>Primer Speaker</h3>

<a name="dragicevic"></a>
<div class="talk">
    <div class="ttitle">Statistical dances: why no statistical analysis is reliable and what to do about it
        <!--{% if talk.slides %}
        <span class="tspeaker" style="float: right;"><a href="{{ site.baseurl }}/files/{{talk.slides}}">Download
            Slides</a></span>
        {% endif %}-->
    </div>
    <div><span class="tspeaker"><a href=" http://www.aviz.fr/badstats">Pierre Dragicevic</a></span>, <span> Inria, France </span></div>

    <div class="tportrait"><img src="{{ site.baseurl}}/images/speakers/pDragicevic.jpeg" style="width: 250px;" alt="P.Dragicevic">
    </div>

    <div class="tbioabstract">

        <div class="tabstract"><b>Abstract:</b>
        It is now widely recognized that we need to improve the way we report empirical data in our scientific papers. More formal training in statistics is not enough. We also need good "intuition pumps" to develop our statistical thinking skills. In this talk I explore the basic concept of statistical dance. The dance analogy has been used by Geoff Cumming to describe the variability of p-values and confidence intervals across replications. I explain why any statistical analysis and any statistical chart dances across replications. I discuss why most attempts at stabilizing statistical dances (e.g, increasing power or applying binary accept/reject criteria) are either insufficient or misguided. The solution is to embrace the uncertainty and messiness in our data. We need to develop a good intuition of this uncertainty and communicate it faithfully to our peers. I give tips for conveying and interpreting interval estimates in our papers in a honest and truthful way.
        </div>

        <div class="tbio"><b>Bio:</b>
        Pierre Dragicevic is working in the Aviz team at Inria in France as a permanent research scientist. He studies information visualization and human-computer interaction. He co-signed many research articles with p-values until he got frustrated and discovered a vast literature on statistical reform. In 2014 he banished p-values from all his publications. Since then, he has been promoting an approach to better statistical communication based on charts, interval estimation and nuanced interpretations.
        </div>
    </div>
</div>

<h3> Challenge Speaker</h3>
<a name="franzosa"></a>
<div class="talk">
    <div class="ttitle">A Introduction to microbiome data visualization
        <!--{% if talk.slides %}
        <span class="tspeaker" style="float: right;"><a href="{{ site.baseurl }}/files/{{talk.slides}}">Download
            Slides</a></span>
        {% endif %}-->
    </div>
    <div><span class="tspeaker"><a href="http://franzosa.net/">Eric Franzosa</a></span>, <span> Harvard School of Public Health </span></div>

    <div class="tportrait"><img src="{{ site.baseurl}}/images/speakers/eFranzosa.jpg" style="width: 250px;" alt="E.Franzosa">
    </div>

    <div class="tbioabstract">

        <div class="tabstract"><b>Abstract:</b>
        This talk will introduce the concepts and challenges of visualizing the results of microbial community (microbiome) sequencing projects. We will begin with an overview of current amplicon - and shotgun sequencing-based approaches for generating taxonomic and functional profiles of microbiome samples. We will then discuss methods for effectively representing high-dimensional microbiome profiles in low-dimensional space (ordination). This will include an introduction to the ecological distance measures that underlie microbiome ordination and distinguish it from other dimensionality reduction applications. Following this, we will cover additional topics relevant to visualization of microbiome data, including embedding stratified microbiome profiles on phylogenetic trees, and methods for augmenting common graphical data representations to handle the "quirks" of microbiome data (including compositionality, zero-inflation, and high dynamic range). We will close with an overview of existing platforms for visualizing microbiome data and by pointing out open challenges in the field.
        </div>

        <div class="tbio"><b>Bio:</b>
        Eric received a Bachelors in Biophysics (2006) from Brown University and a Ph.D. Bioinformatics (2011) from Boston University, where he studyied protein structure-evolution relationships with Prof. Brandon Xia. In 2012 he joined Curtis Huttenhower's lab at Harvard School of Public Health/Broad Institute to research metatranscriptomics and microbiome personalization. In 2015 he transitioned to staff scientist role in the Huttenhower lab and is currently researching efficient methods for microbiome functional profiling (HUMAnN2) and expanding the Human Microbiome Project. He is also involved in various Microbiome and bioinformatics workshops and education initiatives.
        </div>
    </div>
</div>
