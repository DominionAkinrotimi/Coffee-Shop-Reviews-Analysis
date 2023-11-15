# Coffee-Shop-Reviews-Analysis
## Java June Coffee Shops Analysis

Java June is a coffee shop company with locations across Europe. This project aims to provide insights into factors influencing the number of reviews for their stores and explores the relationship between reviews and ratings.

## Task 1: Data Cleaning

Before analysis, the dataset in "coffee.csv" underwent cleaning to ensure a standardized format. The cleaned dataset, named `clean_data`, adheres to the following criteria:

### Cleaned Columns and Criteria:

- **Region:**
  - Nominal.
  - Where the store is located, one of 10 possible regions (A to J).
  - Missing values replaced with "Unknown."

- **Place Name:**
  - Nominal.
  - The name of the store.
  - Missing values replaced with "Unknown."

- **Place Type:**
  - Nominal.
  - The type of coffee shop, one of "Coffee shop," "Cafe," "Espresso bar," and "Others."
  - Missing values replaced with "Unknown."

- **Rating:**
  - Ordinal.
  - Average rating of the store from reviews on a 5-point scale.
  - Missing values replaced with 0.

- **Reviews:**
  - Nominal.
  - The number of reviews given to the store.
  - Missing values replaced with the overall median number.

- **Price:**
  - Ordinal.
  - The price range of products in the store, one of '\$', '\$\$', or '\$\$\$'.
  - Missing values replaced with "Unknown."

- **Delivery Option:**
  - Nominal.
  - If delivery is available, either True or False.
  - Missing values replaced with False.

- **Dine-in Option:**
  - Nominal.
  - If dine-in is available, either True or False.
  - Missing values replaced with False.

- **Takeaway Option:**
  - Nominal.
  - If take away is available, either True or False.
  - Missing values replaced with False.

### Usage:
1. Load the data from "coffee.csv."
2. Utilize the `clean_data` dataframe for further analysis.
   

## Task 2: Reviews by Rating

The team at Java June hypothesizes that the number of reviews changes depending on the rating. The table `reviews_by_rating` provides insights into this hypothesis, showcasing the difference in the median number of reviews by rating, along with the minimum and maximum number of reviews.

### Output Columns:

- **Rating:**
  - The rating from the reviews.

- **Med_Review:**
  - Median number of reviews, rounded to 1 decimal place.

- **Min_Review:**
  - Minimum number of reviews, rounded to 1 decimal place.

- **Max_Review:**
  - Maximum number of reviews, rounded to 1 decimal place.

### Usage:
1. Load the data from "coffee.csv."
2. Utilize the `reviews_by_rating` dataframe to explore the relationship between reviews and ratings.
