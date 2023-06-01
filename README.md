# Predicting Customer Buying Behavior - British Airways

## Task 1: Analysis of British Airways Customer Reviews

This section aims to collect and analyze customer reviews of British Airways from the website airlinequality.com. The objective is to extract information about customer sentiments and commonly discussed topics in their reviews.

### Step 1: Comment Collection via Web Scraping

Step 1 focuses on collecting customer comments from the British Airways website. Web scraping is used to extract comments from various pages of the website, utilizing popular libraries such as Beautiful Soup and Scrapy.

#### Instructions

1. Ensure that Python is installed on your machine.
2. Clone this GitHub repository to your local machine.
3. Install the required dependencies by running the following command: `pip install -r requirements.txt`
4. Execute the web scraping script to collect customer comments : This will initiate the web scraping process and save the comments into a database (CSV file).

#### Results

After completing Task 1, you will have a database containing customer comments of British Airways. These comments will serve as the foundation for the subsequent steps of sentiment analysis and topic analysis.

## Disclaimer

This project is for educational purposes only. Please adhere to the website's policies and terms of use when performing web scraping.

## Task 2: Flight Booking Prediction

This section aims to develop a prediction model for customer flight bookings of British Airways. The provided data includes information such as flight route, flight day, travel type, sales channel, and booking origin.

### Step 1: Data Exploration

In Step 1, we explore the data to understand its structure and characteristics. We utilize the Pandas library to load the data from a CSV file and display the initial rows of the DataFrame. Then, we use Pandas methods to obtain information about the columns, such as data types and descriptive statistics.

### Step 2: Building a Database

Step 2 involves building a database from the British Airways customer booking data. We use the Pandas library to load the data from the CSV file. Next, we utilize the scikit-learn library to perform data engineering steps, such as encoding categorical variables into numerical values using the `LabelEncoder` class. Then, we split the data into independent variables and the target variable, and use a RandomForest classifier to train our prediction model.

### Installation and Execution

1. Clone this repository to your local machine.
2. Ensure that Python 3 is installed.
3. Install the required dependencies by running the following command: `pip install -r requirements.txt`
4. Place the CSV file containing the booking data with the name `customer_booking.csv` in the project directory.
5. Run the `Prediction_model.ipynb` file to build the database and train the prediction model.

Feel free to customize these instructions based on your project and specific requirements.