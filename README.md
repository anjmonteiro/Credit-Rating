# AI for fixed income

Building AI course project.

## Summary

This project uses AI methods to find suitable bonds for fixed income investors based on their current holdings. 


## Background

The Nordic corporate bond market is illiquid and opaque which creates challenges for both buy and sell side market participants. This project explores different AI methods as a  way to better match buyers and sellers.  

Specifically we're exploring models that
* Predict which bonds an investor is likely to buy based on parameters of its current holdings
* Identify cheap and expensive bonds based on sets of fundamental variables


## How is it used?

The models will run as an app on Bloomberg's BQNT platform. The user will choose what fund or portfolio to analyze and certain parameters.


## Data sources and AI methods

The project runs on Bloomberg's BQNT platform and uses Bloomberg's data. It can only be used with a Bloomberg Professional licence. Sharing of any data is limited by Bloomberg's licence terms. 

## Challenges

Although Bloomberg can be considered the best data source for bonds, the quality of the data is the single most important challenge. Many data items are missing or incorrect and all these challenges must be handled in some way.  

## What next?

The project could eventually include different, complementing data sources. Company fundamentals would in an ideal world be forward looking analyst estimates but at this stage historical data is used. 


## Acknowledgments

* The introductions of Bloomberg's BQNT platform makes projects like this possible. BQNT combines Bloomberg's data and functions with the versatility of Python.   

