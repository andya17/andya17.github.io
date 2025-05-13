---
permalink: /webgis/
title: "WebGIS Portfolio"
toc: true
toc_icon: "cog"
toc_sticky: true
---

The following is a digital portfolio assignment created for the course GEOG 693: WebGIS, in which I was enrolled during the Spring 2025 semester. Students were tasked with choosing three strong assignments and improving them.

## Product 1: Invasive Species and Areas of Critical Environmental Concern
### [Link to Product](https://experience.arcgis.com/experience/fdbb13b1c65d4b088b4496130dabb7ba)

<b>Platform:</b> ArcGIS Online  
<b>Modification of:</b> Production Assignment 2: Data Configuration   
<b>Original feedback:</b> *While the TA graded my assignment, I did not receive written feedback on what to improve.* In the absence of feedback, I thought back on the course and considered what changes I could make to increase interactivity.

<b>Description:</b> This product is a web app created in ArcGIS Experience Builder. It aims to present a point layer of an invasive plant species – yellow horned poppy – alongside one of the MassGIS conservation-related layers – Areas of Critical Environmental Concern. The product is based on the idea that the managers of these vital areas would want to see whether any invasive plant observation points are particularly close or even inside their borders, for part of the danger of invasive plants is whether they might spread to new areas in the future.

<b>Improvements made:</b>  
* The Production Assignment on which this product is based was constructed using ArcGIS Instant Apps, which is the more limited Esri web app tool students interacted with in the early weeks of class.
* Users are now able to view the pop-up for a feature in a side panel which matches the height of the screen. This helps in that users are more easily able to see the picture for each yellow horned poppy observation without having to scroll down.
* Users can flip through all features in both feature layers (polygon areas and observation points) and apply actions to each feature, such as zooming to them.
* Users can switch the basemap to Imagery to see what the coastline looks like at the spot where an invasive species was observed.
* Users can choose to view bookmarks which correspond to the inset maps on the previous version, which were perhaps in the way sometimes.


## Product 2: Pioneer Valley Invasive Species Survey
### [Link to Product](https://survey123.arcgis.com/share/98c527fcc73f4774918355814c75790b)

<b>Platform:</b> ArcGIS Survey123   
<b>Modification of:</b> Production Assignment 8: Making a Survey    
<b>Original feedback:</b> *While the TA graded my assignment, I did not receive written feedback on what to improve.* In the absence of feedback, I thought back on the course and considered what changes I could make to increase interactivity.

<b>Description:</b> This product is a web survey created in ArcGIS Survey 123. Its aim is to provide a way for community members to send geographic information concerning invasive species sightings directly to non-profit organizations or governmental bodies invested in invasive species monitoring. While I was not sure if a survey fit the expectations of the assignment, instructor Dr. Hongyu Zhang provided that students should make sure any included survey asks a spatial question and encourages users to contribute. I feel that the product meets these requirements. 

<b>Improvements made:</b>  
* Added important contextual information and links to the description of the survey.
* Introduced and added links to iNaturalist for the invasive plant chosen in a question to foster knowledge of community science and encourage contribution to a global database.
* Added visibility rule for geospatial questions to reflect the concept of geoprivacy. Users may be concerned about their device asking for their location, so a list of popular water features is included if users opt not to show their location.

<style>.embed-container {position: relative; height: 0; padding-bottom:80%; max-width: 100%;} .embed-container iframe, .embed-container object, .embed-container iframe{position: absolute; top: 0; left: 0; width: 100%; height: 100%;} small{position: absolute; z-index: 40; bottom: 0; margin-bottom: -15px;}</style><div class="embed-container"><iframe name="survey123webform" width="500" height="400" frameborder="0" marginheight="0" marginwidth="0" title="Amherst Area Aquatic Invasive Plant Monitoring" src="//survey123.arcgis.com/share/98c527fcc73f4774918355814c75790b" allow="geolocation https://survey123.arcgis.com; camera https://survey123.arcgis.com"></iframe></div><script>var survey123webform = document.getElementsByName('survey123webform')[0];window.addEventListener("message",e=>{if(e.data){var t=JSON.parse(e.data);["survey123:webform:formLoaded","survey123:onFormLoaded"].includes(t.event)&&t.contentHeight&&(survey123webform.parentNode.style.height=t.contentHeight+"px")&&(survey123webform.parentNode.style["padding-bottom"]="unset")}});</script>

## Product 3: UMass Amherst Science Building Tour
### [Link to Product](https://jsfiddle.net/aatallah/sk6q9rcx/88/)

<b>Platform:</b> Google Maps JavaScript API, JSFiddle  
<b>Modification of:</b> Production Assignment 6: Making A Google Map  
<b>Original feedback:</b> *While the TA graded my assignment, I did not receive written feedback on what to improve.* In the absence of feedback, I thought back on the course and considered what changes I could make to increase interactivity.

<b>Description:</b> This product is a Google Map created using the Google Maps JavaScript API and the associated documentation for this service. The goal of the map is to present a series of features 

<b>Improvements made:</b>  
* Added pop-ups using JavaScript to show names of science buildings.
* Added numerical glyph to feature pins to show an order by which a user may take a tour from one side of campus (Holdsworth) to the other (Morrill).