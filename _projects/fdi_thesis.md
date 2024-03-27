---
layout: page
cover-title: Passing Style Analyser
cover-description: Final thesis for the "Football Data Intelligence" course 2022 (by SICS and Soccerment)
title: Passing Style Analyser
description: Webapp for the final thesis of the "Football Data Intelligence" course 2022 (by SICS and Soccerment)
img: assets/img/passing_style_analyser/cover.jpg
importance: 1
category: Personal
---
This web application has been developed as the final thesis of the ["Football Data Intelligence" course 2022](https://www.sics.it/corso-football-data-intelligence/) organised by [SICS](https://www.sics.it/en/) and [Soccerment](https://soccerment.com/).

<div class="links" style="margin-top: -10px; margin-left: -5px; margin-bottom: 20px">
    <a href="/assets/pdf/certificates/FDI_Certificato_Purificato_Erasmo.pdf" class="btn btn-sm z-depth-0" role="button">Certificate</a>
</div>


## Links

<i class="fa-solid fa-globe"></i> [WebApp](https://erasmopurif-passing-style-analysis--home-xkeymq.streamlit.app/)

<i class="fa-brands fa-github"></i> [GitHub Repo](https://github.com/erasmopurif/passing_style_analysis)

<i class="fa-solid fa-file-pdf"></i> [Thesis (Italian)](/assets/pdf/thesis/purificato_fdi_thesis.pdf)


## App description

With this application, you can analyse the passing style of each Serie A 2021/22 team.

The two main functionalities available are described below.

### Full Pitch & Field Tilt Networks

After selected a **single matchday** or a **range of matchdays**, it is possible to analyze:
* a single team,
* two teams, or
* all the 20 Serie A teams,
by viewing their **passing network** in the **most used formation** for the selected matchdays, either visualizing the **full-pitch** or **field-tilt** passing network.

Additionally, the user can select the number of minimum passes to be displayed in the passing networks (Note that for multiple matchdays, this value is multiplied by the number of selected matchdays).

<!-- Fig: Full Pitch & Field Tilt Networks - Selection page -->
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/passing_style_analyser/full_pitch_field_tilt_home.jpg" title="ui_full_pitch" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Full Pitch & Field Tilt Networks - Selection page 
</div>

<!-- Fig: Full Pitch Network - Multiple matchdays/Single team -->
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/passing_style_analyser/multiple_match_single_team.png" title="multiple_match_single_team" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Full Pitch Network - Multiple matchdays/Single team 
</div>

<!-- Fig: Full Pitch Network - Multiple matchdays/Two teams -->
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/passing_style_analyser/multiple_match_two_teams.png" title="multiple_match_two_teams" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Full Pitch Network - Multiple matchdays/Two teams 
</div>

<!-- Fig: Full Pitch Network - Multiple matchdays/All teams -->
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/passing_style_analyser/multiple_match_all_teams.png" title="mult_match_all_teams" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Full Pitch Network - Multiple matchdays/All teams 
</div>


### Match Status Networks

After selected a **single matchday** or a **range of matchdays**, and a **team**, it is possible to analyze the full-pitch passing network for each **match status** (i.e. winning, drawing, losing) and view their barycenter in the "passing" scenario.

Additionally, the user can decide whether or not to keep the goalkeeper in the barycenter computation, and select the number of minimum passes to be displayed in the passing networks (Note that in this case, for multiple matchdays, this value is **NOT** multiplied by the number of selected matchdays).

<!-- Fig: Match Status Networks - Selection page -->
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/passing_style_analyser/match_status_network_home.jpg" title="match_status_network_home" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Match Status Networks - Selection page 
</div>

<!-- Fig: Match Status Network - Multiple matchdays - Team info -->
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/passing_style_analyser/ms_multiple_match_info.png" title="ms_multiple_match_info" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Match Status Network - Multiple matchdays - Team info 
</div>

<!-- Fig: Match Status Network - Multiple matchdays - Pitch -->
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/passing_style_analyser/ms_multiple_match_pitch.png" title="ms_multiple_match_pitch" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Match Status Network - Multiple matchdays - Pitch 
</div>