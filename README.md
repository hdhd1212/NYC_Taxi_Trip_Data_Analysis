Juel Antonio Teixeira Baptista
October 14, 2026

# NYC Yellow Taxi - Data Analysis

Exploratory analysis of NYC yellow taxi trip data using Python (pandas, matplotlib) in Google Colab
My findings are from the Month of January 2026.

## Question
What panner emerge in NYC taxi trips - When do they happen, where and what drives the fare/tips amounts.

## Data

NYC Yellow Taxi records ~[N] trips for [month/year] and to download taxe zone lookup as well.
  https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page

## Approach

All Analysis is in 'Analysis/NewYorkTaxiAnalysis.ipynb'
1. **Load**         - Read the trip data into pandas dataframe.
2. **Clean**        - Missing values, bevahiour out of pattern, cast types
3. **Explore**      - Trip volume, fare distribution, day, week, hour behaviours.
4. **Visualize**    - Charts with matplotlib.

## Key findings

1. **Busiest hour** 18:00, Quietest hour: 5.00. Busiest weekday: sat.
2. **Weekend share** 28.7% worth of trips.
3. **Top pick up zones** Upper East Size South (4.3% of trips)
4. **Median trip behaviour** 1.9 mi and 14 min.
5. **credit card dominates** 62.4. with Median tip on cards that tipped counting for 27.4 of fare.
6. **Busisest day of the month**. 

## Skill
Python . Pandas . Data cleaning . Exploratory analysis . Matplotlib . Jupyter/Collab

## Running it
 Open notebook in Google Colab:


 loads data from Google Drive.
 1. Download the data from TLC link
 2. Open the notebook and run alll cells



