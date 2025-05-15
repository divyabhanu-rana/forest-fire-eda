# 📁 `data/` Folder README

This folder contains the dataset used for the **Exploratory Data Analysis (EDA) of Forest Fires in Portugal**.

---

## 📄 Dataset Description

**Dataset Name:** Forest Fires Data Set  
**Source:** UCI Machine Learning Repository  
**URL:** [https://archive.ics.uci.edu/ml/datasets/forest+fires](https://archive.ics.uci.edu/ml/datasets/forest+fires)  
**Format:** CSV (`forestfires.csv`)  
**Instances:** 517  
**Features:** 13

This dataset captures meteorological and fire-related attributes in the Montesinho natural park of Portugal. The main goal is to understand the environmental and human factors that influence the **severity and frequency** of forest fires.

---

## 🧾 Features in the Dataset

| Column     | Description                                           |
|------------|-------------------------------------------------------|
| X, Y       | Spatial coordinates within the Montesinho park grid   |
| month      | Month of the year (`jan` to `dec`)                   |
| day        | Day of the week (`mon` to `sun`)                     |
| FFMC       | Fine Fuel Moisture Code (fire risk index)             |
| DMC        | Duff Moisture Code (index related to fuel availability) |
| DC         | Drought Code (long-term drought effects)              |
| ISI        | Initial Spread Index (rate of fire spread)            |
| temp       | Temperature in Celsius                                |
| RH         | Relative Humidity (%)                                 |
| wind       | Wind speed in km/h                                    |
| rain       | Rainfall in mm                                        |
| area       | Burned area of the forest (in ha)                     |

---

## 📥 How to Obtain the Dataset

You can download the dataset manually from the [UCI Forest Fires Dataset Page](https://archive.ics.uci.edu/ml/datasets/forest+fires).

Alternatively, download directly:
- [forestfires.csv (direct link)](https://archive.ics.uci.edu/ml/machine-learning-databases/forest-fires/forestfires.csv)

Place the downloaded file into this `data/` folder for analysis.

---

## ⚠️ Licensing & Use

The dataset is made freely available for academic and research purposes. Please credit the UCI Machine Learning Repository when sharing insights or publishing work derived from this dataset.
