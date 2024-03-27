---
layout: page
cover-title: Goalkeeper Analysis - Serie A 2021/22
cover-description: Football Data Analysis project
title: Goalkeeper Analysis - Serie A 2021/22
description: Football Data Analysis project
img: assets/img/gk_analysis/cover.jpg
importance: 2
category: Personal
---
With this application, you can analyse the **stats** and **performance** of all the goalkeepers who played in the Serie A teams during the season 2021/22.

:warning: ***Important information***
* *The analysis considers only goalkeepers with at least **800 minutes** played.*
* *The visualisation of all charts has been optimised for a laptop screen of 15"*.


## Links

<i class="fa-solid fa-globe"></i> [WebApp](https://gk-analysis-serie-a-21-22.streamlit.app/)

<i class="fa-brands fa-github"></i> [GitHub Repo](https://github.com/erasmopurif/gk-analysis-serie-a-21-22)


## Data sources
The data used in this work are taken from various sources:
* [Transfermarkt](https://www.transfermarkt.com/): personal information and profile picture;
* [SICS](https://www.sics.it/) & [Soccerment](https://soccerment.com/): event data and advanced metrics (datasets provided during the 2nd Course on [Football Data Intelligence](https://www.sics.it/corso-football-data-intelligence/)).

## Analysis
The information that are provided through the application for analysing a goalkeeper are listed below.

When needed, specific description is provided within the analysis page.

### Personal information and basic statistics
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/gk_analysis/basic_info.jpg" title="ui_basic_info" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

### Specific goalkeeper metrics
Percentile rank vs all Serie A goalkeepers and individual scores.
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/gk_analysis/gk_metrics.jpg" title="ui_gk_metrics" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

### Goals conceded map
The heatmap displays the distribution of the goals conceded by the goalkeeper during the season, considering the point where the scorers made the shots.
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/gk_analysis/goals_map.jpg" title="ui_goals_map" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

### Goal kicks map
The heatmap displays the distribution of the goal kicks carried out by the goalkeeper during the season, considering the end-point of the pass.
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/gk_analysis/goal_kick_map.jpg" title="ui_goal_kick_map" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

### Passes distribution (*no goal kicks*) per match and average position in pass plays
For each selected matchday, on the left hand side, the chart displays the distribution of passes (no goal kicks) made by the goalkeeper. On the opposite side of the chart, the :blue[blue] line (and related point in the pitch) represents the average position of the goalkeeper in the pass plays during the selected match, while the :green[green] line represents the average position of the goalkeeper in the pass plays during the entire season.
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/gk_analysis/passes_avg_pos.jpg" title="ui_passes_avg_pos" class="img-fluid rounded z-depth-1" %}
    </div>
</div>