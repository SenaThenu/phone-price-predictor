# Phone Price Predictor

This is a fun project I did to sharpen my ML skills. After creating an imaginary problem, I started the whole thing!

## Problem

The Out-of-Limbo Corp has given me a contract to create a price predictor based on different features. So, they can choose which features to add to their latest Into-the-Limbo phone to maximize their profits.

## Data

To make sure my predictor works properly, I'm using a trusty dataset from Kaggle: [Phone Prices](https://www.kaggle.com/datasets/berkayeserr/phone-prices/data)

## Evaluation

Because phone prices vary based on the quality rather just the specs, the success of this model would be defined through r-squared score of 0.6

## Features

**_X_**
- phone_name: name of the phone
- brand: brand of the phone
- os: operating system of the phone
- inches size of the phone screen as inches
- resolution: resolution of the phone screen
- battery: battery capacity of the phone
- battery_type: battery type of the phone
- ram(GB): ram of the phone as GB
- announcement_date: the date of the announcement of the phone
- weight(g): weight of the phone as gram
- storage(GB): storage capacity of the phone as GB
- video_720p: does phone camera has 720p feature
- video_1080p: does phone camera has 1080p feature
- video_4K: does phone camera has 4K feature
- video_8K: does phone camera has 8K feature
- video_30fps: does phone camera has 30fps feature
- video_60fps: does phone camera has 60fps feature
- video_120fps: does phone camera has 120fps feature
- video_240fps: does phone camera has 240fps feature
- video_480fps: does phone camera has 480fps feature
- video_960fps: does phone camera has 960fps feature

**_y_**
- price(USD): price of the phone as USD