
# Uplimit Sydney Airbnb Analysis

This repository contains an analysis of Airbnb data for listings in Sydney, Australia. The data includes information on listings, reviews, neighborhoods, and calendar availability.

## Data

Source: https://uplimit.com/course/sql-crash-course/v2/dashboard

The analysis uses data from the following tables:

- `listings`: Contains information on each listing such as id, host, room type, price, etc.
- `reviews`: Contains reviews for each listing, including the reviewer name, date, and comments.
- `neighborhoods`: Information on each neighborhood id and name. 
- `calendar`: Availability calendar for each listing, with dates and prices.

## Notebook

The main analysis is contained in `sydney_airbnb.ipynb`. The notebook explores the data by:

- Printing out all rows from each table to explore the data
- Fetching host ids and names to create a lookup for customer service
- Investigating issues for specific hosts based on reviews, availability, and price
- Comparing availability and pricing between high and low cost neighborhoods
- And more!

## Running the Code

The notebook requires Python and several libraries including Pandas, Sqlcc, and IPython.

To run the notebook:

1. Clone the repo
2. Install requirements (`pip install -r requirements.txt`) 
3. Run `jupyter notebook sydney_airbnb.ipynb`
4. Walk through the cells in order to execute the full analysis

## Extensions

The bonus section includes some suggested extensions for further analysis:

- Finding potential price gouging in the calendar
- Coming up with additional queries and analyses on the data

