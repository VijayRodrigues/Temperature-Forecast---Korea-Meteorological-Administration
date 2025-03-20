# 🌡️ Temperature Forecast Project using ML  

## 📌 Problem Statement  
This project aims to improve **next-day maximum and minimum air temperature forecasts** using machine learning techniques. The dataset originates from the **LDAPS model operated by the Korea Meteorological Administration** over Seoul, South Korea.  

## 📊 Dataset Information  
- **Time Period**: Summer data from **2013 to 2017**  
- **Forecasting Model**: LDAPS (Limited-area Data Assimilation and Prediction System)  
- **Target Variables**:  
  - `Next_Tmax`: Next-day **maximum** air temperature (°C)  
  - `Next_Tmin`: Next-day **minimum** air temperature (°C)  
- **Hindcast Validation**: Conducted from **2015 to 2017**  

## 🔢 Attribute Information  
| Feature | Description | Range |
|---------|------------|--------|
| `station` | Weather station number | 1 to 25 |
| `Date` | Present-day date | 2013-06-30 to 2017-08-30 |
| `Present_Tmax` | Present-day max air temperature (°C) | 20 to 37.6 |
| `Present_Tmin` | Present-day min air temperature (°C) | 11.3 to 29.9 |
| `LDAPS_RHmin` | LDAPS forecast of next-day min relative humidity (%) | 19.8 to 98.5 |
| `LDAPS_RHmax` | LDAPS forecast of next-day max relative humidity (%) | 58.9 to 100 |
| `LDAPS_Tmax_lapse` | LDAPS forecast of next-day max temp applied lapse rate (°C) | 17.6 to 38.5 |
| `LDAPS_Tmin_lapse` | LDAPS forecast of next-day min temp applied lapse rate (°C) | 14.3 to 29.6 |
| `LDAPS_WS` | LDAPS forecast of next-day avg wind speed (m/s) | 2.9 to 21.9 |
| `LDAPS_LH` | LDAPS forecast of next-day avg latent heat flux (W/m²) | -13.6 to 213.4 |
| `LDAPS_CC1-CC4` | LDAPS forecast of next-day cloud cover for 6-hour splits (%) | 0 to 0.98 |
| `LDAPS_PPT1-PPT4` | LDAPS forecast of next-day precipitation for 6-hour splits (%) | 0 to 23.7 |
| `lat` | Latitude (°) | 37.456 to 37.645 |
| `lon` | Longitude (°) | 126.826 to 127.135 |
| `DEM` | Elevation (m) | 12.4 to 212.3 |
| `Slope` | Slope (°) | 0.1 to 5.2 |
| `Solar radiation` | Daily incoming solar radiation (Wh/m²) | 4329.5 to 5992.9 |
| `Next_Tmax` | Next-day maximum air temperature (°C) | 17.4 to 38.9 |
| `Next_Tmin` | Next-day minimum air temperature (°C) | 11.3 to 29.8 |

## 📂 Dataset Download  
🔗 **[Download the dataset](https://github.com/dsrscientist/Dataset2/blob/main/temperature.csv)**  

---

