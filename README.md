# Cleaning and Analyzing Used Car Listings on eBay

In this notebook, I'll work with a dataset of used cars from eBay *Kleinanzeigen*, a classifieds section of the German eBay website. The aim of this notebook is to practice cleaning data and to analyze used car listings.

## Data

The dataset was originally scraped and uploaded to [Kaggle](https://www.kaggle.com/orgesleka/used-cars-database/data). The version of the dataset I am working with is a sample of 50,000 data points that was prepared by [Dataquest](https://www.dataquest.io) including simulating a less-cleaned version of the data.

The data dictionary provided with data is as follows:

- `dateCrawled` - When this ad was first crawled. All field-values are taken from this date.
- `name` - Name of the car.
- `seller` - Whether the seller is private or a dealer.
- `offerType` - The type of listing
- `price` - The price on the ad to sell the car.
- `abtest` - Whether the listing is included in an A/B test.
- `vehicleType` - The vehicle Type.
- `yearOfRegistration` - The year in which which year the car was first registered.
- `gearbox` - The transmission type.
- `powerPS` - The power of the car in PS.
- `model` - The car model name.
- `kilometer` - How many kilometers the car has driven.
- `monthOfRegistration` - The month in which which year the car was first registered.
- `fuelType` - What type of fuel the car uses.
- `brand` - The brand of the car.
- `notRepairedDamage` - If the car has a damage which is not yet repaired.
- `dateCreated` - The date on which the eBay listing was created.
- `nrOfPictures` - The number of pictures in the ad.
- `postalCode` - The postal code for the location of the vehicle.
- `lastSeenOnline` - When the crawler saw this ad last online.
## Shoutout
This notebook is based on a guided project from [Dataquest](https://www.dataquest.io), an online platform to learn Data Analysis and Data Science. The learning goal of the project was to review pandas and cleaning data.  I add a few parts to the guided project that I've picked up on my own including sorting databases. 
