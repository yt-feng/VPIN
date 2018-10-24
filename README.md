# Volume Synchronized Probability of Informed Trading
The Volume Synchronized Probability of Informed Trading, commonly known as VPIN, is a mathematical model used in financial markets for multiple purposes.

## Market micro-structure and high frequency trading
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
