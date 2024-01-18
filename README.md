# UFC Historical Analysis
The UFC (Ultimate Fighting Championship) is a mixed martial arts organization that started in 1993 and has grown into a popular global sport with thousands of athletes.
## Objective
I am not familiar with the UFC, so the goal of the project was to learn more about the sport and see if there are any particular characteristics that contribute to winning. This was done with exploratory visual analysis, linear regression, and k-mean clustering. Other analysis techniques used included geospatial analysis and time-series analysis.<br/>
<br/>
The hypothesis formed during the exploratory analysis was that if a fighter had more rounds, then they would have more matches. These two variables had a high correlation and this remained true during the regression analysis, but less so during the clustering analysis. <br/> 
<br/>
From this I concluded that while there is a correlation, it is not the only factor in winning. There are many factors that can affect a fighter's performance, even those not found in the data. Focusing on wins narrowed the scope of the project, and I later expanded it to highlight individual careers of the talented fighters in the UFC. 
## Data
The dataset is the UFC-Fight Historical Data from 1993-2001 by Rajeev Warrier via [Kaggle](https://www.kaggle.com/datasets/rajeevw/ufcdata/data), accessed on December 26th, 2023. <br/>
<br/>
This data set only has fights from 1994 to March 2021. It includes each match as an individual row, with both fighters' statistics (age at time of fight, current win streak, height, weight, significant strike attempts, etc.) There were multiple versions of the data as well, including a raw version from the scraper.<br/>
<br/>
Geospatial analysis was conducted in Python using the world-countries.json by Kostya via [Kaggle](https://www.kaggle.com/datasets/ktochylin/world-countries). <br/>
<br/>
## Tools
- Python libraries used in this project include:
  * pandas
  * NumPy
  * seaborn
  * matplotlib
  * Folium
  * scikit-learn
- Scripts were created in Jupyter. <br/>
- The final presentation was created in Tableau and can be viewed [here](https://public.tableau.com/views/UFCExplorationProject/UFC?:language=en-US&:display_count=n&:origin=viz_share_link). <br/>
## Folder Structure
01. Project Management: Contains the project brief, a document containing an overview of the CareerFoundry course and project.
02. Data: Contains the original datasets, versions I cleaned, and subsets data used in this project.
03. Scripts: A folder with all of the Jupyter scripts created for analysis and visualizations.
04. Analysis: This contains the visuals created for the project, as well as data sourcing documentation, full correlation matrixes, and the time analysis data preprocessing.
