# Volume Synchronized Probability of Informed Trading
The Volume Synchronized Probability of Informed Trading, commonly known as VPIN, is a mathematical model used in financial markets for multiple purposes.

## Basic Info
* Version - Written in Python 2.7.1
* Keywords
  * VPIN
  * Random control
  * Market micro-structure
   
## Prerequisite
* Numpy as np
* Pandas as pd
* Matplotlib as plt

## Usage
### Dataset
* Data source: wind
* Sampling time range: Jan 2015-Oct 2018
### Correspondence
Please do not hesitate to submit an issue or contact via email.

## Output
* Correlation between VPIN gap versus tick price
* Market volume and sample population

## Landscape
### Introduction
For high frequency trading, market maker need information to make a profit in an informed trading, because reverse selection may cause losses in transactions. The VPIN method intends to measure the probability of market informed transaction; as a predictive sign of the market liquidity risk.

### Methodology
#### Overview
For transactions in the sampling period, the entile volume is divided into 50 baskets. VBS (i.e. Volume of Basket) is defined as total transaction volume in each separate basket.
#### Filling Procedure
* Fill of basket starts when transaction starts
* When volume of transaction exceeds the upper bound, calculate r, which indicates the rest of transaction amount
* Loop of aforementioned process generate a series of baskets.
#### Implications
From a visualized perspective, time series remained stationary. Meanwhile, CSI-300 normally fluctuate dramatically after enlargement of VPIN index.  

## Review of code
### VPIN.ipynb
Please refer to the entire code project via this document, including sample outputs.
### Sample Output

<img src="https://github.com/yt-feng/VPIN/blob/master/dataset/Series.png" width="50%" height="50%">
