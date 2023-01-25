---
layout: post
title:  Where Should You Live?
categories: [D3, Project]
excerpt: We created a visualization to allow the user to compare different states and cities based on a number of criteria. 
---

For a school project, we were asked to create a visualization from a large dataset of our choosing. Given the 5 members of my group are all graduate students looking to enter the workforce in the next few months, we decided to select a project that would be pertinent to all of us.

We chose to make an interactive set of visualizations that allowed the user to compare states over a number of variables. Furthermore, it allowed the user to select one or more cities and compare their values of the selected variable. We also deployed a KNN model which lets the user compare a selected city with the k nearest cities based on how similar their variable values are. 

To create this tool, we first had to clean the data. A number of different tables were joined in pandas, and the number of usable cities was whittled down until we had 950. The visualizations were created using the D3.js libraries. 

To check out the wesbite we made, navigate on over [here](https://josephgeibig.github.io/CityFinder/). Our group member Joseph was kind enough to host the website on his GitHub pages. 