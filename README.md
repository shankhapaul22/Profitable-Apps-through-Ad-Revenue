# Context

As of September 2018, there were approximately 2 million iOS apps available on the App Store, and 2.1 million Android apps on Google Play Store.  

Instead of collecting data from over 4 million apps, we will be using a sample of the data.

- A data set, `AppleStore.csv`, containing data about approximately 7,000 iOS apps from the App Store; the data was collected in July 2017.
- A data set, `googleplaystore.csv`, containing data about approximately 10,000 Android apps from Google Play; the data was collected in August 2018.

# Objective

The purpose of this project is to identify profitable apps for an app development company. The company builds apps that are free to download and focuses on in app purchases as their main source of revenue.

We will be observing apps in the Apple Store and Google Play Store. We will analyze the data sets to identify types of apps that attract a large user base for potential profitable margins. This is will give the app development company insights for their next app ideas.

# Process

The following steps outline the analysis:

- We explore the data and analyze the column names for additional info.
- We clean the data by:
  - removing unnecessary characters.
  - removing duplicate rows.
  - removing non English apps.
- We isolate the free apps on both data sets.
- We conduct our data analysis by observing the most common genres.
- Then, we analyze the most popular genres by total installs per genre.
- Lastly, we categorzied the top apps in the most popular genres to check for market dominance by other apps.

# Results

From our analysis, `Books & Reference` seems to be the best genre to enter as a free app for English audience given the market.
We decided not to enter the `Games` genre as it seems oversaturated.
The app in the `Books & Reference` genre can include gameification such as users earn points/achievements as they read and interact on the app to make it more fun.
