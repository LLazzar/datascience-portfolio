## • Spain Data Job Dashboard
>> [![](https://img.shields.io/badge/Github-View_on_Github-blue?logo=Github&style=flat-square)](https://github.com/lorenzolazzari98/dash-profesion-data-es) [![](https://img.shields.io/badge/Powerbi-Open_live_dashboard-yellow?logo=powerBI&style=flat-square)](https://app.powerbi.com/view?r=eyJrIjoiZDM1Y2MyY2UtOTdkNi00YTZlLWFmMTYtMzY4ZGViN2IxOGVlIiwidCI6Ijc4NDg0MWU1LTAxYjEtNGQ5My04NzczLTUwYzcxYWI4NWMzYiIsImMiOjl9) 
>>
>> **Context** = *Personal project*
>> 
>> **Keywords** = `Scraping` `NoSQL Database` `Azure CosmosDB` `Azure Functions` `PowerBI` `Español`
> 
> <img src="https://github.com/lorenzolazzari98/dash-profesion-data-es/blob/main/figures/cover.jpg?raw=true" width=430> 
> 
> This project aims to create a publicly accessible Power BI dashboard that displays real-time data about job offers and salaries in the data field, specifically in Spain. The dashboard provides historical records of the data and analyzes four main job categories: Data Engineer, Data Scientist, Data Analyst, and Business Analyst. This is achieved by deploying an Azure Function to scrape data from glassdoor.es, the Spanish version of Glassdoor, using Beautiful Soup, which is triggered daily by a timer. The data is then uploaded to an Azure Cosmos DB NoSQL database and accessed by Power BI to generate visualizations for the dashboard. The dashboard refreshes daily to reflect the new data loaded into the database. The live dashboard is available [here](https://app.powerbi.com/view?r=eyJrIjoiZDM1Y2MyY2UtOTdkNi00YTZlLWFmMTYtMzY4ZGViN2IxOGVlIiwidCI6Ijc4NDg0MWU1LTAxYjEtNGQ5My04NzczLTUwYzcxYWI4NWMzYiIsImMiOjl9)
> 

<br>

## • Commit Classification using NLP
>> [![](https://img.shields.io/badge/Github-View_on_Github-blue?logo=Github&style=flat-square)](https://github.com/lorenzolazzari98/commit-classification) [![](https://img.shields.io/badge/Jupyter-Open_main_notebook-orange?logo=jupyter&style=flat-square)](https://github.com/lorenzolazzari98/commit-classification/blob/main/scripts/Commit_Classification.ipynb) 
>>
>> **Context** = *University Project*
>> 
>> **Keywords** = `Supervised Learning` `NLP` `Text Preprocessing (Stem, Lem)` `Text Vectorization (n-gram,skip-gram)` `Logistic Regression` `Fasttext by Facebook`
> 
> <img src="https://raw.githubusercontent.com/lorenzolazzari98/commit-classification/main/figures/data_example.jpg" width=310> <img src="https://raw.githubusercontent.com/lorenzolazzari98/commit-classification/c15d9775b7d5c70bebbe9179780adbebece193de/figures/logit_confusion_matrix.png" width=120 length=120>
> 
> In this project, I aimed to replicate the work done in [this paper](https://raw.githubusercontent.com/lorenzolazzari98/commit-classification/c15d9775b7d5c70bebbe9179780adbebece193de/reference/paper.pdf). The project started with a 5-class labeled dataset of commit messages, and classical NLP techniques such as data cleaning and feature extraction were used to preprocess the data. Then, several baseline classification models were fitted and evaluated. One of the models was chosen and fine-tuned using RepeatedKFold validation. Finally, the chosen model (a logistic regression) was evaluated on the test set to measure its performance.
> 

