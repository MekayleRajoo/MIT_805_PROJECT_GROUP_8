# Dataset

**NYC Yellow Taxi Trip Records** - trip-level records of New York City Yellow Taxi rides

## Source
Published by the New York City Taxi and Limousine Commission (TLC), available via https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page

## Dataset Sizes
- **Raw**: The full public dataset (2009–present) exceeds 50 GB
- **Working**: 12 GB 
- **Processing**: 4 GB (after cleaning and taking a 20% random sample for computational feasibility)

## Format & Structure
Data is released as one Parquet file per month. Each row represents a single taxi trip. Raw files include fields such as VendorID, tpep_pickup_datetime, tpep_dropoff_datetime, passenger_count, trip_distance, RatecodeID, store_and_fwd_flag, PULocationID, DOLocationID, payment_type, fare_amount, extra, mta_tax, tip_amount, tolls_amount, improvement_surcharge, total_amount, congestion_surcharge, airport_fee, and cbd_congestion_fee. Two derived variables - trip_duration (hours) and average_trip_speed (mph) - were engineered during cleaning. Raw files were downloaded separately due to size and are not committed to this repository.

## Collection Period
Data collection began in 2009 and continues to the present, with monthly files published on a rolling basis with a 2 month delay. This project analyses the subset from 2014–2026.

## License / Terms of Use
Data is published as open government data by the NYC TLC. The TLC makes no representations as to the accuracy of the data, and no personal/individual identifiers are included, making it suitable for academic use.

## Processing Data
Due to the size limit of file sizes on Github we have uploaded our files to Google Drive which you can find here: https://drive.google.com/drive/folders/1mpjButE14UIQPJA-h8JlGZGFfXd2Xz1a?usp=drive_link
