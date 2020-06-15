---
layout: post
title: "Climate Change Visualization"
date: 2019-12-18
excerpt: " A data science visualizing project portraying a compeling story on Climate Change: R"
tags: [sample post, images, test]
feature: https://scx2.b-cdn.net/gfx/news/2018/9-climatechange.jpg
comments: true
---

# Global Climate Change

Now more than ever before, there is an urgent need to make climate change data accessible to everyone in the general public.
This is an important first step in having an informed discussion about ways in which we can contribute to a more sustainable
planet in the future. It is not a secret that our climate is changing faster than ever before and the consequences of 
this change on life are tremendous. Global climate change will have a profound effect on the ocean by altering temperature, 
CO<sub>2</sub>-acidification, and dissolved oxygen (DO) in the ocean. The consequences of climate change on land are even more severe 
than that of the ocean. Longer, more intense droughts threaten crops, wildlife, and freshwater supplies. From polar bears in 
the Arctic to marine turtles off the coast of Africa, our planet’s diversity of life is at risk from an ever-changing climate 
(worldwildlife.org). For these reasons, it critical to study how important climate change variables (example Carbon-dioxide 
and Methane gas emissions) are changing over time and what other factors may be correlated with such variables. 
It is important to note that though not every country is contributing to climate change, the consequence of the warming 
planet is global.

There are a great number of data out there showing an association between increased temperatures, rising
sea levels, melting polar caps, and other variables indicative of a changing world. We are interested in exploring the global 
rise in greenhouse gases such as carbon dioxide gas and methane gas (CO<sub>2</sub> and CH<sub>4</sub>: proxies for climate change) and their strong
associations with change in land-temperatures, the size of glaciers, sea level, and change in forest percentage over time.

### We plan to achieve following things in this project:
- Visualize the global rise in CO<sub>2</sub> and CH<sub>4</sub> emmission across time(1880-2010)by countries and region  
  - Interactive scatter plots
  - Importance plots
- Visualize the change in Land-temperature, Sea level, Glacier-Mass, and Forest Area over time (1880-2010)
- Juxtapose the association of rise in green house gases (climate chage) and its consequence in sea level rise, land temperatire rise,
decrease in glacier mass and forest area across the world

### How users can get started with the project?
- [Climate_Shiny.Rmd](https://github.com/gurungkshitij/climate_change/blob/master/Climate_Shiny.Rmd) is the main shinny app file
- [Climaechange-datacleaning.Rmd](https://github.com/gurungkshitij/climate_change/blob/master/Climaechange-datacleaning.Rmd) is the 
data cleaning code 
- After you download all the files, change the directories of the datasets as you read in the csv files in Rmd code metioned above
- Everythign should run smoothly. 
- The final version of the published shinny app work in this [link](https://gurung.shinyapps.io/Climate_Shiny/)



<form class="container">
<div markdown="0"><a href="https://gurung.shinyapps.io/Climate_Shiny/" class="btn btn-success"> Final product</a></div>
<div markdown="0"><a href="https://github.com/gurungkshitij/climate_change" class="btn btn-info"> Source Codes</a></div>
</form>

<div class="container">
  <h2>Button Group</h2>
  <p>The .btn-group class creates a button group:</p>
  <div class="btn-group">
    <button type="button" a href="https://gurung.shinyapps.io/Climate_Shiny/" class="btn btn-primary">Final product</button>
    <button type="button" a href="https://github.com/gurungkshitij/climate_change" class="btn btn-info">Source Codes</button>
  </div>
</div>

<hr>
<figure class="half">
    <a href='/assets/img/ch4.jpg'><img src='/assets/img/ch4.jpg'></a>
    <a href='/assets/img/co2_country.jpg'><img src='/assets/img/co2_country.jpg'></a>
    <figcaption>Top cotributors of CO<sub>2</sub> and CH<sub>4</sub> </figcaption>
</figure>
        
<figure class="half">
	<a href='/assets/img/co2.jpg'><img src='/assets/img/co2.jpg'></a>
	<a href='/assets/img/sealevel.jpg'><img src='/assets/img/sealevel.jpg'></a>
    <figcaption>Association between CO<sub>2</sub> rise and Sealevel rise</figcaption>
</figure>


