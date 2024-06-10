# Recommendation System in C++
## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Algorithm](#algorithm)
- [Contributers](#contributers)
- [Acknowledgments](#acknowledgments)

## Introduction
In this project, neighborhood-based collaborative filtering (NBCF) algorithms are implemented to predict movie ratings for users. NBCF encompasses two main types of algorithms: user-based (UBCF) and item-based (IBCF). These algorithms analyze user behavior and preferences to provide personalized movie recommendations. The goal is to develop a movie recommendation system that utilizes machine learning techniques to filter and predict users' film preferences based on their past choices.
![cmp](https://github.com/erogluegemen/Movie-Recommendation-System/assets/30879498/3de18fa7-4077-4479-b43e-bf7ef6b97b0e)

## Features
- Collaborative filtering algorithm based on the Manhattan distance similarity metric.
- Predicts user ratings for items based on similar users' ratings.
- Customizable parameters for the number of users, items, and top user count.
- Input data is read from text files, and recommendations are written to a CSV file.

## Requirements
To run the recommendation system, you need:
- C++ compiler
- Development environment or IDE

## Installation
1. Clone the project repository:
   ```bash
   $ git clone https://github.com/erogluegemen/Movie-Recommendation-System.git
   $ cd Movie-Recommendation-System
   ```
2. Open the source code file recommendation_system.cpp in a C++ development environment.
3. Modify the necessary constants in the code according to your data.
4. Build and run the code.

## Usage
1. Prepare your training and testing data files in the required format.
2. Modify the code to provide the correct paths to your data files.
3. Build and run the code.
4. The system will generate a CSV file named submission.csv containing the recommendations.

## Algorithm
The recommendation system uses a collaborative filtering algorithm based on the Manhattan distance similarity metric. <br>
It calculates the similarity between the query user and other users in the dataset based on their rating profiles. <br>
The top similar users are then selected, and their ratings are used to predict the rating for the query user and item. <br>

## Contributers 
If you encounter any problems, do not hesitate to contact. <br>
[@Egemen Eroglu](https://github.com/erogluegemen) <br>
[@Cagatay Tugcu]() <br>

## Acknowledgments
The recommendation system code was developed using C++ and the collaborative filtering algorithm. We would like to thank the contributors for their efforts in creating this system. <br>
If you have any questions or need assistance, please don't hesitate to contact us. <br>
Thank you for using the recommendation system! <br>
