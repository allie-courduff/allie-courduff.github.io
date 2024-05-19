---
title: "GES 687: Final Project"
excerpt: "The final product of GES687 melding various advanced GIS techniques <br/><img src='/images/FinalProj_Crop.png'>"
collection: portfolio
---

The primary goal of the advanced GIS course for both undergrads and graduate students at UMBC is for students to improve/hone their skills in R code manipulation as in map-making programs, such as QGIS and Geoda. Over the course of the semester, students refine these skills with the end-goal of ease in making professional looking maps and code.

While Lab 05 - given an earlier page in this portfolio - occured in the middle of the semester, in the middle of building our skills, this final project acted as a comprehensive check of how well we had understood all of material covered. Were we able to utilize the different methods of coding and mapping systems to produce communicative, professional-looking maps. This final project is my entry to answer yes to this question.

My final project looked at Toxic Inventory Release data from the EPA and county-measured median household income counts, both for Maryland in 2022. Before even performing any form of spatial analysis on the two variables, looking at the distribution of the TRI points when inputted into QGIS, if the national highway system (maryland.gov) is overlaid, you can see an overlap.

![Toxic Releases and National Highway System](/images/TRI and Highways.png)

This shows that TRI releases are aggregated typically around highways, likely due to industry and other releasing sites being placed close to major transportation routes for commuting employees. But what of a relationship between the TRI data and median household income. My expectation was that there would be a higher TRI count in counties with lower household income, as polluting industries are often times moved to communities with the least economic and political power to speak against its placement.

![TRI Moran's I](/images/tri_morans.png)

![MHHI Moran's I](/images/mhhi_morans.png)

Performing a univariate Moran's I test in geoda for both variables provided the significant clustering of the data as well as a resulting values for the Moran's I for each. From these tests, there is not an exact direct relationship between the two. We see this more clearly in the bivariate map created in QGIS. There are several counties with signifcance for both variables, which gives backing to evalauting and analyzing this relationship further.

![TRI and MHHI Bivariate Final Layout](/images/FinalLayout.png)

There are only 3 counties that met my expectation, with High MHHI/Low TRI or Low MHHI/High TRI, and six that showcase the oppposite - Low MHHI/Low TRI. So, there is a spatial relationship between the two with statistical significance, but only slightly leaning towards the low-low distribution along the Eastern shore and Western Maryland (while Baltimore City in particular is an outlier with Low MHHI and High TRI. This could be from industries not being placed in areas of lower income, a supplemental analysis could be used to look at TRI count/1 individual. 
