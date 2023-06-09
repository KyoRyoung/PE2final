# PE2_C
**Programming for Engineer Ⅱ**   


## Overview
This software is programed to analyze measured data of semiconductor wafers.
* * *

## Contents
1. [Development time](#Development-time)   
2. [Info](#Info)
3. [Collaborators](#Collaborators)
4. [Project](#Project)
5. [Instructions](#Instructions)
6. [Requirements](#Requirements)
* * *

## Development time
2023.03.01-
* * *

## Info
- `python 3.9`
- `Windows 11`
* * *

## Collaborators
- 2019030455 고주환   
- 2019052415 윤석현   
- 2019080973 이동현   
- 2020027192 김교령
* * *

## Project
- dat: a folder contains XML data
- doc: a folder contains documentation- Jupyter notebook file describing data analysis results and powerpoint file for presentation
- res: a folder contains result figures and csv files
- src: a folder contains codes of the software
- .gitignore: : data is confidential so it should not be uploaded and published
- README.md: brief introduction of this software repository
- run.py: execution python file of this software   

![image](https://user-images.githubusercontent.com/127359402/236680428-3d8cf99c-d164-4a9d-a818-274bbd423bff.png)

* * *

## Instructions
1. Run run.py
2. Select the desired device type (ex. `LMZC`, `LMZO`, `LMZ`)
3. Enter the desired wafer number in the form "D##" (ex. `D07`, `D08`, `D23`, `D24`, `all`)
4. Enter Wafer's coordinates in the form of "#,#" (ex. `0,0`)
5. Enter y/n whether to see the data as png file or not
6. Enter y/n whether to save the data as png file or not
* * *

## Requirements
- NumPy
- xml.etree.ElementTree
- matplotlib
- scikit-learn
- pandas
- lmfit
- tqdm
- glob

To install all requirements, use the following command.   
```
pip install -r requirements.txt
```
