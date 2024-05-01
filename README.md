# 🚗 Learn: Guided Project - Revving Up eBay Car Data 🚗

Welcome to our journey of exploring and cleaning a dataset of used cars from eBay Kleinanzeigen, the German eBay classifieds section!

Originally scraped and uploaded to Kaggle by user orgesleka, this dataset offers a thrilling ride into the world of car listings.

[Data Source](https://data.world/data-society/used-cars-data)

## 📊 Data Dictionary

Here's your map through the dataset:

- `dateCrawled`: When the ad was first crawled.
- `name`: Car's name.
- `seller`: Private or dealer.
- `offerType`: Type of listing.
- `price`: Listed selling price.
- `abtest`: Part of an A/B test?
- `vehicleType`: Type of vehicle.
- `yearOfRegistration`: Year the car was registered.
- `gearbox`: Transmission type.
- `powerPS`: Car's power in PS.
- `model`: Car model.
- `odometer`: Kilometers driven.
- `monthOfRegistration`: Month of registration.
- `fuelType`: Fuel used.
- `brand`: Car's brand.
- `notRepairedDamage`: Unrepaired damage?
- `dateCreated`: Date of listing creation.
- `nrOfPictures`: Number of pictures.
- `postalCode`: Vehicle's location postal code.
- `lastSeenOnline`: Last online sighting.

## 🎯 Project Aim

Our goal? Clean the dataset and dive into initial analysis, all while enjoying the unique benefits of JupyterLab.

## 🚀 Let's Get Started!

Time to ignite our engines! Strap in as we import the necessary libraries and load the dataset using pandas:

```python
# Buckle up! We're importing the tools we need
import pandas as pd

# Loading the dataset
# Replace 'file_path' with the path to your dataset file
file_path = 'path_to_your_dataset_file.csv'
data = pd.read_csv(file_path)

# Ready to roll? Let's take a peek at the first few rows
print(data.head())
