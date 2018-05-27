### An Analysis of Home Healthcare Quality Measures and How to Increase Star Rating ###

*Jonathan King*

***
**The Problem:** 

Beginning in July of 2015 the Centers for Medicare & Medicaid Services (CMS) began publishing a star rating system for Home Health Care (HHC) Agencies who provide services to Medicare and Medicaid clients.  The star ratings and quality measures are updated quarterly and a report is produced for each update.

Furthermore, CMS created the Home Health Compare website, which allows consumers to search for HHC agencies in their area and compare them based on these quality measures and star ratings.  As such, it has become imperative for HHC agencies to increase their star ratings to compete with one another and attract more consumers.

[Home Health Compare Website](https://www.medicare.gov/homehealthcompare/search.html)

This problem will be approached as though a HHC agency has requested assistance from a consulting company to increase their overall star rating.  Since all companies have their limitations, the outcome of this project would be to identify the top three quality measures the client would need to improve to increase their star rating. 

***
**The Client:** 

As stated in the introduction, HHC agencies would be the primary client for this project.  The client would care about this problem because this could directly affect the number of consumers seeking services from the client.  Furthermore, this analysis would provide the client immediate measures to focus on, which would effectively and efficiently increase their overall score.  Moreover, a higher star rating is a great marketing opportunity for the clients marketing team to use in a campaign to acquire more consumers.

***
**The Data:** 

CMS has provided open data [online](https://data.medicare.gov/data/home-health-compare) that contains the data set regarding this analysis.  

I will be acquiring and utilizing the Home Health Care Agencies data set from the website listed above as it contains comprehensive quality measure data for each HHC agency.  This will significantly increase the observations available to me over the national reports that group quality measures and star ratings by state.

The specific Home Health Care Agencies dataset can be found [here](https://data.medicare.gov/Home-Health-Compare/Home-Health-Care-Agencies/6jpm-sxkc).

***
**Approach Outline:**

First, I intend to clean the data and prepare it for analysis.  This would include filtering out missing data in the observations and assigning string and true/false values categorical or Boolean assignments.

Second, I will create data visualizations to compare ratings, measures, and counts, along with some inferential statistics, to determine what measures have the highest correlation with star rating.

Finally, I will use supervised machine learning to test its predictive capabilities using star rating as my classifier.  Upon obtaining an optimized model, I will select a real agency from the data and, using its quality measures, have the model list the three top quality measures that would best improve the agency’s star rating.

***
**Deliverables:** 

My deliverables will include a narrative of the project in the form of a paper, the code, and a PowerPoint slide deck, which will be made available as part of a GitHub repository.