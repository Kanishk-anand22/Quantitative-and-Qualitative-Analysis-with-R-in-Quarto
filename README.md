# Quantitative-and-Qualitative-Analysis-with-R-in-Quarto
This project leverages R programming within Quarto to perform both quantitative and qualitative analyses. Utilizing packages such as dplyr, ggplot2 and plotly, the project focuses on data manipulation, visualization, and geographical analysis. Interactive visualizations and data flow diagrams are created using Mermaid in Quarto.

## Objectives
The primary objectives of this project are:
1. To preprocess and clean multiple datasets.
2. To visualize data interactively and geographically for better insights.
3. To perform thematic and sentiment analysis.
4. To enhance insights with data flow diagrams using Mermaid.

## Key Features
Data Collection and Preprocessing
1. Library Import and Setup: Utilized dplyr, lubridate, magrittr, tidyverse, tidytext, textdata, ggplot2, shiny, and plotly for data manipulation and visualization.
2. Working Directory: Set the working directory to read CSV files for analysis.

## Mermaid Code for Data Flow
Data Flow Diagrams: Used Mermaid to create diagrams illustrating the steps of data transformation from initial data frames to the final joined dataset.

## Data Loading and Preprocessing
1. Data Loading: Imported multiple datasets using read.csv.
2. Data Cleaning: Renamed and selected specific columns from each dataset.
3. Data Merging: Joined the cleaned datasets into a final comprehensive dataset.

## Exploratory Data Analysis
1. Summary Statistics: Provided summary statistics of the final dataset.
2. Visualization: Created static and interactive plots using ggplot2 and plotly to explore data distributions and relationships.

## Sentiment Analysis
1. Sentiment Analysis Setup: Loaded sentiment lexicons from the tidytext package.
2. Tokenization: Tokenized the text data and performed sentiment analysis.
3. Sentiment Scoring: Calculated sentiment scores and visualized the results using ggplot2.

## Technology Stack
1. Programming Language: R
2. Data Manipulation: dplyr, tidyverse
3. Text Analysis: tidytext, textdata
4. Visualization: ggplot2, plotly, leaflet
5. Interactive Reports: Quarto, Mermaid
