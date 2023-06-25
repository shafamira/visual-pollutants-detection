# Visual Pollutant Detection in Urban Environments
This repository contains the code and report for the project "Visual Pollutant Detection in Urban Environments". The project aims to detect various visual pollutants in urban areas, specifically in KSA (Kingdom of Saudi Arabia). The dataset used for this project is obtained from https://www.kaggle.com/datasets/abhranta/urban-visual-pollution-dataset.

## Dataset
The dataset consists of labeled images representing different types of visual pollutants in the urban environment. Some of the categories include:
- GRAFFITI
- FADED SIGNAGE
- POTHOLES
- GARBAGE
- CONSTRUCTION ROAD
- BROKEN_SIGNAGE
- BAD STREETLIGHT
- BAD BILLBOARD
- SAND ON ROAD
- CLUTTER_SIDEWALK
- UNKEPT_FACADE
The dataset includes two files (```train.csv``` and ```test.csv```) and one folder (```images```). The ```train.csv``` file contains information such as class, image_path, name, xmax, xmin, ymax, and ymin. On the other hand, the ```test.csv``` file only contains image_path, as it is originally designed for competition purposes.

## Files
**Report.pdf:** This file contains a comprehensive report detailing the project, including the methodology, experimental setup, results, and analysis.
**Code.ipynb:** This Jupyter Notebook file contains the code implementation for the project. It includes object recognition using YOLOv5n and image classification using VGG16, MobileNet, and DenseNet121 models.

If you have any questions or suggestions, please feel free to reach out. Happy exploring!
