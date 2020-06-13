---
layout: post
title: "Airbnb Rating Analysis"
date: 2019-12-18
excerpt: "Examples and code for displaying images in posts."
project: true
tags: [sample post, images, test]
feature: https://cdn2.lamag.com/wp-content/uploads/sites/6/2019/10/GettyImages-1158411199.jpg
comments: true
---

## Introduction

Have you ever booked or stayed at Airbnb?  If yes, you probably have considered the reveiws and ratings of properties before making your decision. Reviews and ratings of properties play a huge role in hospitality industry like Airbnb. Accurate and honest reviews of properties and services are valuable informations for clients and owners. A good place with high ratings attract clients, where as a bad rating warns or repels them. The owners of properties aim to deliver best service and comfort possible for thier client and expect decent reviews and ratings in return. 

Keeping in mind the importance of Airbnb rating, I decided to make a prediction model that considers different components (price, location, reaction of property owner, etc) and quantifies their impact on the quality of review rating. Similarly, I also studied what determines the number of reviews the property recieves. These are particularly helpful for Airbnb property owners because, based on the results of the prediction models, they could evaluate thier strength, weakness, and improve on delivering better services, good reveiws, ratings, and reputations for their business.  

In this project we plan to accomplish two main goals:

 1) Build a prediction (multilevel) model for predicting the quality of ratings
 2) Build a prediction (poisson distribution) model to quantify what determines the number of reveiws

### How users can get started with the project?
- Download all the files and put them in a folder
- Change the dataset directories in Rmarkdown files before running the file.
- [AirBnB Zero Inflation Poisson Model.Rmd](https://github.com/gurungkshitij/airbnb-rating-analysis/blob/master/AirBnB%20Zero%20Inflation%20Poisson%20Model.Rmd) is the code for predicting number of reviews. 
- [Final Multilevel.Rmd](https://github.com/gurungkshitij/airbnb-rating-analysis/blob/master/Final%20Multilevel.Rmd) is the code for predicting quality of ratings. 
- The final report of our work in under [FinalReport-Airbnb.pdf](https://github.com/gurungkshitij/airbnb-rating-analysis/blob/master/FinalReport-Airbnb.pdf)
<hr />
<figure>
	<a href="https://samdatourism.com/wp-content/uploads/2019/10/airbnb-recommended-destinations.png"><img src="https://samdatourism.com/wp-content/uploads/2019/10/airbnb-recommended-destinations.png"></a>
</figure>


#### Two Up

Apply the `half` class like so to display two images side by side that share the same caption.

{% highlight html %}
<figure class="half">
    <a href="assets/img/Lifetouch Portrait.png"><img src="/imassets/img/Lifetouch Portrait.png"></a>
    <a href="/images/image-filename-2-large.jpg"><img src="/images/image-filename-2.jpg"></a>
    <figcaption>Caption describing these two images.</figcaption>
</figure>
{% endhighlight %}

And you'll get something that looks like this:

<figure class="half">
	<a href="assets/img/Lifetouch Portrait.png"><img src="assets/img/Lifetouch Portrait.png"></a>
	<a href="http://placehold.it/1200x600.jpeg"><img src="http://placehold.it/600x300.jpg"></a>
	<figcaption>Two images.</figcaption>
</figure>

#### Three Up

Apply the `third` class like so to display three images side by side that share the same caption.

{% highlight html %}
<figure class="third">
	<img src="/images/image-filename-1.jpg">
	<img src="/images/image-filename-2.jpg">
	<img src="/images/image-filename-3.jpg">
	<figcaption>Caption describing these three images.</figcaption>
</figure>
{% endhighlight %}

And you'll get something that looks like this:

<figure class="third">
	<img src="http://placehold.it/600x300.jpg">
	<img src="http://placehold.it/600x300.jpg">
	<img src="http://placehold.it/600x300.jpg">
	<figcaption>Three images.</figcaption>
</figure>

### Alternative way

Another way to achieve the same result is to include `gallery` Liquid template. In this case you
don't have to write any HTML tags – just copy a small block of code, adjust the parameters (see below)
and fill the block with any number of links to images. You can mix relative and external links.

Here is the block you might want to use:

{% highlight liquid %}
{% raw %}
{% capture images %}
	http://vignette2.wikia.nocookie.net/naruto/images/9/97/Hinata.png
	http://vignette4.wikia.nocookie.net/naruto/images/7/79/Hinata_Part_II.png
	http://vignette1.wikia.nocookie.net/naruto/images/1/15/J%C5%ABho_S%C5%8Dshiken.png
{% endcapture %}
{% include gallery images=images caption="Test images" cols=3 %}
{% endraw %}
{% endhighlight %}

Parameters:

- `caption`: Sets the caption under the gallery (see `figcaption` HTML tag above);
- `cols`: Sets the number of columns of the gallery.
Available values: [1..3].

It will look something like this:

{% capture images %}
	http://vignette2.wikia.nocookie.net/naruto/images/9/97/Hinata.png
	http://vignette4.wikia.nocookie.net/naruto/images/7/79/Hinata_Part_II.png
	http://vignette1.wikia.nocookie.net/naruto/images/1/15/J%C5%ABho_S%C5%8Dshiken.png
{% endcapture %}
{% include gallery images=images caption="Test images" cols=3 %}
