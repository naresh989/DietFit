# Diet Fit App

This is a Fast-API powered web application which designed to help users calculate their BMI and estimate their average calorie intake, using their personal information as input. This application will also provide tailored diet and fitness plans for users for a week.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)

## Prerequisites

To run this application, you need to have the following software installed on your system:

- python3
- pip3 (Python package manager)

## Installation (Creating python virtual environment)
1. change the directory to `~/5130f2023/diet-fit`
```
cd ~/5130f2023/diet-fit
```
2. create a virtual env( this is done only once)
```
python3 -m venv venv
```
3. activate the virtual env
```
source venv/bin/activate
```
4. install the dependencies
```
pip3 install -r requirements.txt
```


## Usage 
1. change the directory to `~/5130f2023/diet-fit`
```
cd ~/5130f2023/diet-fit
```
2. activate the virtual env
```
source venv/bin/activate
```
3. start the flask server
```
python3 app.py
```

3. To access the application, open the below url in the browser 
```
http://localhost:8000/
```