# koalabase

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0) 

My Volunteer research on data from "Koalabase" Hospital and sightings data. An attempt to help shed light on the concerning rapid decline of the koala in South East Queensland. 

For full analysis, see my [website](https://dataviz.com.au/2018/06/06/koalabase-disease-and-accident-hospital/)

South East Queensland koalas are currently undergoing a major population decline. Data on major causes of koala disease or injury has been collected, but no detailed epidemiological studies on morbidity and mortality exist. Additionally, a lack of standardised pathological analysis and scientific data management procedures to compile and analyse disease and mortalities, are major constraints on understanding the threats to SE-QLD koalas.” – From the University of Queensland Koalabase website

KoalaBASE is an online database that summarizes data collected on koala mortalities and morbidities in South East Queensland and has been published by the Queensland Government. The database has approximately 40,000 rows from 1996 to 2017,  each row contains very granular incident or sighting of a Koala that made its way to the Koala Hospital. The data may include details such as the presence of younger koalas – and if they are now orphaned, Cause  (eg Car strike, Falls, Dog attacks) and observations on the presence of two forms of common eye disease. Importantly geolocation data is also recorded, and this allows for spatial-temporal analysis over time.

Through the generous volunteering program of my employer Salesforce I was able to take some time out to dig deep into this data, whilst practicing skills and working with tools that I use on a daily basis to detect malicious activity in the Information Security field for Salesforce. From Information security to studying sick Koalas, Data is Data and a lot of the same challenges exist in both fields in terms of complexity and volume.

After some data cleansing scripts, I used tools such as Splunk and Google Maps to provide a dynamic viewpoint for experts to study clusters based on dynamic queries on the dataset. Screenshot examples follow.

Whilst I am only a layperson, one observation was that the seasons consistently mapped to car strikes, as did almost all other disease and mortality stats, possibly due to increased movement during these seasons.  A practical outcome of data and observations like this is that controls such as fencing, lighting, speed limits and education may be introduced to coincide with the seasonal movement of koalas, so as to lessen the chance of car strikes in known hot spots, which can be dynamically viewed as clusters on the zoom-able maps.

This volunteer work is ongoing, as the Veterinarians and Researchers suggest additional ways to filter and view the dataset that will help answer the key questions and arrest the population decline.

