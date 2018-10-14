# Quantified Self (QS) Ledger

## A Personal Data Aggregator and Dashboard for Self-Trackers and Quantified Self Enthusiasts

[Quantfied Self (QS) Ledger](https://github.com/markwk/qs_ledger) aggregates and visualizes your personal data. 

The project has two primary goals: 

1. **download all of your personal data** from various tracking services (see below for list of integration services) and store locally. 
2. provide the starting point for creating a **personal data dashboard** for data analysis, data visualization, and predictive analytics and forecasting using Machine Learning and Artificial Intelligence. 

At present, the main objective is to provide working data downloaders and simple data analysis for each of the integrated services. 

### Code / Dependencies: 

* The code is written in Python 3. 
* Shared and distributed via Jupyter Notebooks. 
* To get started, we recommend downloading and using the [Anaconda Distribution](https://www.anaconda.com/download/#macos).
* For installation, setup and usage of individual services, see documentation provided by each integration.  
* Most services depend on Pandas and NumPy for data manipulation and Matplot and Seaborn for data analysis and visualization. 
* Each project has a NAME_donwloader and NAME_data_analysis.  

### Current Integrations: 

* [Apple Health](https://github.com/markwk/qs_ledger/tree/master/apple_health): fitness and health tracking and data analysis from iPhone or Apple Watch.
* [Fitbit](https://github.com/markwk/qs_ledger/tree/master/fitbit): fitness and health tracking and analysis of Steps, Sleep, and Heart Rate from a Fitbit wearable.
* [GoodReads](https://github.com/markwk/qs_ledger/tree/master/goodreads ): book reading tracking and data analysis for GoodReads.
* [Habitica](https://github.com/markwk/qs_ledger/tree/master/habitica/habitica_downloader.ipynb): habit and task tracking with Habitica's gamified approach to task management.
* [Instapaper](https://github.com/markwk/qs_ledger/tree/master/instapaper/instapaper_downloader.ipynb): articles read and highlighted passages from Instapaper.
* [Kindle Highlights](https://github.com/markwk/qs_ledger/tree/master/kindle/kindle_clippings_parser.ipynb): Parser and Highlight Extract from Kindle clippings. 
* [Last.fm](https://github.com/markwk/qs_ledger/tree/master/last_fm): music tracking and analysis of music listening history from Last.fm.
* [RescueTime](https://github.com/markwk/qs_ledger/tree/master/rescuetime): track computer usage and analysis of computer activities and time with RescueTime. 
* [Pocket](https://github.com/markwk/qs_ledger/tree/master/pocket/pocket_downloader.ipynb): articles read and read count from Pocket. 
* [Strava](https://github.com/markwk/qs_ledger/tree/master/strava): activities downloader (runs, cycling, swimming, etc.) and analysis from Strava. 
* [Todoist](https://github.com/markwk/qs_ledger/tree/master/todoist): task tracking and analysis of todo's and tasks completed history from Todoist app. 
* [Toggl](https://github.com/markwk/qs_ledger/tree/master/toggl): time tracking and analysis of manual timelog entries from Toggl. 

### EXAMPLES: 

* [Combine and Merge Personal Data into Unified Data Frame](https://github.com/markwk/qs_ledger/blob/master/Example_Combined_Personal_Data.ipynb): This example notebook provides a step-by-step walkthrough about how to combine multiple data points into a unified daily CSV of personal metrics. 

#### Creators and Contributors: 

* [Mark Koester](https://github.com/markwk/)

**Want to help?** Fork the project and provide your own data analysis, integration, etc.   

## Questions? Bugs? Feature Requests? Need Support?

Post a ticket in the [QS Ledger Issue Queue](https://github.com/markwk/qs_ledger/issues) 