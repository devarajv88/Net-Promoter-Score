
# Net Promoter Score

## Overview
This project focuses on calculating the Net Promoter Score (NPS) of Airbnb, a famous firm working in the  lodging and tourism sector. For this calculation the available dataset in the form of '.csv' format is used. As this data is limited, the whole project just aims to provide a model of how to calculate the NPS.

The NPS is a crucial metric used to measure customer satisfaction and loyalty. This repository contains the dataset, analysis scripts, and results of the NPS calculation.

## Table of Contents
1. [Introduction](#introduction)
2. [Dataset](#dataset)
3. [Methodology](#methodology)
4. [Installation](#installation)
5. [Usage](#usage)
6. [Results](#results)

## Introduction
The Net Promoter Score (NPS) is a widely recognized metric for assessing customer loyalty. It is calculated based on responses to the question: "On a scale of 0 to 10, how likely are you to recommend our company/product/service to a friend or colleague?" Customers are categorized as Promoters (9-10), Passives (7-8), or Detractors (0-6). The NPS is then calculated by subtracting the percentage of Detractors from the percentage of Promoters.

## Dataset
The dataset used in this project is stored in the survey.txt file, which contains a series of numbers from 1 to 10 indicating customer feedback.

- File: survey.txt
- Content: Series of customer feedback ratings (1-10).
The dataset can be found in the data folder of this repository.

## Methodology
The analysis process involves the following steps:
- Categorize the feedback into Promoters, Passives, and Detractors.
- Calculate the percentage of each category.
- Compute the NPS using the formula: NPS = %Promoters - %Detractors.

## Installation
To run the analysis locally, follow these steps:
- Clone the repository:

    git clone https://github.com/devarajv88/Net-Promoter-Score.git

    cd Net-Promoter-Score

- Install the required dependencies:

    pip install -r requirements.txt

## Usage
Run the analysis script to calculate the NPS:

    python src/nps_calculation.ipynb

## Results
The results of the analysis, including the NPS score and visualizations, are documented and the detailed explanation of the findings and insights derived from the data can be found in the nps_calculation.ipynb file.
