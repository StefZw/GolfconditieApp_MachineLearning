# GolfconditieApp Machine Learning

## Prerequisites

Ensure you have the following software installed on your device:

- Java 17.0.12
- Hadoop 3.4.0 (with winutils from the same version on [winutils repository](https://github.com/kontext-tech/winutils/tree/master/hadoop-3.4.0-win10-x64))
- Spark 3.5.4
- Python 3.8
- Pyspark 3.5.4

## Installation

Install all required Python packages using the following command in bash:
```bash
pip install -r requirements.txt
```

## Data Extraction

First, extract the data by running the notebook `Scripts/extractMultipleMeasurements.ipynb`. In this notebook, you can change the start and end dates for the data extraction.

## Machine Learning

After extracting the data, run the notebook `Scripts/machineLearning.ipynb` to perform the machine learning tasks.