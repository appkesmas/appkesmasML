# appkesmasML

This is a repository for machine learning part of the Appkesmas application. 
There are two parts of this repository:
- Patient Waiting Time Prediction (with Machine Learning)
- Hospital Ranking Recommendation (no Machine Learning, just use some data exploration libraries to prepare data to be served on API)

It also contains the datasets used in this project:
- 2017 National Hospital Ambulatory Medical Care Survey Data Files [https://ftp.cdc.gov/pub/Health_Statistics/NCHS/Datasets/NHAMCS/](https://ftp.cdc.gov/pub/Health_Statistics/NCHS/Datasets/NHAMCS/)
- Data Info Puskesmas (Puskesmas Information Data) [https://data.jakarta.go.id/dataset/daftarpuskesmasjakarta](https://data.jakarta.go.id/dataset/daftarpuskesmasjakarta)
- Informasi Ketersediaan Bed Rumah Sakit Provinsi DKI Jakarta (DKI Jakarta’s Hospital Bedroom Availability Information) [http://eis.dinkes.jakarta.go.id/eis/](http://eis.dinkes.jakarta.go.id/eis/)
- Sistem Informasi Rumah Sakit Kemenkes (Hospital Information System by Ministry of Health) [http://sirs.yankes.kemkes.go.id/fo/home](http://sirs.yankes.kemkes.go.id/fo/home)

## Required Tools and Libraries

- python
- pandas
- numpy
- matplotlib
- sklearn
- tensorflow
- requests
- json
- geopy


## How to use

- Clone/Fork the repository and save it locally to your computer.
- Install Python and the required libraries.
- Use it according to the part you want to do.
  + Patient Waiting Time Prediction:
    1. Open 'Capstone_Project__Waiting_time_v2.ipynb', and run each cell. 
    2. It will result in a TensorFlow .h5 model that can be found in 'myModel.h5'.
  + Hospital Recommendation:
    1. Open 'hospital_ranking' folder.
    2. Notice there are two CSV files. The 'rs_dki.csv' contains raw data from Ministry of Health regarding data of hospitals in DKI Jakarta, and the 'rs_dki_cleaned.csv' is the result of the raw data that has already been cleaned.
    3. You can find the cleaning part in the 'hospital_data_cleaning.ipynb' and run through the cells. Meanwhile if you are interested in the hospital ranking recommendation, you can check 'hospital_ranking.ipynb'.
