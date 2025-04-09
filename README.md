# Traffic-counts-dataset

This repository includes a derived dataset based on open data from the City of Calgary. The dataset includes **car**, **bicycle**, and **pedestrian** counts, recorded every 15 minutes at various intersections throughout the city.

## 📊 Dataset Overview

- **Location:** Calgary, Alberta, Canada  
- **Frequency:** 15-minute intervals  
- **User Types:**  
  - Vehicles (Cars)  
  - Cyclists  
  - Pedestrians  
- **Spatial Coverage:** Multiple intersections  
- **Time Coverage:** 2020


## 🛠️ Data Processing

The final dataset includes the following transformations:
- Merging of vehicle, pedestrian, and bikes traffic datasets.
- Resampling and aligning to consistent 15-minute intervals.
- Addition of geolocation data (latitude and longitude) per intersection.

## 📜 License 

The traffic data included in this repository is derived from the following publicly available datasets provided by the City of Calgary:

1. [Traffic Volume - Vehicles](https://data.calgary.ca/Transportation-Transit/Traffic-Counts-at-Permanent-stations/vuyp-sbjp/about_data)  
2. [Traffic Volume - Pedestrians and Cyclists](https://data.calgary.ca/Transportation-Transit/Bike-and-Pedestrian-Counts/pede-tz7g/about_data)

These datasets are made available under the [Open Government Licence – City of Calgary](https://data.calgary.ca/stories/s/Open-Calgary-Terms-of-Use/u45n-7awa).

> **Attribution:**  
> Contains information licensed under the Open Government Licence – City of Calgary.

The merged and processed dataset retains the same license. You may copy, modify, and use the dataset for any lawful purpose with appropriate attribution.

## 🙏 Acknowledgment

If you use this dataset in your research or publication, I would be grateful if you could mention this repository and acknowledge the City of Calgary as the data provider.

---

For any questions or contributions, feel free to open an issue or contact Rania Farjallah at [rania.farjallah.eng@gmail.com].
