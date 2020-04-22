# Welcome to the Studio Week 3!
### Date: 4/17/2020
### Author: Rowan Moody
This repo contains a small, 3 page website that contains a series of different base maps, each on it's own page, completed as an assignment for a Webmapping course at Clark University. You can preview the site by clicking the link below. The code used in this repo is a mix of html and css, and utilizes Mapbox mapping and styles.  The tutorial information used in creating this site are detailed below in the Instructions section.



Link: https://rmoody3.github.io/studio-week3/







## Assignment Instructions

1. `index.html` - Start with [this Mapbox tutorial for creating a style for a choropleth map](https://docs.mapbox.com/help/tutorials/choropleth-studio-gl-pt-1/). This tutorial will include downloading sample data, then uploading them *to your Mapbox account.* Once you've completed that, move on to [this tutorial that will show you how to add interactivity to your map](https://docs.mapbox.com/help/tutorials/choropleth-studio-gl-pt-2/). In your final map, make the following edits to the CSS in your header: Add `padding-top: 200px;` to `#map` and update `#features` from`top: 0;` to `top: 200px;`
2. `mapbox-interaction.html` - Next, we'll explore adding some functionality in Mapbox. Open the file and look for the comment code that prompts you to add certain types of interactivity and gives you a place to start looking for documentation. This is a very common challenge when creating a webmap: you want to do something, but you're not sure how! So you have to look around at documentation and other people's code to find the answer. As you go through this exercise remember how much emphasis we put on good documentation in my classes...  
3. `mapbox-turfjs.html` - Finally, we're going to introduce some analytical capability to our maps. [Follow this Mapbox tutorial for creating a map that can do some basic analysis on point data](https://docs.mapbox.com/help/tutorials/analysis-with-turf/). Note that the **Getting started** and **Add Structure** sections of the tutorial have already been completed in the `mapbox-turfjs.html` starter file. 

## For those who want to explore the basics more: 
- If you want to explore Leaflet more, you can follows this [Leaflet tutorial for adding basic geographic features (point, polygon, polyline) to a map](https://github.com/jakobzhao/geog371/tree/master/lectures/lec07). You will need to set up a new `.html` file from scratch.  
- Alternatively, the [Leaflet website hosts a variety of tutorials](https://leafletjs.com/examples.html). Most of these tutorials assume that you can set up a basic html file, including body, header, and script tags. 

## For those who need a bigger challenge: 
After successfully following the instructions above you can take things further... these tutorials are more complex but allow for some really cool interactivity. They both require you to construct complete web pages. 
- Mapbox has a good tutorial for how to [build a Store Locator](https://docs.mapbox.com/help/tutorials/building-a-store-locator/) that includes some really cool interactivity.
- Here's a great Mapbox tutorial for how to [show changes over time](https://docs.mapbox.com/help/tutorials/show-changes-over-time/): this tutorial includes a 4MB GeoJSON file that contains 15,273 geocoded motor vehicle collision incidents in NYC. Github pages limits are 1GB, you should be able to host these data and the code in a repo! 
- I really love this Leaflet tutorial for a [Boston Rat Map](http://maptimeboston.github.io/leaflet-intro/) ([repo here](https://github.com/maptimeBoston/leaflet-intro)). It's quite easy to follow and covers basic geographic features, styling, and interactivity. However, it uses an outdated version of Leaflets css/jss. You would need to update these in the header and then figure out if there are other things that don't quite work. 
