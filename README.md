# NearBite-KSA-Restaurant-and-Cafe
This repository contains code for exploring and cleaning a dataset of restaurants and cafes in Saudi Arabia. The dataset was collected from Google Maps and includes information about ( 5000 rows ) such as the name, type, location, and working hours of each establishment. <br> <br>

- pandas <br>
- numpy <br>
- seaborn <br>
- matplotlib <br><br>

You can install these libraries using pip: <br>

pip install pandas numpy seaborn matplotlib <br><br>

## Data <br><br>

The dataset is divided into several CSV files, each containing information for a particular region of Saudi Arabia. The files are: <br>

- `Riyadh2.csv` <br>
- `Al-Madina.csv` <br>
- `Makkah_Jeddah_Taif.csv` <br>
- `dammam_khobar_dhahran.csv` <br>
- `Jeddah.csv` <br>
- `Makkah_Jeddah_Taif.csv` <br><br>

The columns of the dataset are: <br>

- `name`: The name of the restaurant or establishment, as listed on Google Maps. <br>
- `type`: The general category or type of the restaurant or establishment. <br>
- `phone`: The phone number of the restaurant or establishment. <br>
- `full_address`: The full address of the restaurant or establishment. <br>
- `street`: The street address of the restaurant or establishment. <br>
- `city`: The city or locality in which the restaurant or establishment is located. <br>
- `latitude`: The latitude coordinate of the restaurant or establishment. <br>
- `longitude`: The longitude coordinate of the restaurant or establishment. <br>
- `rating`: The overall rating of the restaurant or establishment on Google Maps, as a decimal value out of 5. <br>
- `working_hours`: The hours of operation for the restaurant or establishment, listed as a dictionary object with keys representing each day of the week and values representing the hours of operation on that day. <br>
- `business_status`: The current operational status of the restaurant or establishment, as listed on Google Maps. <br>
- `logo`: A URL linking to the restaurant or establishment's logo, as listed on Google Maps. <br>
- `verified`: A boolean value indicating whether the restaurant or establishment has been verified by Google. <br>
- `location_link`: A URL linking to the Google Maps page for the restaurant or establishment. <br><br>

## Exploratory Data Analysis <br><br>

The code in this repository includes exploratory data analysis (EDA) of the dataset. The EDA includes: <br>

- Merging all dataframes into one <br>
- Removing unnecessary columns <br>
- Cleaning missing data <br>
- Mapping city and establishment types to standardized names <br>
- Converting English day names in `working_hours` column to Arabic <br>
- Creating a new feature, `total_reviews`, based on the `reviews_per_score` column <br><br>

Please note that the `total_reviews` feature is not present in the original dataset, and was created as part of the EDA.

# __________________________________________

# Saudi Arabia Restaurant and Cafe Dataset Telegram Chatbot <br><br>

This repository contains code for a Telegram chatbot that allows users to search for restaurants and cafes in Saudi Arabia. The chatbot is built using the `python-telegram-bot` library and uses the dataset in this repository to retrieve information on establishments. <br><br>

https://github.com/Mariyyahes/NearBite-KSA-Restaurant-and-Cafe/assets/53354457/74ba223b-5caf-40ee-9053-b5c7d14d7aaa
