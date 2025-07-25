# Bank-Marketing-EDA

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Dataset Description](#dataset-description)
- [Requirement](#requirement)
- [Installation](#installation)
- [License](#license)

## Introduction
This project aims to perform Exploratory Data Analysis (EDA) on the Banking Dataset for Marketing Targets from Kaggle. The goal is to uncover patterns, identify significant variables, and provide insights that can help in developing targeted marketing strategies.

## Dataset
The dataset can be found [here](https://www.kaggle.com/datasets/prakharrathi25/banking-dataset-marketing-targets). It includes various attributes related to customers' banking details and the marketing campaigns they were subjected to.

## Dataset Description
The dataset contains the following columns:

* age: Age of the customer
* job: Job type of the customer
* marital: Marital status of the customer
* education: Education level of the customer
* default: Indicates if the customer has credit in default (binary: "yes","no")
* balance: Account balance
* housing: Indicates if the customer has a housing loan (binary: "yes","no")
* loan: Indicates if the customer has a personal loan (binary: "yes","no")
* contact: Contact communication type
* day: Last contact day of the month
* month: Last contact month of the year
* duration: Last contact duration, in seconds
* campaign: Number of contacts performed during this campaign and for this client
* pdays: Number of days that passed by after the client was last contacted from a previous campaign
* previous: Number of contacts performed before this campaign and for this client
* poutcome: Outcome of the previous marketing campaign
* y: Has the client subscribed a term deposit? (binary: "yes","no")

## Requirements
To run the EDA, you need the following libraries installed:
```
pandas
numpy
matplotlib
seaborn
```

## Installation
To run this project locally, follow these steps:
1. Clone the repository:
```bash
git clone https://github.com/yourusername/customer-segmentation.git
```
2. Navigate to the project directory:
```bash
cd customer-segmentation
```
3. Create a virtual environment:
```bash
python3 -m venv venv
```
4. Activate the virtual environment:
On Windows:
``` bash
venv\Scripts\activate
```
On MacOS/Linux:
```bash
source venv/bin/activate
```
5. Install the dependencies:
``` bash
pip install -r requirements.txt
```

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
