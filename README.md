# Credit ratings using AI

Building AI course project.

## Summary

This project uses AI methods to assign a credit rating to bond issuers not rated by rating agencies.  


## Background

Most companies issuing bonds in the Nordic corporate bond market are not rated by any of the international rating agencies. It is, however, of interest to many market participants to have an objective measure of credit risk also for these companies. Assigning a credit rating is a complex task and this project only focuses on the numerical part of it. Specifically certain key ratios of non-rated companies are compared to those of rated companies in order to derive an implied credit rating.     


## How is it used?

The models will run as an app on Bloomberg's BQNT platform. The user will choose a company to analyze and the model will return an implied credit rating based on ceratin assumptions.


## Data sources and AI methods

The project runs on Bloomberg's BQNT platform and uses Bloomberg's data. It can only be used with a Bloomberg Professional licence. Sharing of any data is limited by Bloomberg's licence agreement. This app will not be used for any commercial purposes as it is solely a project for the Building AI course.  

## Challenges

Although Bloomberg can be considered the best data source for financial data, the quality of the data is the single biggest challenge. Many data items are missing or incorrect and could lead to poor results. 

## What next?

Assigning a credit rating is a complex task and this project only makes comparisons of numerical key ratios for different companies. The model could be developed to include also qualitative parameters and forward looking estimates instead of historical data but that is currently out of scope for this project.

## Acknowledgments

* The introduction of Bloomberg's BQNT platform makes projects like this possible. BQNT combines Bloomberg's data and functions with the versatility of Python.   

