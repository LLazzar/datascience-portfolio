## • Graphical displays to better understand ML classifiers results
>> [![](https://img.shields.io/badge/Github-classmapExt_R_package-blue?logo=Github&style=flat-square)](https://github.com/llazzar/classmapExt) [![](https://img.shields.io/badge/PDF-Paper_draft-red?logo=adobeacrobatreader&style=flat-square)](https://llazzar.github.io/datascience-portfolio/projectsMetadata/masterThesis/draft_paper.pdf) [![](https://img.shields.io/badge/R-NSC_data_classification_draft-9cf?logo=rstudio&style=flat-square)](https://llazzar.github.io/datascience-portfolio/projectsMetadata/masterThesis/PAMR_analysis.html)
>>
>> **Context** = *Master Research Thesis*
>> 
>> **Keywords** = `ML classifiers` `Diagnostic` `Visualizations Tools` `R Package Development` `Silhouttes` `High Dimensional Data` `Genomics` `Genomics` `RNA-seq pipelines` `Research`
> 
> <img src="https://raw.githubusercontent.com/LLazzar/datascience-portfolio/master/projectsMetadata/masterThesis/masterthesis_project.png" width=430> 
> 
> In my ongoing master's thesis, I explore novel machine learning (ML) visualization tools like Silhouettes, Class Maps, and Quasi-residual plots, accessible via the R "classmap" package. A new tool, MDScolorscale, is introduced to further enhance these visualization methods. This work also develops a versatile function that allows the use of these graphical tools for almost any ML classifier, extending their current applicability. An extension package named ["classmapExt"](https://github.com/LLazzar/classmapExt) is released. Practical application of these methods is illustrated by using them to diagnose gene-expression-based cancer classifications with the Nearest Shrunken Centroid Classifier and the XGBoost classifier. Draft of paper along with drafts of data analysis demonstrating the visualizations adapted for the methods are available at the links
> 

<br>

## • Spain Data Job Dashboard
>> [![](https://img.shields.io/badge/Github-View_on_Github-blue?logo=Github&style=flat-square)](https://github.com/llazzar/dash-profesion-data-es) [![](https://img.shields.io/badge/Powerbi-Open_live_dashboard-yellow?logo=powerBI&style=flat-square)](https://app.powerbi.com/view?r=eyJrIjoiZDM1Y2MyY2UtOTdkNi00YTZlLWFmMTYtMzY4ZGViN2IxOGVlIiwidCI6Ijc4NDg0MWU1LTAxYjEtNGQ5My04NzczLTUwYzcxYWI4NWMzYiIsImMiOjl9) 
>>
>> **Context** = *Personal project*
>> 
>> **Keywords** = `Scraping` `NoSQL Database` `Azure CosmosDB` `Azure Functions` `PowerBI` `Español`
> 
> <img src="https://github.com/llazzar/dash-profesion-data-es/blob/main/figures/cover.jpg?raw=true" width=430> 
> 
> This project aims to create a publicly accessible Power BI dashboard that displays real-time data about job offers and salaries in the data field, specifically in Spain. The dashboard provides historical records of the data and analyzes four main job categories: Data Engineer, Data Scientist, Data Analyst, and Business Analyst. This is achieved by deploying an Azure Function to scrape data from glassdoor.es, the Spanish version of Glassdoor, using Beautiful Soup, which is triggered daily by a timer. The data is then uploaded to an Azure Cosmos DB NoSQL database and accessed by Power BI to generate visualizations for the dashboard. The dashboard refreshes daily to reflect the new data loaded into the database. The live dashboard is available [here](https://app.powerbi.com/view?r=eyJrIjoiZDM1Y2MyY2UtOTdkNi00YTZlLWFmMTYtMzY4ZGViN2IxOGVlIiwidCI6Ijc4NDg0MWU1LTAxYjEtNGQ5My04NzczLTUwYzcxYWI4NWMzYiIsImMiOjl9)
> 

<br>

## • Commit Classification using NLP
>> [![](https://img.shields.io/badge/Github-View_on_Github-blue?logo=Github&style=flat-square)](https://github.com/llazzar/commit-classification) [![](https://img.shields.io/badge/Jupyter-Open_main_notebook-orange?logo=jupyter&style=flat-square)](https://github.com/llazzar/commit-classification/blob/main/scripts/Commit_Classification.ipynb) 
>>
>> **Context** = *University Project*
>> 
>> **Keywords** = `Supervised Learning` `NLP` `Text Preprocessing (Stem, Lem)` `Text Vectorization (n-gram,skip-gram)` `Logistic Regression` `Fasttext by Facebook`
> 
> <img src="https://raw.githubusercontent.com/lorenzolazzari98/commit-classification/main/figures/data_example.jpg" width=310> <img src="https://raw.githubusercontent.com/llazzar/commit-classification/c15d9775b7d5c70bebbe9179780adbebece193de/figures/logit_confusion_matrix.png" width=120 length=120>
> 
> In this project, I aimed to replicate the work done in [this paper](https://raw.githubusercontent.com/llazzar/commit-classification/c15d9775b7d5c70bebbe9179780adbebece193de/reference/paper.pdf). The project started with a 5-class labeled dataset of commit messages, and classical NLP techniques such as data cleaning and feature extraction were used to preprocess the data. Then, several baseline classification models were fitted and evaluated. One of the models was chosen and fine-tuned using RepeatedKFold validation. Finally, the chosen model (a logistic regression) was evaluated on the test set to measure its performance.
> 

