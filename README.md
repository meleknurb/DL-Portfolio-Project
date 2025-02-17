# Forest Cover Type Classification

In this project, a multi-class classifier is built using only cartographic variables to predict forest cover types using deep learning. The project aims to predict forest cover types obtained from US Forest Service (USFS) Region 2 Resource Information System data.

---

## Data Set:

Data were derived from raw data from the US Geological Survey and US Forest Service. The data include qualitative variables related to topography and other environmental factors (e.g. soil type, wilderness area). These data are provided in raw form and have not been pre-processed or scaled.

The classes in the data set are:

| **Name**                                 | **Data Type**   | **Measurement**                | **Description**                                                    |
|------------------------------------------|-----------------|--------------------------------|--------------------------------------------------------------------|
| Elevation                                | quantitative    | meters                         | Elevation in meters                                                |
| Aspect                                   | quantitative    | azimuth                        | Aspect in degrees azimuth                                          |
| Slope                                    | quantitative    | degrees                        | Slope in degrees                                                   |
| Horizontal_Distance_To_Hydrology         | quantitative    | meters                         | Horizontal distance to nearest surface water features              |
| Vertical_Distance_To_Hydrology           | quantitative    | meters                         | Vertical distance to nearest surface water features                |
| Horizontal_Distance_To_Roadways          | quantitative    | meters                         | Horizontal distance to nearest roadway                             |
| Hillshade_9am                            | quantitative    | 0 to 255 index                 | Hillshade index at 9am, summer solstice                            |
| Hillshade_Noon                           | quantitative    | 0 to 255 index                 | Hillshade index at noon, summer solstice                           |
| Hillshade_3pm                            | quantitative    | 0 to 255 index                 | Hillshade index at 3pm, summer solstice                            |
| Horizontal_Distance_To_Fire_Points       | quantitative    | meters                         | Horizontal distance to nearest wildfire ignition points            |
| Wilderness_Area (4 binary columns)       | qualitative     | 0 (absence) or 1 (presence)    | Wilderness area designation (binary columns for each area)         |
| Soil_Type (40 binary columns)            | qualitative     | 0 (absence) or 1 (presence)    | Soil type designation (binary columns for each soil type)          |
| Cover_Type (7 types)                     | integer         | 1 to 7                         | Forest cover type designation (1-7 categories)                     |

## Requirements::

The project works with Python 3.7+ and the following libraries:

- pandas
- numpy
- tensorFlow
- keras
- imblearn
- scikit-learn
- matplotlib
- seaborn


