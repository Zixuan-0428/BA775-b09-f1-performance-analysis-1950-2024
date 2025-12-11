# Analyzing Formula One Performance Data and Trends (1950–2024)
BA775-Business Analysis Toolbox
Boston University
## Project Overview

This project conducts a comprehensive analysis of performance determinants in the Formula One World Championship from 1950 to 2024. Using a relational dataset hosted on Kaggle and accessed through BigQuery, the study examines how speed, qualifying performance, reliability, pit-stop strategy, and environmental conditions influence both race-level and season-level outcomes. Through systematic data cleaning, integration, and exploratory analysis, the project identifies key performance patterns and evaluates how different factors interact to shape competitive results.

## Contributors

Mika Ismayilli — mikaism@bu.edu | Riya Poojary — jya17@bu.edu | Xinying (Charlotte) Wang — cwang56@bu.edu | TzuHsuan (Vina) Liu — vina26@bu.edu | Xiaoyan Wang — wxiaoyan@bu.edu | Zixuan (Casseay) Zhu — zzx0428@bu.edu

## Motivation

Formula One is a performance-intensive sport in which extremely small time differences can significantly affect driver and constructor outcomes. While substantial literature and commentary exist on individual race results, fewer analyses examine multiple performance dimensions concurrently using a data-centered approach. This project aims to fill this gap by quantifying how preparation, driver skill, technical reliability, and environmental factors jointly influence competitiveness across races and seasons. The findings contribute to a broader understanding of sports analytics, resource allocation, and strategic planning in high-performance environments.

## Data Sources

The dataset used in this analysis originates from the Formula 1 World Championship database (1950–2024) available on Kaggle. It includes relational tables covering circuits, drivers, constructors, races, qualifying, lap times, pit stops, results, and standings. These tables are linked by key identifiers such as raceId, driverId, and constructorId, enabling multi-level analysis across race, team, and driver dimensions.

An Entity-Relationship Diagram (ERD) was generated to map table connections and guide the construction of the integrated analytical dataset.

## Dashboard Visualizations

### 📊 Tableau Dashboard 1
<div class='tableauPlaceholder' id='viz1765423357046' style='position: relative'><noscript><a href='#'><img alt='Dashboard 1 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;F1&#47;F1Viz1&#47;Dashboard1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='F1Viz1&#47;Dashboard1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;F1&#47;F1Viz1&#47;Dashboard1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='zh-CN' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1765423357046');                    var vizElement = divElement.getElementsByTagName('object')[0];                    if ( divElement.offsetWidth > 800 ) { vizElement.style.width='1000px';vizElement.style.height='827px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='1000px';vizElement.style.height='827px';} else { vizElement.style.width='100%';vizElement.style.height='1577px';}                     var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);       
### 📊 Tableau Dashboard 2
<div class='tableauPlaceholder' id='viz1765423480087' style='position: relative'><noscript><a href='#'><img alt='Dashboard 2 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;F1&#47;F1Viz1&#47;Dashboard2&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='F1Viz1&#47;Dashboard2' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;F1&#47;F1Viz1&#47;Dashboard2&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='zh-CN' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1765423480087');                    var vizElement = divElement.getElementsByTagName('object')[0];                    if ( divElement.offsetWidth > 800 ) { vizElement.style.width='1000px';vizElement.style.height='827px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='1000px';vizElement.style.height='827px';} else { vizElement.style.width='100%';vizElement.style.height='1577px';}                     var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);    

## Slide Deck
https://www.canva.com/design/DAG6lDLpzRE/qvxLuUAfyWAKKXxbEGYjEA/edit
