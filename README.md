# Final Project for PPOL-670

This is the public repository for final project, PPOL 670.

## Which *Sustainable Development Goals (SDG)* are linked in the country's *Nationally Determined Contributions (NDC)* document?  

### Introduction
This project aims to use supervised machine learning model to identify potential alignment between the targets, actions, policy measures and plans in countries' Nationally Determined Contributions (NDCs) and the Sustainable Development Goals (SDGs).  

A Treemap is generated first to show the general distribution of NDC-SDG linkages. And Term Frequency - Inverse Document Frequency (tf-idf) is used here to further create the bar chart groups, which shows the important words for each sustainable development goals. Bigrams are also used here to analyze the relationships between words.

And three supervised machine learning models are used here: Random Forest, K-Nearest Neighbor, and Neural Network. The Random Forest model with number of trees equals to 100 will give us the largest accuracy, which is 55.2%, and over 75% accuracy for Sustainable Development Goal 7, 13, 15, 17.

### Keywords
Sustainable Development Goals, National Determined Contributions, Text Analysis, NLP, Classification

### Data Source
1. Nationally Determined Contributions submissions: [NDC Registry, UNFCCC.](https://www4.unfccc.int/sites/NDCStaging/Pages/All.aspx)
2. Sustainable Development Goals: [Sustainable Development Goals Knowledge Platform, United Nations](https://sustainabledevelopment.un.org/sdgs)
3. NDC-SDG linkages analysis data: [Climate Watch, World Resources Institute.](https://www.climatewatchdata.org/data-explorer/ndc-sdg-linkages?ndc-sdg-linkages-countries=All%20Selected&ndc-sdg-linkages-goals=All%20Selected&ndc-sdg-linkages-sectors=All%20Selected&ndc-sdg-linkages-targets=All%20Selected&page=1)

### File included
* This README.md file.
* The index.md file.
* The project proposal .pdf file.
* The .Rmd file with the detailed R code.
* The result .html file.
* The raw data .csv file.

