# Cyclistic Marketing Bike Share Usage Case Study

Eric Chan 2022-03-03

# Case background

This is the capstone project of the Google Data Analytics Professional Certificate.

co info

- maximising annual members is key to future growth
- design marketing strategies aimed at converting casual riders into annual members

https://ride.divvybikes.com/how-it-works

Divvy trip data Mar 2021 to Feb 2022
Data source
https://ride.divvybikes.com/system-data

# 1. Ask

## Business task

- Find how do annual members and casual riders use Cyclistic bikes differently?

## Key stakeholders

- Lily Moreno, Marketing Director
- Cyclistic marketing analytics team
- Cyclistic executive team

# 2. Prepare

## Description of data source used

The specific dataset used is the Divvy historic trip data (licensed by Lyft Bikes and Scooters, LLC).

Reliability -- Second-party data, collected by Chicago Divvy bicycle sharing service. Trip data by staff as they service, inspect the system, or under 60 sec (e.g. false start, re-dock) are removed.

Original -- System data from Lyft Bikes and Scooters, LLC

Comprehensive -- Includes the time and GPS location of every trip.

Current -- Data was collected and release every month.

Cited -- Not cited. No Warranty to be error free.

# 3. Process

- what tool? why?
- check data integrity
- clean and doc -- duplicated, missing values
- verify it's clean
- find ride length HH:MM:SS = ended_at - started_at
- find day of week

# 4. Analyse

- join table

- descriptive analysis
- calc mean of ride_length
- calc max ride_length
- calc mode day_of_week
- calc mean ride_length for members vs casual riders
- calc mean ride_length for users by day_of_week
- calc number of rides for users by day_of_week

- analyse for month, and season

- merge to full year view, analyse
- export summary file

## Summary of Analysis

# 5. Visualise and share

## Support visualisations and key findings
