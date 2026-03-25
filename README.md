# ✈️ Indian Airline Ticket Price Analysis (EDA Project)
## 📌 Project Overview
------
This project performs Exploratory Data Analysis (EDA) on a dataset of 10,683 Indian domestic flights from 2019. The objective is to understand how different factors such as airline type, number of stops, travel duration, journey date, and additional services influence airline ticket prices.

Through data cleaning, visualization, and analysis, the project uncovers important pricing patterns and travel trends in the Indian aviation market.

## 🎯 Objectives
* Clean and preprocess the airline dataset for accurate analysis.
* Explore how airline type affects ticket prices.
* Analyze the impact of total stops on flight prices.
* Identify the most expensive and cheapest flights.
* Understand travel patterns based on source and destination cities.
* Study how flight duration influences ticket prices.
* Generate business insights from the data.

## 📊 Dataset Information
* Total Records: 10,683 flights
* Year: 2019
* Region: Domestic flights within India
* Format: .xlsx
* File Used:Data_Train_xlsx
## Key Features (Columns)
* Airline
* Date_of_Journey
* Source
* Destination
* Route
* Dep_Time
* Arrival_Time
* Duration
* Total_Stops
* Additional_Info
* Price

## ⚙️ Project Workflow
### Data Loading
* Imported dataset using Pandas
### Data Cleaning
* Handled missing values
* Removed irrelevant information
* Converted date and time columns
* Standardized categorical variables
### Feature Engineering
* Extracted Journey Day and Month
* Converted Duration into numeric format
* Created new useful variables for analysis
###  Exploratory Data Analysis (EDA)
* Analyzed price distributions
* Studied relationships between features
* Compared airline pricing strategies
###  Data Visualization
* Created visual insights using Matplotlib and Seaborn
  
## 📈 Key Business Questions
* Which airline has the highest ticket prices?
* Which airline provides the cheapest flights?
* How does the number of stops affect ticket prices?
* Which routes are most expensive?
* How does flight duration impact pricing?
* Which cities have the highest average airfare?
* Do additional services affect ticket price?

## 🛠️ Technologies Used
* Python
* Pandas – Data Cleaning & Manipulation
* Matplotlib & Seaborn – Data Visualization
* NumPy – Numerical Computation
* Jupyter Notebook


## 🔍 Key Insights
* One-stop flights are the most common travel option.
* Jet Airways Business flights are among the most expensive.
* Budget airlines like SpiceJet and IndiGo dominate lower price segments.
* Flight prices vary significantly depending on journey timing and airline type.
* Flights with more stops generally have longer travel durations.
* Interestingly, some non-stop flights are among the cheapest, challenging the common assumption that direct flights are always expensive.
