# Tips

<details>
  <summary>Recommended readings</summary>
  
  <summary> Google Earth Engine and Artificial Intelligence (AI): A Comprehensive Review</summary>
📄 In this article, the authors provided a systematic review of relevant literature to identify recent research that incorporates AI methods in GEE.
Then, they discuss some of the major challenges of integrating GEE and AI and identify several priorities for future research.

🟢 Here are some important points and info from the paper that I would like to highlight:

➡️ About 25 PB of data are being generated per day at Google, a significant portion of which is spatio-temporal data.

➡️ The primary applications that have applied GEE integrated with AI are crop, LULC, vegetation, wetland, water, and forest.

➡️ Land cover classification is the 2nd-most-developed domain area using GEE and AI, followed by forest and deforestation monitoring.

➡️ The primary study areas are China, Brazil and USA.

➡️ The most-used remote sensing data types are Landsat 8 OLI, Landsat 5 TM, Landsat 7 ETM+.

➡️ Random Forest, Support Vector Machine and Classification and Regression Tree are the most popular Machine Learning models.

➡️ The top evaluation metrics used are: overall accuracy, producer's accuracy, user's accuracy and Kappa.

➡️ SAR imagery is often used in water mapping of flood monitoring analyses because of its ability to see through clouds and work over spatial scales.

⚠️ GEE compute limits:

➡️  Authors often ran into memory errors when analyzing too many field samples/observations.

➡️  This also happened when the size of the author's input data was too large more generally and it was difficult to know beforehand if intermediate processing steps would trigger this error.

➡️  Many authors had to export data as part of their analysis to access functionality not on GEE or because using GEE would make them run out of the amount of free compute provided. For example, every image uploaded to GEE is limited to 10 GB. As the authors used subcentimeter drone imagery, they had to downsize each image before uploading it, resulting in a loss of resolution.

