# Improving Food Security through Crop Yield Prediction

Droughts and climate change threaten crop production which in turn impact food availability and price.

Knowing in advance what food the import and export helps
  * maintain food security
  * planning, storage for farmers
  * prevent famine
  
## Methods

![alt text](https://github.com/multiyumz/FoodSecurityForecaster/blob/toms-branch/method_img.png)

The aim of this project was to
  * Predict future crop yeild from past satellite date provide by Google Earth Engine
  * Apply deep learning models (specifically CNN and LTSM) combined with ground truth data
  * Use model outputs to predict future months crop yeild in the USA and India

## Models

* ### Convolution Neural Networks (CNNs)
![alt text](https://github.com/multiyumz/FoodSecurityForecaster/blob/toms-branch/cnn.png)

#### Automatically learn useful features from satellite images

* ### Long-Short Term Memory (LSTM) Network
#### Learn temporal patterns & sequences from monthly NDVI maps

## Data

* Satellite data for Vegetation Index (NDVI)
  - periodic past maps (X) of different wavelengths of the electromagnetic spectrum
  
* Annual crop yeild
  - Options to choose the average crop yeild of the USA and India or state at a more granular level
  - Line of best fit can be used in the app to predict crop yeild in future years
  
## Final Product

* Real-time forecast of crop yeild
* Create interactive map - user can select the year and country with the option to view the average crop yeild prediction or state level
* A tool that is able to tell if there will be food shortages
* Ultimately be able to tell what food to import/export in order to maintain food security and prevent famine


## Hosted URL can be found at:
http://tinyurl.com/5n6esnku
