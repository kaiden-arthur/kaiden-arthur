---
name: Trimet Usage Data
tools: [Python, R, GitHub]
image: ../bus station.jpg
description: MSDS Capstone project, summer 2025
---

# Trimet Usage Data

For my capstone project in the MSDS program, my group worked with TriMet's Spring 2025 usage data and schedule information, focusing on predicting usage of a given stop based on some features calculated using the schedule data. 

We found that the features we engineered from schedule data had some interesting effects on usage and were relatively predictive, but that our models would benefit from the addition of additional predictive features such as location data and neighborhood context.

### Workflow and Skills Used
My section of the data collection process focused on webscraping schedule data from the TriMet website, using requests and BeautifulSoup. 

For the analysis, I created a number of machine learning models, including a final random forest. I also worked heavily on creating visuals for this project. 

<p class="text-center">
{% include elements/button.html link="https://wu-msds-capstones.github.io/trimet-usage-data/" text="Read the Report" %}

{% include elements/button.html link="https://github.com/wu-msds-capstones/pdx-project-workbook-kaiden-denton-capstone" text="Repository" %}
</p>