📰 [*Check out this paper*](https://www.mdpi.com/2072-4292/14/14/3253)

<div align="center">
<img src="https://github.com/rafaelatiengo/Tips/blob/main/Images/GEE_AI.png" width="700" height="700" />
</div>


<summary>Fifty years of Landsat science and impacts</summary>

  Uncover the incredible story of Landsat's 50-year journey! Discover how this pioneering remote sensing technology has transformed our understanding of Earth and its dynamic changes.

📰 [*Check out this paper*](https://www.sciencedirect.com/science/article/pii/S0034425722003054)

<div align="center">
<img src="https://github.com/rafaelatiengo/Tips/blob/main/Images/Landsat_50y.png" width="700" height="700" />
</div>

<summary> Google Earth Engine: A Global Analysis and Future Trends</summary>
Are you interested in understanding the primary applications of the Google Earth Engine? 
Would you like to know which articles are most frequently cited? 
Which nations are at the forefront of utilizing this platform?

📰 [*Check out this paper*](https://www.mdpi.com/2072-4292/15/14/3675)

<div align="center">
<img src="https://github.com/rafaelatiengo/Tips/blob/main/Images/GEE_Global_Analysis.png" width="700" height="700"/>
</div>
</details>


<details>
<summary>Materials & courses</summary>

  <summary> 5 materials to get started with Vegetation Indices </summary>
🌱 5 materials that will help you to study & understand Vegetation Indices through Remote Sensing🛰️

1️⃣ [*EVI from First Principles*](https://www.linkedin.com/feed/update/urn:li:activity:7082367195699154944?updateEntityUrn=urn%3Ali%3Afs_updateV2%3A%28urn%3Ali%3Aactivity%3A7082367195699154944%2CFEED_DETAIL%2CEMPTY%2CDEFAULT%2Cfalse%29)

2️⃣ [*In the Field: NDVI, SAVI, EVI Compared*](https://www.linkedin.com/feed/update/urn:li:activity:7085288082001825792?updateEntityUrn=urn%3Ali%3Afs_updateV2%3A%28urn%3Ali%3Aactivity%3A7085288082001825792%2CFEED_DETAIL%2CEMPTY%2CDEFAULT%2Cfalse%29)

3️⃣ [*NDVI from First Principles*](https://www.linkedin.com/feed/update/urn:li:activity:7074073312250777600?updateEntityUrn=urn%3Ali%3Afs_updateV2%3A%28urn%3Ali%3Aactivity%3A7074073312250777600%2CFEED_DETAIL%2CEMPTY%2CDEFAULT%2Cfalse%29)

4️⃣ [*Creating and Using Normalized Difference Vegetation Index (NDVI) from Satellite Imagery*](https://appliedsciences.nasa.gov/join-mission/training/english/arset-creating-and-using-normalized-difference-vegetation-index-ndvi)

5️⃣ [*Monitoring Aquatic Vegetation with Remote Sensing*](https://appliedsciences.nasa.gov/join-mission/training/english/arset-monitoring-aquatic-vegetation-remote-sensing)

<summary> 5 NASA ARSET materials to get started with land cover mapping </summary>
🗺️ 5 NASA ARSET materials for land cover mapping:

1️⃣ [*Using Google Earth Engine for Land Monitoring Applications*](http://appliedsciences.nasa.gov/join-mission/training/english/arset-using-google-earth-engine-land-monitoring-applications)

2️⃣ [*SAR for Landcover Applications*](http://appliedsciences.nasa.gov/join-mission/training/english/arset-sar-landcover-applications)

3️⃣ [*Land Cover Classification with Satellite Imagery*](https://appliedsciences.nasa.gov/join-mission/training/english/arset-land-cover-classification-satellite-imagery)

4️⃣ [*Accuracy Assessment of a Land Cover Classification*](https://appliedsciences.nasa.gov/join-mission/training/english/arset-accuracy-assessment-land-cover-classification)

5️⃣ [*Change Detection for Land Cover Mapping*](https://appliedsciences.nasa.gov/join-mission/training/english/arset-change-detection-land-cover-mapping)

<summary> 5 crucial NASA ARSET available resources to fuel your journey in fire mapping </summary>
🔥 5 crucial NASA ARSET available resources to fuel your journey in fire mapping:

1️⃣ [*Satellite Observations and Tools for Fire Risk, Detection, and Analysis*](https://appliedsciences.nasa.gov/get-involved/training/english/arset-satellite-observations-and-tools-fire-risk-detection-and)

2️⃣ [*Introduction to Remote Sensing for Wildfire Applications*](https://appliedsciences.nasa.gov/get-involved/training/english/arset-introduction-remote-sensing-wildfire-applications)

3️⃣ [*NASA Earth Science Data for Wildland Fire Decision Making*](https://appliedsciences.nasa.gov/get-involved/training/english/arset-nasa-earth-science-data-wildland-fire-decision-making)

4️⃣ [*Using Earth Observations for Pre- and Post-Fire Monitoring*](https://appliedsciences.nasa.gov/get-involved/training/english/arset-using-earth-observations-pre-and-post-fire-monitoring)

5️⃣ [*Techniques for Wildfire Detection and Monitoring*](https://appliedsciences.nasa.gov/get-involved/training/english/arset-techniques-wildfire-detection-and-monitoring)

<summary> Take the first step on your radar data learning journey today!  </summary>
Check out 5 top-notch resources available for FREE!

1️⃣ [*Introduction to Synthetic Aperture Radar*](https://www.esri.com/arcgis-blog/products/arcgis-pro/imagery/introduction-to-synthetic-aperture-radar/)

2️⃣ [*Guide: fundamentals of Synthetic Aperture Radar (SAR) *](https://storymaps.arcgis.com/stories/20d8cd2ce11a4d5d81a8a65711d5ec29)

3️⃣ [*Explore SAR satellite imagery*](https://learn.arcgis.com/en/projects/explore-sar-satellite-imagery/)

4️⃣ [* SAR satellite data*](https://storymaps.arcgis.com/stories/3fbad9bf7d9f480c9f41e7f1c7e6ce15)

5️⃣ [*SAR for landcover applications*](https://appliedsciences.nasa.gov/get-involved/training/english/arset-sar-landcover-applications)

</details>
