<center><img src='./imgs/logo.png' width=300></center></img>

# Introduction
This is an attempt to aggregate as many covid-19 analytical resources online. Ranging from data sources, dashboards, maps, charts, algorithms, and published papers to social media channels and blog posts. If you find a resource not here, please consider contributing by reaching out to  [Catherine](mailto:cordun1@umbc.edu) or [Michael](mailto:mjfagundo@gmail.com), or submitting a pull request.


# Table of Contents
[Datasets](#datasets)

[Visualizations](#visualizations)

[Epi Models](#epi)

[Journals](#journals)

[Social Media](#sm)

[Deep Learning Models](#dl)

<img src="https://img.shields.io/badge/-NEW-yellow"></img> badges refer to new as of this week. The most recent updates are at the bottom of the enumerated list.


# Datasets <a name="datasets"/>

1. **Novel Coronavirus (COVID-19) Cases, provided by Johns Hopkins University CSSE**  https://github.com/CSSEGISandData/COVID-19 <img src="https://img.shields.io/badge/data-primary-green"></img>

2. **Midas Data and Research Portal** - https://github.com/midas-network/COVID-19 <img src="https://img.shields.io/badge/data-primary-green"/></img>
- Disease Catalog - https://midasnetwork.us/covid-19/, Public-access data collections with documented metadata. (Click on a collection name to see the collection in GitHub.)
- Parameter Estimates - Peer-reviewed Published estimates of epidemiological characteristics that have been peer-reviewed, encoded by community members and approved by authors. For complete information on each estimate, view this file on GitHub https://github.com/midas-network/COVID-19/blob/master/parameter_estimates/2019_novel_coronavirus/estimates.csv
- Parameter Estimates - Not peer-reviewed Published estimates of epidemiological characteristics that have not been peer-reviewed, encoded by community members and approved by authors. For complete information on each estimate,https://github.com/midas-network/COVID-19/blob/master/parameter_estimates/2019_novel_coronavirus/estimates.csv
- Software Catalog - Listing of software created by community members, with documented metadata. (Click on a software name to open the software webpage.)
- **Multiple** Midas-curated aggregate and individual-level datasets, global - https://github.com/midas-network/COVID-19/wiki/Data-catalog#cases

3. **Chinese nCov Memory -  Memory of 2020 nCoV: Media Coverage, Non-fiction Writings, and Individual Narratives (Continuously updating)** https://github.com/2019ncovmemory/nCovMemory, About - https://qz.com/1811018/chinese-citizens-use-github-to-save-coronavirus-memories/ here: https://2019ncovmemory.github.io/nCovMemory/ <img src="https://img.shields.io/badge/data-noneng-lightgray"/></img>

4. **Raw data in Wuhan, Hubei, and Guangzhou for serious COVID-19 cases, and Wuhan hospitalization data** - https://github.com/c2-d2/COVID-19-wuhan-guangzhou-data for *Ruoran, Li, Caitlin Rivers, Qi Tan, Megan B Murray, Eric Toner, and Marc Lipsitch. The Demand for Inpatient and ICU Beds for COVID-19 in the US: Lessons From Chinese Cities (March 2020).* https://dash.harvard.edu/handle/1/42599304; data at https://github.com/c2-d2/COVID-19-wuhan-guangzhou-data <img src="https://img.shields.io/badge/data-published-9cf"></img> <img src="https://img.shields.io/badge/-paper-brightgreen"></img> <img src="https://img.shields.io/badge/sm-thread-blue"></img> <img src="https://img.shields.io/badge/-withcode-red"></img>

5. **Google Sheets From DXY.cn Google Sheets** - https://docs.google.com/spreadsheets/d/1jS24DjSPVWa4iuxuD4OAXrE3QeI8c9BC1hSlqr-NMiU/edit#gid=1187587451 <img src="https://img.shields.io/badge/data-global-yellowgreen"></img>

6. **Kaggle Dataset** - https://www.kaggle.com/sudalairajkumar/novel-corona-virus-2019-dataset, Johns Hopkins University has made an excellent dashboard using the affected cases data. Data is extracted from the google sheets associated and made available here.<img src="https://img.shields.io/badge/data-challenge-ff69b4"></img>

7. **Nextstrain** - https://github.com/nextstrain/ncov - The hCoV-19 / SARS-CoV-2 genomes were generously shared via GISAID. We gratefully acknowledge the Authors, Originating and Submitting laboratories of the genetic sequence and metadata made available through GISAID on which this research is based. For a full list of attributions please see the metadata file.<img src="https://img.shields.io/badge/data-genome-red"></img>

8. **ECDC Download today’s data on the geographic distribution of COVID-19 cases worldwide** - https://www.ecdc.europa.eu/en/publications-data/download-todays-data-geographic-distribution-covid-19-cases-worldwide <img src="https://img.shields.io/badge/data-global-yellowgreen"></img>

9. **BNO** - https://bnonews.com/index.php/2020/02/the-latest-coronavirus-cases/ <img src="https://img.shields.io/badge/data-global-yellowgreen"></img> <img src="https://img.shields.io/badge/-timeline-yellow"></img>

10. **U.S. Centers for Disease Control and Prevention (CDC)** - https://www.cdc.gov/media/dpk/diseases-and-conditions/coronavirus/coronavirus-2020.html <img src="https://img.shields.io/badge/data-primary-green"></img>

11. **Covid19 News Tracker b Scops** - https://covid19.scops.ai/superset/dashboard/home/  <img src="https://img.shields.io/badge/viz-dash-blue"></img>

12. *Chen, Emily, Kristina Lerman, and Emilio Ferrara. "COVID-19: The First Public Coronavirus Twitter Dataset." arXiv preprint arXiv:2003.07372 (2020).*  https://arxiv.org/pdf/2003.07372.pdf  Github https://github.com/echen102/COVID-19-TweetIDs <img src="https://img.shields.io/badge/-paper-brightgreen"></img> <img src="https://img.shields.io/badge/-withcode-red"></img>

13. **2019 new coronavirus epidemic time series data warehouse (Chinese and English)** - https://github.com/BlankerL/DXY-COVID-19-Data <img src="https://img.shields.io/badge/data-noneng-lightgray"/></img> <img src="https://img.shields.io/badge/-NEW-yellow"></img>

14. **The Covid Tracking Project** - https://covidtracking.com/, with real-time API: https://covidtracking.com/api/ <img src="https://img.shields.io/badge/-NEW-yellow"></img>

15. **COVID Tracking Data (CSV)** https://github.com/COVID19Tracking/covid-tracking-data - Developed by Julia Kodysh. GitHub backup for versioning the contents of our public Google spreadsheet data in CSV format. <img src="https://img.shields.io/badge/-NEW-yellow"></img>

16. **COVID Post man APIs** - https://covid-19-apis.postman.com/?mkt_tok=eyJpIjoiTTJJM1ptVm1NemRtTkRnMiIsInQiOiJpMzc4aFwvRWJvK3RnTnBNNUdRTmRXVEhtRXFUeW4rcmhsNUlVV09TWnVjRnhxOVl0N2NvMUxyQ3BNd2J5YnFTVnQ4aW5xbnlZMVpDVzVQWUtaMjZcL0FNc1ZcL2wrSXpUd1Q0U0F5UTJLdGNpV0c3cVwvRXhrTXBnRWtzejhQMklPZmIifQ%3D%3D - During the present novel coronavirus (COVID-19) pandemic, those on the front lines—including health care professionals, researchers, and government experts—need quick, easy access to real-time critical data. This type of information exchange is what APIs do best, and as an API-first company, Postman is committed to providing whatever assistance we can in this area. <img src="https://img.shields.io/badge/-NEW-yellow"></img>

17. **Smartphone data reveal which Americans are social distancing (and not)** - https://www.washingtonpost.com/technology/2020/03/24/social-distancing-maps-cellphone-location/, data available by UnaCast; data free for non-for-profit groups - https://www.unacast.com/covid19 <img src="https://img.shields.io/badge/-NEW-yellow"></img>

18. **Covid Medical Radiology Datasets** https://github.com/ieee8023/covid-chestxray-dataset; https://github.com/lindawangg/COVID-Net by @lindawangg, and https://github.com/ieee8023/covid-chestxray-dataset by @ieee8023 <img src="https://img.shields.io/badge/dl-cv-green"></img> <img src="https://img.shields.io/badge/-NEW-yellow"></img>

19. **New York Times Coronavirus (Covid-19) Data in the United States** - https://github.com/nytimes/covid-19-data - The New York Times is releasing a series of data files with cumulative counts of coronavirus cases in the United States, at the state and county level, over time. We are compiling this time series data from state and local governments and health departments in an attempt to provide a complete record of the ongoing outbreak. We have used this data to power our maps and reporting tracking the outbreak, and it is now being made available to the public in response to requests from researchers, scientists and government officials who would like access to the data to better understand the outbreak. The data begins with the first reported coronavirus case in Washington State on Jan. 21, 2020. We will publish regular updates to the data in this repository.<img src="https://img.shields.io/badge/-NEW-yellow"></img>

# Visualizations <a name="visualizations"/>
Maps, Descriptive Charts, Dashboards<pr>

1. **Mapping 2019-nCoV** - https://www.thelancet.com/journals/laninf/article/PIIS1473-3099(20)30120-1/fulltext (Dong E, Du H, Gardner L. An interactive web-based dashboard to track COVID-19 in real time. Lancet Infect Dis; published online Feb 19. https://doi.org/10.1016/S1473-3099(20)30120-1), <img src="https://img.shields.io/badge/viz-map-brightgreen"></img>

2.  **U.S. Centers for Disease Control and Prevention** - https://www.cdc.gov/coronavirus/2019-ncov/cases-updates/world-map.html <img src="https://img.shields.io/badge/viz-map-brightgreen"></img>
- Cases in U.S. https://www.cdc.gov/coronavirus/2019-ncov/cases-updates/cases-in-us.html <img src="https://img.shields.io/badge/viz-map-brightgreen"></img>
- Testing in U.S. https://www.cdc.gov/coronavirus/2019-ncov/cases-updates/testing-in-us.html <img src="https://img.shields.io/badge/viz-map-brightgreen"></img>

3.  **Covid-19 Dashboards** - https://covid19dashboards.com/, Github https://github.com/github/covid19-dashboard <img src="https://img.shields.io/badge/-withcode-red"></img>
- Part 1 Statistics by Country: https://covid19dashboards.com/covid-overview/#Part-One:-Statistics-By-Country <img src="https://img.shields.io/badge/-charts-yellow"></img>
- Part 2 Part Two: United States, by State - https://covid19dashboards.com/covid-overview/#Part-Two:-United-States,-by-State <img src="https://img.shields.io/badge/-charts-yellow"></img>
- COVID-19 Deaths Per Capita - https://covid19dashboards.com/covid-compare-permillion/ <img src="https://img.shields.io/badge/-charts-yellow"></img>
- How many cases of COVID-19 does each U.S. state really have? - https://covid19dashboards.com/covid-19-us-case-estimation/ <img src="https://img.shields.io/badge/-charts-yellow"></img>
- Compare Country Trajectories - Total Cases - https://covid19dashboards.com/compare-country-trajectories/ <img src="https://img.shields.io/badge/-charts-yellow"></img>
- Compare Country Trajectories - Death Rate - https://covid19dashboards.com/compare-country-death-trajectories/ <img src="https://img.shields.io/badge/-charts-yellow"></img>
- Interactive Map - Confirmed Cases in the US by State - https://covid19dashboards.com/growth-map-us-states/ <img src="https://img.shields.io/badge/viz-map-brightgreen"></img>
- Changes In The Daily Growth Rate - https://covid19dashboards.com/growth-analysis/  <img src="https://img.shields.io/badge/-charts-yellow"></img>
- COVID-19 Exploratory Data Analysis - https://covid19dashboards.com/corona-eda/  <img src="https://img.shields.io/badge/-charts-yellow"></img>
- COVID-19 Growth By State (US) - https://covid19dashboards.com/growth-us-states/  <img src="https://img.shields.io/badge/-charts-yellow"></img>

4. **HealthMap alert notifications** - https://healthmap.org/wuhan/ <img src="https://img.shields.io/badge/viz-map-brightgreen"></img>

5. **HealthMap/John Brownstein Covid-19 Map** - https://www.healthmap.org/covid-19/ <img src="https://img.shields.io/badge/viz-map-brightgreen"></img>

6. **Covid-19 spread, Chinese Disease Control** - http://2019ncov.chinacdc.cn/2019-nCoV/ <img src="https://img.shields.io/badge/viz-map-brightgreen"></img> <img src="https://img.shields.io/badge/-noneng-lightgrey"></img>

7. **New York Times/Lai R KK, et al., Coronavirus Map: Tracking the Global Outbreak** - https://www.nytimes.com/interactive/2020/world/coronavirus-maps.html <img src="https://img.shields.io/badge/viz-map-brightgreen"></img>

8. **European Centre for Disease Prevention and Control**, https://darwinanddavis.github.io/worldmaps/coronavirus.html (Github: https://github.com/darwinanddavis/worldmaps) <img src="https://img.shields.io/badge/viz-map-brightgreen"></img> <img src="https://img.shields.io/badge/-withcode-red"></img>

9. **University of Virginia - COVID-19 Surveillance Dashboard**, http://ncov.bii.virginia.edu/dashboard/ <img src="https://img.shields.io/badge/viz-dash-blue"></img>

10. **University of Virginia  - COVID-19 Cases and Clusters Outside of China**, https://datastudio.google.com/u/0/reporting/f6ad0988-f203-45f8-8d18-5d726c1d2d8b/page/MGzDB <img src="https://img.shields.io/badge/viz-dash-blue"></img>

11. **University of Washington HGIS Lab** - https://hgis.uw.edu/virus/ (Github: https://github.com/jakobzhao/virus)<img src="https://img.shields.io/badge/viz-dash-blue"></img> <img src="https://img.shields.io/badge/-withcode-red"></img>

12. **nCov2019 for studying COVID-19 coronavirus outbreak**, Tianzhi Wu, Erqiang Hu, Patrick Tung, Xijin Ge, Guangchuang Yu - nCov2019: An R package with real-time data, historical data and Shiny app (https://guangchuangyu.github.io/nCov2019/) <img src="https://img.shields.io/badge/library-R-blue"></img> <img src="https://img.shields.io/badge/-withcode-red"></img>

13. **Dipartimento della Protezione Civile COVID-19 Italia - Monitoraggio della situazione** - http://opendatadpc.maps.arcgis.com/apps/opsdashboard/index.html#/b0c68bce2cce478eaac82fe38d4138b1 <img src="https://img.shields.io/badge/viz-map-brightgreen"></img>

14. **Esri Story Map Mapping the novel coronavirus outbreak** - https://storymaps.arcgis.com/stories/4fdc0d03d3a34aa485de1fb0d2650ee0 <img src="https://img.shields.io/badge/viz-map-brightgreen"></img>

15. **World Health Organization. Novel coronavirus (COVID-19) situation (public dashboard)** - https://who.maps.arcgis.com/apps/opsdashboard/index.html#/c88e37cfc43b4ed3baf977d77e4a0667 <img src="https://img.shields.io/badge/viz-dash-blue"></img>

16. **Crowdsourced Google Map by covid-2019 Reddit Map Community** - https://www.google.com/maps/d/u/0/viewer?mid=1yCPR-ukAgE55sROnmBUFmtLN6riVLTu3&ll=30.359193252484147%2C0&z=2
<img src="https://img.shields.io/badge/viz-map-brightgreen"></img> <img src="https://img.shields.io/badge/sm-reddit-red"></img>

17. **COVID19 Infodemics Observatory** - https://covid19obs.fbk.eu/, CoMuNe Labs <img src="https://img.shields.io/badge/viz-dash-blue"></img>

18. **Bing COVID Tracker** - https://www.bing.com/covid <img src="https://img.shields.io/badge/viz-dash-blue"></img>

19. **E-Tracking map of the #CoViD19 in Africa** - http://umap.openstreetmap.fr/fr/map/e-tracking-map-of-the-covid19-in-africa_411333#3/10.13/45.34 <img src="https://img.shields.io/badge/viz-map-brightgreen"></img>

20. **Vox - 11 coronavirus pandemic charts** - https://www.vox.com/future-perfect/2020/3/12/21172040/coronavirus-covid-19-virus-charts <img src="https://img.shields.io/badge/-charts-yellow"></img>

21. **Early Alert** - https://early-alert.maps.arcgis.com/apps/opsdashboard/index.html#/20bfbf89c8e74c0494c90b1ae0fa7b78 <img src="https://img.shields.io/badge/viz-dash-blue"></img>

22. **EpiRisk** -  <a href="http://epirisk.net/#eyJxdWVyeSI6eyJ0cmF2ZWxMZXZlbCI6MSwicGVyaW9kIjoxMCwidG90YWxDYXNlcyI6MzEyMDAsImRpc3RyaWJ1dGlvbk1vZGUiOiJ1bmlmb3JtIiwibW9udGgiOiJKYW4iLCJnZW9MZXZlbCI6ImJhc2luIiwic291cmNlcyI6W3siaWQiOjQ3NywiY2FzZXMiOjF9XX0sIm1hcCI6eyJjZW50ZXIiOlsxNDguMzUxMDAyNzk3Mzk1NzIsMzEuOTYyMDM3NzEzMjQ4MzM2XSwiem9vbSI6MiwicGl0Y2giOjAsImJlYXJpbmciOjB9fQ==">link here</a> <img src="https://img.shields.io/badge/viz-dash-blue"></img>

23. **WorldoMeters**- https://www.worldometers.info/coronavirus/ <img src="https://img.shields.io/badge/-charts-yellow"></img> <img src="https://img.shields.io/badge/-timeline-yellow"></img>

24. **Covid2019app Live Site** - https://covid2019app.live/ <img src="https://img.shields.io/badge/-charts-yellow"></img> <img src="https://img.shields.io/badge/data-global-yellowgreen"></img>

25. **Here’s how coronavirus spreads on a plane—and the safest place to sit** - https://www.nationalgeographic.com/science/2020/01/how-coronavirus-spreads-on-a-plane/ <img src="https://img.shields.io/badge/-charts-yellow"></img>

26. **How Much Worse the Coronavirus Could Get, in Charts**-  https://www.nytimes.com/interactive/2020/03/13/opinion/coronavirus-trump-response.html, By Nicholas Kristof and Stuart A. Thompson <img src="https://img.shields.io/badge/-charts-yellow"></img> <img src="https://img.shields.io/badge/viz-simul-yellow"></img>

27. **COVID-19 Mobility Monitoring project,  ISI Foundation and Cuebiq** - https://covid19mm.github.io/in-progress/2020/03/13/first-report-assessment.html  <img src="https://img.shields.io/badge/data-global-yellowgreen"></img> <img src="https://img.shields.io/badge/viz-map-brightgreen"></img> <img src="https://img.shields.io/badge/-charts-yellow"></img>

28. **How the Virus Got Out** - <a href="https://www.nytimes.com/interactive/2020/03/22/world/coronavirus-spread.html?action=click&amp;auth=login-google1tap&amp;login=google1tap&amp;module=Spotlight&amp;pgtype=Homepage">link here</a> <img src="https://img.shields.io/badge/viz-simul-yellow"></img> <img src="https://img.shields.io/badge/-NEW-yellow"></img>

29. **COVID-19 Scenarios** - https://neherlab.org/covid19/?fbclid=IwAR3yjOLs7zCdT7mI_OpBiB1-1Kgaz1-V8MqpBQZE6dMFiXC46d-8UWUOEQc <img src="https://img.shields.io/badge/-NEW-yellow"></img>

30. **Kinsa temperature data** https://www.nytimes.com/2019/02/14/health/kinsa-flu-tracking.html - Kinsa's fever map https://techcrunch.com/2020/03/23/kinsas-fever-map-could-show-just-how-crucial-it-is-to-stay-home-to-stop-covid-19-spread/ <img src="https://img.shields.io/badge/viz-map-brightgreen"></img> <img src="https://img.shields.io/badge/-NEW-yellow"></img>

31. **An interactive visualization of the exponential spread of COVID-19** A project to explore the global growth of COVID-19. Updated daily. Inspired by the work of John Burn-Murdoch. - http://91-divoc.com/pages/covid-visualization/ <img src="https://img.shields.io/badge/-NEW-yellow"></img>

32. **1point3acres** - https://coronavirus.1point3acres.com/en - <img src="https://img.shields.io/badge/viz-dash-blue"></img> <img src="https://img.shields.io/badge/-NEW-yellow"></img>

33. **Example of State county-by-county TN model** - https://jefferson-county-tn-coronavirus-response-jcgiscb.hub.arcgis.com/app/79afca92fb024131af8322da5fd6ee80 <img src="https://img.shields.io/badge/-NEW-yellow"></img>

34. **Skyris Odin-Covid19** - https://odin-covid19.com/ Welcome to our ODIN Lite access portal providing data from around the globe related to the currently emerging COVID-19 infectious disease. This data is fully identified and processed using Artificial Intelligence and Natural Language Processing to provide a better understanding of the effects and scope of the disease. This portal provides a very basic, scaled down version of our standard ODIN portal to facilitate free and open access to as many users as might need this data. <img src="https://img.shields.io/badge/-NEW-yellow"></img> <img src="https://img.shields.io/badge/viz-map-brightgreen"></img>


# Epi Models <a name="epi"/>

1. **COVID-19 Growth Rate Prediction**- https://covid19dashboards.com/growth-bayes/ - We assume a negative binomial likelihood as we are dealing with count data. A Poisson could also be used but the negative binomial allows us to also model the variance separately to give more flexibility. | Thomas Wiecki, @HamelHusain <img src="https://img.shields.io/badge/-withcode-red"></img> <img src="https://img.shields.io/badge/code-colab-yellow"></img> <img src="https://img.shields.io/badge/library-py-9cf"></img>

2. **Estimating The Mortality Rate For COVID-19**- https://covid19dashboards.com/covid-19-mortality-estimation/#Interpretation-of-Country-Level-Parameters  - Using Country-Level Covariates To Correct For Testing & Reporting Biases And Estimate a True Mortality Rate. (Github model: https://github.com/jwrichar/COVID19-mortality, full analysis https://github.com/jwrichar/COVID19-mortality/blob/master/COVID-19%20Mortality%20Rate.ipynb) | @HamelHusain, @jwrichar  <img src="https://img.shields.io/badge/-withcode-red"></img> <img src="https://img.shields.io/badge/library-py-9cf"></img>

3. **NobBS: Nowcasting by Bayesian Smoothing** - https://github.com/sarahhbellum/NobBS - NobBS is Bayesian approach to estimate the number of occurred-but-not-yet-reported cases from incomplete, time-stamped reporting data for disease outbreaks. NobBS learns the reporting delay distribution and the time evolution of the epidemic curve to produce smoothed nowcasts in both stable and time-varying case reporting settings. | sarahhbellum <img src="https://img.shields.io/badge/-withcode-red"></img> <img src="https://img.shields.io/badge/library-R-blue"></img>

4. **Scenario analysis for the transmission of COVID-19 in Georgia** - http://2019-coronavirus-tracker.com/stochastic-GA.html - The epidemiology of COVID-19 in the United States is poorly understood. To better understand the potential range of epidemic outcomes in the state of Georgia, we developed a model based on data from Hubei Province, China calibrated to regionally specific conditions in Georgia and observations of the number of reported cases in Georgia in early March. Github - https://github.com/CEIDatUGA/ncov-wuhan-stochastic-model | The Center for the Ecology of Infectious Diseases (CEID) at the University of Georgia <img src="https://img.shields.io/badge/-withcode-red"></img>

5. **Probability of widespread transmission** - http://2019-coronavirus-tracker.com/final-size.html; Github (private) - https://github.com/CEIDatUGA/ncov-coupled-outbreaks | The Center for the Ecology of Infectious Diseases (CEID) at the University of Georgia

6. **Spatial Spread of 2019 novel coronavirus in China** - http://2019-coronavirus-tracker.com/spatial-china.html  - We developed a gravity-based model to better understand the risk of spatial spread of the 2019-nCov at the prefecture level in China, and to determine the efficacy of quarantines imposed in Wuhan and other prefectures. Github (private) - https://github.com/CEIDatUGA/CoronavirusSpatial | The Center for the Ecology of Infectious Diseases (CEID) at the University of Georgia

7. **Effect of early intervention on outbreak size of COVID-19 in China** - http://2019-coronavirus-tracker.com/early-intervention.html - The epidemic of COVID-19 reached different areas of China at different times. This means that different locations were at different phases of outbreak at the time of the Wuhan lockdown (23 January) and other provincial and national actions. This provides what is sometimes called a “natural experiment” becuase it is as if replicate epidemics had been induced and then intervened on at different times. By looking at the effect of timing on outbreak size, we can draw conclusions about the effect of delaying intervention, which may be informative to other countries that are considering taking action. Github - https://github.com/CEIDatUGA/ncov-early-intervention | The Center for the Ecology of Infectious Diseases (CEID) at the University of Georgia

8. **Effect of mass testing** - http://2019-coronavirus-tracker.com/mass_testing.html - A symptom-based mass screening and testing intervention (MSTI) can identify a large fraction of infected individuals during an infectious disease outbreak. China is currently using this strategy for the COVID-19 outbreak. However, MSTI might lead to increased transmission if not properly implemented. We investigate under which conditions MSTI is beneficial. Github (private) - https://github.com/CEIDatUGA/CoV_MassTesting | The Center for the Ecology of Infectious Diseases (CEID) at the University of Georgia

9. **Epidemic Data Curves, Maps** - http://2019-coronavirus-tracker.com/data.html - Github (private) - https://github.com/CEIDatUGA/ncov-data-summary | The Center for the Ecology of Infectious Diseases (CEID) at the University of Georgia

10. **Nowcasting the current size of the COVID-19 outbreak in the United States** - http://2019-coronavirus-tracker.com/nowcast.html - At any given time, most COVID-19 cases are circulating in the community and not known to us. We wish to estimate the total current size of the COVID-19 outbreak (the total number of unnotified individuals currently infected with SARS-CoV2). Github (private) https://github.com/CEIDatUGA/ncov-nowcast, Global and US Parameters http://2019-coronavirus-tracker.com/parameters | The Center for the Ecology of Infectious Diseases (CEID) at the University of Georgia

11. **Speed of Spread of COVID-19** - http://2019-coronavirus-tracker.com/speed-of-spread.html By US State and Global - Epidemics of COVID-19 are occuring at different times across the United States so it is important to compare the spread of an epidemic in a given state with the appropriate stage in other countries. The following figures show the cumulative number of cases in a state by number of days since the 100th case, number of days since the 1st case, and by calendar date, respectively. Github (private) https://github.com/CEIDatUGA/ncov-data-summary | The Center for the Ecology of Infectious Diseases (CEID) at the University of Georgia

12. **COVID-19 in Context** - http://2019-coronavirus-tracker.com/context.html - How does the 2019 novel coronavirus disease (COVID-19) epidemic compare in severity to other recent disease outbreaks? We gathered data from existing studies to put COVID-19 into context. Github (private) https://github.com/CEIDatUGA/ncov-context | The Center for the Ecology of Infectious Diseases (CEID) at the University of Georgia

13. **Estimating $R_0$ and other parameters for the 2019-nCov epidemic** -The epidemiology of the global 2019-nCov is poorly understood. Identifying the key processes that shape transmission and estimating the relevant model parameters is therefore an important task. This document presents arguments and analysis to support the estimation of a number of key quantities - Epidemic curve, Basic reproduction number ($R_0$), Case detection rate (q), Incubation period ($\frac{1}{\sigma}$), Lag between symptom onset and isolation, Transmissibility ($\beta$), Additional parameters; http://2019-coronavirus-tracker.com/parameters-supplement.html | The Center for the Ecology of Infectious Diseases (CEID) at the University of Georgia

14. **Estimation of the effective reproduction number of COVID-19 outside China** - http://2019-coronavirus-tracker.com/reff-outside.html - What is the average $R_{eff}$ outside of China? | The Center for the Ecology of Infectious Diseases (CEID) at the University of Georgia; Github https://github.com/CEIDatUGA/ncov-Reff-outside-China  <img src="https://img.shields.io/badge/-withcode-red"></img>

15. **COVID-19 Growth Rate Prediction** - http://2019-coronavirus-tracker.com/stochastic.html - We developed a stochastic model to better understand the transmission of 2019-nCov in Hubei (primarily Wuhan). The model includes several features of the Wuhan outbreak that are absent from most compartmental models that otherwise confound the interpretation of data, including time-varying rates of case detection, patient isolation, and case notification. Github - https://github.com/CEIDatUGA/ncov-wuhan-stochastic-model, HTML http://2019-coronavirus-tracker.com/stochastic-model.html | The Center for the Ecology of Infectious Diseases (CEID) at the University of Georgia <img src="https://img.shields.io/badge/-withcode-red"></img>

16. **Extended state-space SIR epidemiological models** - https://github.com/lilywang1988/eSIR - R package eSIR: extended state-space SIR epidemiological models. The standard SIR model has three components: susceptible, infected, and removed (including the recovery and dead). In the following sections, we will introduce the other extended state-space SIR models and their implementation in the package. The results provided below are based on relatively short chains. | @lilywang1988 <img src="https://img.shields.io/badge/-withcode-red"></img>  <img src="https://img.shields.io/badge/library-R-blue"></img>

17. **JSON time-series of coronavirus cases (confirmed, deaths and recovered) per country - updated daily** - https://github.com/pomber/covid19- Transforms the data from CSSEGISandData/COVID-19 into a json file. Available at https://pomber.github.io/covid19/timeseries.json. Updated three times a day using GitHub Actions. | @pomber

18. **Genomic epidemiology of novel coronavirus** - https://nextstrain.org/ncov?c=country - Showing 838 of 838 genomes sampled between Dec 2019 and Mar 2020 | the NextStrain Team | nextstrain <img src="https://img.shields.io/badge/data-genome-red"></img>

19. **Phylodynamic Analysis** - http://virological.org/  - Novel 2019 coronavirus category| virological  <img src="https://img.shields.io/badge/data-genome-red"></img>

20. **Genomic epidemiology of hCoV-19** - https://www.gisaid.org/epiflu-applications/next-hcov-19-app/ - Showing 838 of 838 genomes sampled between Dec 2019 and Mar 2020.| GISAID <img src="https://img.shields.io/badge/data-genome-red"></img>

21. **Don’t “Flatten the Curve,” squash it!, with simulations Modeling COVID-19 Spread vs Healthcare Capacity** - https://alhill.shinyapps.io/COVID19seir/?fbclid=IwAR2aXJT79M2AmZxMdy8jsiEuSC4i7ijU8Av6oB4dmlZIeJ2VQgL7Tt3QGxA - The graph shows the expected numbers of individuals over time who are infected, recovered, susceptible, or dead over time. Infected individuals first pass through an exposed/incubation phase where they are asymptomatic and not infectious, and then move into a symptomatic and infections stage classified by the clinical status of infection (mild, severe, or critical).  | Alison Hill, Joscha Bach <img src="https://img.shields.io/badge/-withcode-red"></img>  <img src="https://img.shields.io/badge/library-R-blue"></img>

22. ***Ferguson, Neil M., et al. "Impact of non-pharmaceutical interventions (NPIs) to reduce COVID-19 mortality and healthcare demand."*** Impact of non-pharmaceutical interventions (NPIs) to reduce COVID19 mortality and healthcare demand - https://www.imperial.ac.uk/media/imperial-college/medicine/sph/ide/gida-fellowships/Imperial-College-COVID19-NPI-modelling-16-03-2020.pdf - Here we present the results of epidemiological modelling which has informed policymaking in the UK and other countries in recent weeks. | Imperial College COVID-19 Response Team, Neil M Ferguson et al. <img src="https://img.shields.io/badge/-paper-brightgreen"></img>

23. ***Li, Ruiyun, et al. "Substantial undocumented infection facilitates the rapid dissemination of novel coronavirus (SARS-CoV2)." Science (2020)*** https://science.sciencemag.org/content/early/2020/03/13/science.abb3221  - Here we use observations of reported infection within China, in conjunction with mobility data, a networked dynamic metapopulation model and Bayesian inference, to infer critical epidemiological characteristics associated with SARS-CoV2, including the fraction of undocumented infections and their contagiousness. | Li, Ruiyun, et al <img src="https://img.shields.io/badge/-paper-brightgreen"></img>

24.  ***Chan, Jasper Fuk-Woo, et al. "A familial cluster of pneumonia associated with the 2019 novel coronavirus indicating person-to-person transmission: a study of a family cluster." The Lancet 395.10223 (2020): 514-523.*** https://www.thelancet.com/journals/lancet/article/PIIS0140-6736(20)30154-9/fulltext?fbclid=IwAR1YTPBtlNUrZRvcE9sSBnOzJTOUR8sVK4nc54le5k4xXF3_WvjSuKW5BBU  - In this study, we report the epidemiological, clinical, laboratory, radiological, and microbiological findings of five patients in a family cluster who presented with unexplained pneumonia after returning to Shenzhen, Guangdong province, China, after a visit to Wuhan, and an additional family member who did not travel to Wuhan. | Chan, et al. <img src="https://img.shields.io/badge/-paper-brightgreen"></img>

25. **R library (coronavirus)**  https://ramikrispin.github.io/coronavirus/  - Github repo is here https://github.com/RamiKrispin/coronavirus | @RamiKrispin <img src="https://img.shields.io/badge/-withcode-red"></img>  <img src="https://img.shields.io/badge/library-R-blue"></img>

26. **Innophore protein modeling** https://innophore.com/2019-ncov/ - Validating the protease sequence | Innophore <img src="https://img.shields.io/badge/data-genome-red"></img>

27. **Wuhan coronavirus 2019-nCoV protease homology model** - https://3dprint.nih.gov/discover/3DPX-012867|  - Homolgy model by Phyre2 of the Wuhan coronavirus 2019-nCoV protease, https://innophore.com/2019-ncov From a PDB file in the PyMol session linked in that article.| NIH <img src="https://img.shields.io/badge/data-genome-red"></img>

28. **Coronavirus Simulator** - https://www.washingtonpost.com/graphics/2020/world/corona-simulator/,  Harry Stevens, Washington Post <img src="https://img.shields.io/badge/viz-simul-yellow"></img>

29. ***Chinazzi, Matteo, et al. "The effect of travel restrictions on the spread of the 2019 novel coronavirus (COVID-19) outbreak." Science (2020).*** - https://science.sciencemag.org/content/early/2020/03/05/science.aba9757 - Motivated by the rapid spread of COVID-19 in Mainland China, we use a global metapopulation disease transmission model to project the impact of travel limitations on the national and international spread of the epidemic. | Chinazzi, et al <img src="https://img.shields.io/badge/-paper-brightgreen"></img>

30. ***Li, Qun, et al. "Early transmission dynamics in Wuhan, China, of novel coronavirus–infected pneumonia." New England Journal of Medicine (2020).*** - https://www.nejm.org/doi/full/10.1056/NEJMoa2001316 - We analyzed data on the first 425 confirmed cases in Wuhan to determine the epidemiologic characteristics of NCIP. | Qun Li, et al <img src="https://img.shields.io/badge/-paper-brightgreen"></img>

31. ***Li, Ruiyun, et al. "Substantial undocumented infection facilitates the rapid dissemination of novel coronavirus (COVID-19)." medRxiv (2020).*** - https://www.medrxiv.org/content/medrxiv/early/2020/02/17/2020.02.14.20023127.full.pdf - Estimation of the fraction and contagiousness of undocumented novel coronavirus (COVID-19) infections is critical for understanding the overall prevalence and pandemic potential of this disease. Github - https://github.com/SenPei-CU/COVID-19 | Li, Pen, et al.  <img src="https://img.shields.io/badge/-paper-brightgreen"></img>  <img src="https://img.shields.io/badge/-withcode-red"></img>

32. **Fighting Fatal Coronavirus Using Knowledge Graph** - https://community.neo4j.com/t/fighting-fatal-coronavirus-using-knowledge-graph/14634 - uses neo4j http://v.we-yun.com:2020/browser/ | Zhi Zhang from we-yun.com <img src="https://img.shields.io/badge/data-noneng-lightgray"/></img>  <img src="https://img.shields.io/badge/model-graph-yellow"></img>

33. **Using Nebula graph** - Detect Corona Virus Spreading With Graph Database Based on a Real Case https://nebula-graph.io/en/posts/detect-corona-virus-spreading-with-graph-database/  <img src="https://img.shields.io/badge/model-graph-yellow"></img> <img src="https://img.shields.io/badge/-withcode-red"></img>

34. ***Maier, Benjamin F., and Dirk Brockmann. "Effective containment explains sub-exponential growth in confirmed cases of recent COVID-19 outbreak in Mainland China." arXiv preprint arXiv:2002.07572 (2020).*** - https://arxiv.org/pdf/2002.07572.pdf  <img src="https://img.shields.io/badge/-paper-brightgreen"></img>

35. **Mesa: Agent-based modeling in Python 3+** https://github.com/projectmesa/mesa  <img src="https://img.shields.io/badge/library-py-9cf"></img> <img src="https://img.shields.io/badge/-withcode-red"></img>

36. **Excess cases of Influenza like illnesses in France synchronous with COVID19 invasion**. Pierre-Yves Boëlle1 and the Sentinelles syndromic and viral surveillance group, Sorbonne Université, Institut Pierre Louis d’Epidemiologie et de Santé Publique, Paris, France - https://www.epicx-lab.com/uploads/9/6/9/4/9694133/sentinelles-2020-03-11.pdf <img src="https://img.shields.io/badge/-paper-brightgreen"></img>

37. ***Severe Outcomes Among Patients with Coronavirus Disease 2019 (COVID-19) — United States, February 12–March 16, 2020*** - https://www.cdc.gov/mmwr/volumes/69/wr/mm6912e2.htm?s_cid=mm6912e2_w - This first preliminary description of outcomes among patients with COVID-19 in the United States indicates that fatality was highest in persons aged ≥85, ranging from 10% to 27%, followed by 3% to 11% among persons aged 65–84 years, 1% to 3% among persons aged 55-64 years, <1% among persons aged 20–54 years, and no fatalities among persons aged ≤19 years. <img src="https://img.shields.io/badge/-paper-brightgreen"></img> <img src="https://img.shields.io/badge/-NEW-yellow"></img>

38. ***Remuzzi, Andrea, and Giuseppe Remuzzi. "COVID-19 and Italy: what next?." The Lancet (2020).*** - https://www.thelancet.com/journals/lancet/article/PIIS0140-6736(20)30627-9/fulltext?fbclid=IwAR3ke0W7zk58fdCwz_FJGw8VzAiVUveYng6mZmeHPsfBVW5814xlDd_yNgE - The spread of severe acute respiratory syndrome coronavirus 2 (SARS-CoV-2) has already taken on pandemic proportions, affecting over 100 countries in a matter of weeks. A global response to prepare health systems worldwide is imperative. Although containment measures in China have reduced new cases by more than 90%, this reduction is not the case elsewhere, and Italy has been particularly affected. <img src="https://img.shields.io/badge/-paper-brightgreen"></img> <img src="https://img.shields.io/badge/-NEW-yellow"></img>

39. ***Wu, Ke, et al. "Generalized logistic growth modeling of the COVID-19 outbreak in 29 provinces in China and in the rest of the world." arXiv preprint arXiv:2003.05681 (2020).*** - https://arxiv.org/pdf/2003.05681.pdf - Background: the COVID-19 has been successfully contained in China but is spreading all over the world. We use phenomenological models to dissect the development of the epidemics in China and the impact of the drastic control measures both at the aggregate level and within each province. We use the experience from China to analyze the calibration results on Japan, South Korea, Iran, Italy and Europe, and make future scenario projections.  The datasets generated and analysed during the current study are available in the Github repository, https://github.com/kezida/covid-19-logistic-paper <img src="https://img.shields.io/badge/-paper-brightgreen"></img> <img src="https://img.shields.io/badge/-NEW-yellow"></img> <img src="https://img.shields.io/badge/-withcode-red"></img>

40. **Visual Data Analysis and Simulation Prediction for COVID-19** - Baoquan Chen, Mingyi Shi, Xingyu Ni, Liangwang Ruan, Hongda Jiang, Heyuan Yao, Mengdi Wang, Zhenhua Song, Qiang Zhou, Tong Ge - In this study, we seek to answer a few questions: How did the virus get spread from the epicenter Wuhan city to the rest of the country? To what extent did the measures, such as, city closure and community quarantine, help controlling the situation? More importantly, can we forecast any significant future development of the event had some of the conditions changed? By collecting and visualizing publicly available data, we first show patterns and characteristics of the epidemic development; we then employ a mathematical model of disease transmission dynamics to evaluate the effectiveness of some epidemic control measures, and more importantly, to offer a few tips on preventive measures. - https://arxiv.org/abs/2002.07096, with code https://github.com/NCP-VIS <img src="https://img.shields.io/badge/-paper-brightgreen"></img> <img src="https://img.shields.io/badge/-NEW-yellow"></img>  <img src="https://img.shields.io/badge/-withcode-red"></img>

41. ***Peng, Liangrong, et al. "Epidemic analysis of COVID-19 in China by dynamical modeling." arXiv preprint arXiv:2002.06563 (2020).*** - https://arxiv.org/pdf/2002.06563.pdf Based on the public data of National Health Commission of China from Jan. 20th to Feb. 9th, 2020, we reliably estimate key epidemic parameters and make predictions on the inflection point and possible ending time for 5 different regions. <img src="https://img.shields.io/badge/-paper-brightgreen"></img> <img src="https://img.shields.io/badge/-NEW-yellow"></img>

42. ***Li, Ming, Jie Chen, and Youjin Deng. "Scaling features in the spreading of COVID-19." arXiv preprint arXiv:2002.09199 (2020).*** - https://arxiv.org/pdf/2002.09199.pdf Since the outbreak of COVID-19, many data analysis have been done. Some of them are based on the classical epidemiological approach that assumes an exponential growth, but a few studies report that a power-law scaling may provide a better fitting to the currently available data. Hereby, we examine the epidemic data in China mainland (01/20/2020–02/24/2020) in a log-log scale, and indeed find that the growth closely follows a power-law kinetics over a significantly wide time period. <img src="https://img.shields.io/badge/-paper-brightgreen"></img> <img src="https://img.shields.io/badge/-NEW-yellow"></img>

43. ***Biswas, Kathakali, Abdul Khaleque, and Parongama Sen. "Covid-19 spread: Reproduction of data and prediction using a SIR model on Euclidean network." arXiv preprint arXiv:2003.07063 (2020).***  - https://arxiv.org/pdf/2003.07063.pdf We study the data for the cumulative as well as daily number of cases in the Covid-19 outbreak in
China. The cumulative data can be fit to an empirical form obtained from a Susceptible-InfectedRemoved (SIR) model studied on an Euclidean network previously. Plotting the number of cases against the distance from the epicenter for both China and Italy, we find an approximate power law variation with an exponent ∼ 1.85 showing strongly that the spatial dependence plays a key role, a factor included in the model. <img src="https://img.shields.io/badge/-paper-brightgreen"></img> <img src="https://img.shields.io/badge/-NEW-yellow"></img>

44. **COVID-2020 SIR** - https://github.com/amita-kapoor/COVID-2020 @amita-kapoor <img src="https://img.shields.io/badge/-withcode-red"></img> <img src="https://img.shields.io/badge/library-py-9cf"></img> <img src="https://img.shields.io/badge/-NEW-yellow"></img>

45. **Evidation Health** - https://evidation.com/news/covid-19-pulse-first-data-evidation/ - To understand how Americans are coping with the spread of COVID-19, Evidation Health, the health and measurement company, has launched a nationwide initiative tracking people’s attitudes toward and experiences during the pandemic, alongside their health. Over 140,000 (as of March 22) people from across all 50 states and the District of Columbia have agreed to participate, recruited in less than seven days from the nearly 4 million people who use Evidation’s Achievement app—the largest, most diverse virtual research site in the U.S.  <img src="https://img.shields.io/badge/viz-map-brightgreen"></img> <img src="https://img.shields.io/badge/-charts-yellow"></img> <img src="https://img.shields.io/badge/-NEW-yellow"></img>

46. **CoronaTracker: World-wide COVID-19 Outbreak Data Analysis and Prediction
CoronaTracker Community Research Group**  - https://www.who.int/bulletin/online_first/20-255695.pdf CoronaTracker was born as the online platform that provides latest and reliable news development, as well as statistics and analysis on COVID-19. This paper is done
by the research team in the CoronaTracker community and aims to predict and forecast COVID19 cases, deaths, and recoveries through predictive modelling. The model helps to interpret patterns of public sentiment on disseminating related health information, and assess political and economic influence of the spread of the virus. <img src="https://img.shields.io/badge/-NEW-yellow"></img>

47. **Array Advisors’ Model Validates Fears of ICU Bed Shortage Due to Coronavirus Pandemic** - https://array-architects.com/press-release/array-advisors-model-validates-fears-of-icu-bed-shortage-due-to-coronavirus-pandemic/ Array Advisors has built a model that projects the availability of U.S. hospital beds as the coronavirus pandemic grows. The model validates fears that a shortage of beds may occur unless efforts to expand hospital capacity are implemented immediately. Runnable model in Excel. <img src="https://img.shields.io/badge/-NEW-yellow"></img> <img src="https://img.shields.io/badge/-withcode-red"></img>

48. **CHIME (COVID-19 Hospital Impact Model for Epidemics) Application** - https://github.com/CodeForPhilly/chime - The CHIME (COVID-19 Hospital Impact Model for Epidemics) Application is designed to assist hospitals and public health officials with understanding hospital capacity needs as they relate to the COVID pandemic. CHIME enables capacity planning by providing estimates of total daily (i.e. new) and running totals of (i.e. census) inpatient hospitalizations, ICU admissions, and patients requiring ventilation. These estimates are generated using a SIR (Susceptible, Infected, Recovered) model, a standard epidemiological modeling technique. <img src="https://img.shields.io/badge/-NEW-yellow"></img> <img src="https://img.shields.io/badge/-withcode-red"></img>

49. ***Mapping hospital demand: demographics, spatial variation, and the risk of “hospital deserts” during COVID-19 in England and Wales*** - https://osf.io/g8s96/?fbclid=IwAR1hnVIYboDrFL9aZqg-F2js7Bs4JxGf3GT_uYV4KUIApR4kAggP78jsdiE <img src="https://img.shields.io/badge/-NEW-yellow"></img> <img src="https://img.shields.io/badge/-paper-brightgreen"></img>

50. **FluTE, an influenza epidemic simulation model** - https://www.cs.unm.edu/~dlchao/flute/ - FluTE generates text output files, which can be easily processed with use-supplied scripts. In this example, we import the results from a US simulation into ArcGIS to generate a heatmap showing illness prevalence. <img src="https://img.shields.io/badge/-NEW-yellow"></img>

51. ***Chinazzi, Matteo, et al. "The effect of travel restrictions on the spread of the 2019 novel coronavirus (COVID-19) outbreak." Science (2020).*** - https://science.sciencemag.org/content/sci/early/2020/03/05/science.aba9757.full.pdf?casa_token=oH5UDZMQnKoAAAAA:YOfrQGSjNkTOqVmgAjp-O4sbGbdS__ihgi_pr9y_O8E3QyVQlpcvoSkx1Oasp8sz3Ep6Qq49VdlJHzU - Motivated by the rapid spread of COVID-19 in Mainland China, we use a global metapopulation disease transmission model to project the impact of travel limitations on the national and international spread of the epidemic. The model is calibrated based on internationally reported cases, and shows that at the start of the travel ban from Wuhan on 23 January 2020, most Chinese cities had already received many infected travelers.  <img src="https://img.shields.io/badge/-paper-brightgreen"></img> <img src="https://img.shields.io/badge/-NEW-yellow"></img>

52. **Covid Act Now** - https://covidactnow.org/ - CovidActNow.org was created by a team of data scientists, engineers, and designers in partnership with epidemiologists, public health officials, and political leaders to help understand how the COVID-19 pandemic will affect their region. CoVidActNow was founded by Max Henderson, Rep Jonathan Kreiss-Tomkins, Igor Kofman, and Zack Rosen, with medical and policy guidance from Nirav R. Shah (MD, MPH, senior scholar, Stanford University Clinical Excellence Research Center). <img src="https://img.shields.io/badge/viz-map-brightgreen"></img> <img src="https://img.shields.io/badge/-NEW-yellow"></img>

# Link to Journals via Google Scholar <a name="journals"/>
There are a variety of papers being published every day. Check out the below to keep up to date with the latest articles.
- Digital Access to Scholarship for Harvard (DASH) - https://dash.harvard.edu/handle/1/42599304
- CDC - https://www.cdc.gov/coronavirus/2019-ncov/publications.html
- NEJM - https://www.nejm.org/coronavirus
- JAMA - https://jamanetwork.com/journals/jama/pages/coronavirus-alert
- Lancet - https://www.thelancet.com/coronavirus
- Cell - https://www.cell.com/2019-nCOV
- BMJ - https://www.bmj.com/coronavirus
- Elsevier - https://www.elsevier.com/connect/coronavirus-information-center
- Oxford - https://academic.oup.com/journals/pages/coronavirus
- Nature - https://www.nature.com/collections/hajgidghjb
- Wiley - https://novel-coronavirus.onlinelibrary.wiley.com/
- Cambridge - https://www.cambridge.org/core/browse-subjects/medicine/coronavirus-free-access-collection
- medRxiv - http://connect.medrxiv.org/relate/content/181


# Channels and Social Media <a name="sm"/>
1. **Covid-2019 Reddit Map Community** - https://www.reddit.com/r/CovidMapping/ <img src="https://img.shields.io/badge/sm-reddit-red"></img>

2. **Coronavirus: Why You Must Act Now** - https://medium.com/@tomaspueyo/coronavirus-act-today-or-people-will-die-f4d3d9cd99ca <img src="https://img.shields.io/badge/sm-medium-black"></img>

3. **Estimating the Number of Future Coronavirus Cases in the United States** - https://towardsdatascience.com/estimating-the-number-of-future-coronavirus-cases-in-the-united-states-a0ce17df029a <img src="https://img.shields.io/badge/sm-medium-black"></img>

4. https://threadreaderapp.com/thread/1237347774951305216.html, @mlipsitch, with https://github.com/c2-d2/COVID-19-wuhan-guangzhou-data <img src="https://img.shields.io/badge/sm-thread-blue"></img>

5. https://threadreaderapp.com/thread/1238972082756648960.html, @@davidasinclair <img src="https://img.shields.io/badge/sm-thread-blue"></img>

6. **Modelling the coronavirus epidemic in a city with Python** - https://towardsdatascience.com/modelling-the-coronavirus-epidemic-spreading-in-a-city-with-python-babd14d82fa2  <img src="https://img.shields.io/badge/-withcode-red"></img> <img src="https://img.shields.io/badge/-NEW-yellow"></img> <img src="https://img.shields.io/badge/sm-medium-black"></img>

7. Top 15 R resources on Novel COVID-19 Coronavirus - https://towardsdatascience.com/top-5-r-resources-on-covid-19-coronavirus-1d4c8df6d85f <img src="https://img.shields.io/badge/library-R-blue"></img> <img src="https://img.shields.io/badge/-NEW-yellow"></img>

# Deep Learning Models <a name="dl"/>

1. ***Wang, Yunlu, et al. "Abnormal respiratory patterns classifier may contribute to large-scale screening of people infected with COVID-19 in an accurate and unobtrusive manner." arXiv preprint arXiv:2002.05534 (2020).*** - https://arxiv.org/pdf/2002.05534.pdf <img src="https://img.shields.io/badge/-paper-brightgreen"></img> <img src="https://img.shields.io/badge/dl-cv-green"></img>

2. ***Xu, Xiaowei, et al. "Deep Learning System to Screen Coronavirus Disease 2019 Pneumonia." arXiv preprint arXiv:2002.09334 (2020).*** - https://arxiv.org/pdf/2002.09334.pdf <img src="https://img.shields.io/badge/-paper-brightgreen"></img> <img src="https://img.shields.io/badge/dl-cv-green"></img>


3. ***Chen, Jun, et al. "Deep learning-based model for detecting 2019 novel coronavirus pneumonia on high-resolution computed tomography: a prospective study." medRxiv (2020).*** - https://www.medrxiv.org/content/medrxiv/early/2020/02/26/2020.02.25.20021568.full.pdf <img src="https://img.shields.io/badge/-paper-brightgreen"></img> <img src="https://img.shields.io/badge/dl-cv-green"></img>


**Thanks**:<pr>
- Badges made using https://shields.io/
- References: Google Scholar, JHU, Midas, Multiple Twitter Accounts
- Recommendations from LinkedIn and Twitter
