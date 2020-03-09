---
layout: page
title:  "Team news"
lang: en
permalink: "/team-news/"
trans_url: "/nouvelles-dequipe/"
---

## Blog posts

The team has written blog posts about our work and our processes:

July 30, 2019: [**Growing Service Design and Design Research at PSPC**](https://digital.canada.ca/2019/07/30/growing-service-design-and-design-research-at-pspc/), Emilio Franco Senior Director of Procurement Business Modernization at PSPC.

## Prototypes

*Please note, the information contained in each prototype is not current and is for learning and testing purposes only.*  

### [Prototype 1, "Aggregate"](https://github.com/cds-snc/pspc-spa-aggregator): Aggregating multiple data sets

Aggregate is a way to understand how a single point of access might get data from multiple buyer organizations by an automated protocol to display tender notices. Building a prototype and testing integrations early helps create working relationships with other buyer organizations and helps us understand their constraints. 

Aggregate converts data from province and territories' existing data schemas and formats into the Open Contracting Data Standard (OCDS) and JSON, and stores it in a database for a front-end and API to be built on. During Discovery the team worked with provincial and territorial counterparts to make integration as easy as possible. 

[**Code base**](https://github.com/cds-snc/pspc-spa-aggregator)

### [Prototype 2, "Explore"](https://dsinclair-spa.herokuapp.com/): Get data, visualize it.

Explore, is a very low fidelity way to understand what the aggregated content from various buyer organizations looks like on a single site. The team developed a prototype in a few days that randomly selects 25 tenders from single-point-in-time data dumps provided by the federal government and 7 provinces and territories. 

Explore helped the team identify the need for guidance on plain language titles and descriptions, missing information in the available data, and discrepancies in data quality. These findings supported the team in developing a taxonomy for tender summaries and guidance for plain language titles and descriptions.

### [Prototype 3, "Filter"](https://single-point-of-access.herokuapp.com/en/start?filters=&gsin=): What can we build given the current data?

As the title suggests, Filter was a low effort way to understand how a single point of access could filter and display results based on the available data provided currently by the federal government and 3 provinces and territories. The team developed a prototype in two weeks to support the most basic user flow to filter opportunities.   

Filter helped the team confirm basic data quality assumptions like, which fields are necessary to support a feature that refines tender notices. It also helped the team surface complexity associated with the using the Government Services and Goods Identification number as the primary means of filtering.

[**Code base**](https://github.com/cds-snc/single-point-of-access-data)





