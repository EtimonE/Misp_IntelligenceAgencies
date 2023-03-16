# Misp_IntelligenceAgencies
MISP Project - Intelligence Agencies

## Context
This project is part of the Master 2, SSI, in the UFR-MIM in Metz and serves as project and mark for our class "Threat Intelligence. The goal of this project is to scrap existing data from various websites to create a taxonomy or a galaxy in the MISP repository, to enable the possibility for anyone to use it later while working with/on MISP. 
For this Project, we decided to create a taxonomy of the different Intelligence Agencies around the world sorted by country, with the purpose to integrate it into MISP.

## Site Scraping and Creation of the JSON File
Usage of the website https://en.wikipedia.org/wiki/List_of_intelligence_agencies for the different Intelligence Agencies.
We dug further and tried to find other websites, but none were of interest to us because the agencies listed elsewhere were already listed on the Wikipedia page.

To scrape the site, we wrote a code in python using beautifulsoup and http request to be able to read the data before storing it in a dictionary.

Creation of a taxonomy that would fit the MISP requirements in order to output a JSON File with the taxonomy according to the different Countries where each country lists its Intelligence Agencies.

## TO-DO LIST
 Scrape the website with helps of a python code
 Creating a MISP formatted Taxonomy
 Creating JSON File based on the Taxonomy
 Verifying if the format is working
 -Validation by the MISP team in charge of project
 -Integration to the MISP project
 -End of project

