
# Aviation Safety Analysis
![](https://images.theconversation.com/files/472287/original/file-20220704-13-iyr4cr.jpeg?ixlib=rb-1.1.0&rect=38%2C0%2C4086%2C2040&q=45&auto=format&w=668&h=324&fit=crop)
**Authors:** Bobby Gerberick, Claire Sarraille, and Ben Gilbert

## Overview

This project analyzes aircraft data in order to construct recommendations for a business that needs insights on the safety of airplanes. Descriptive analysis of the safety of different aircrafts shows that (insert our 3 findings here). The business can use this analysis to set guidelines for their new endeavor into the aviation industry.

## Business Problem
![](https://gray-wwsb-prod.cdn.arcpublishing.com/resizer/PLAR0OJXJ6Z0qxbtQcXkj_TsLBo=/1200x675/smart/filters:quality(85)/cloudfront-us-east-1.images.arcpublishing.com/gray/HDOIMOAREJELRLVVMTTMBOO664.jpg)
A company is expanding in to new industries to diversify its portfolio. Specifically, they are interested in purchasing and operating airplanes for commercial and private enterprises, but do not know anything about the potential risks of aircraft. The company needs help determining which aircrafts are the lowest risk to start their new business endeavor.

## The Data

The [dataset](https://www.kaggle.com/datasets/khsamaha/aviation-accident-database-synopses) used for this analysis was downloaded from Kaggle. It is from the National Transportation Safety Board and includes data from 1962 to 2023 about civil aviation accidents and selected incidents in the United States and international waters.

## Methods



## Results
- Our recommendations stem from slicing the `Purpose.of.flight` column by cleaned `Make` and `Model` columns. 

### We recommend investing in aircraft for commercial leasing over private leasing to individuals:
- We grouped our dataset by `Purpose.of.flight` and found that most incidents involved flights flown for personal purposes. 
- We define "commercial" as any `Purpose.of.flight` NOT in the personal category. 
- We then investigated the `Make` of the aircraft involved in the most incidents. 
- We found that of these top 5, most are single engine planes traditionally used for recreation and other personal purposes, such as Cessna and Piper. 
- This reinforces our inclination that private flying is riskier than commercial. 
- The exception to this rule is Boeing, the fourth riskiest `Make`.

 ### Out of large commercial aircraft, we recommend the Airbus A350 and the Airbus A220:
- Overwhelmingly, the largest commercial passenger aircraft manufacturers are Boeing and Airbus.
- Among these, we found that Airbus aircraft were involved in fewer incidents over the past 30 years. 
- Among the Airbus aircraft still in production, the A350 was the safest -- having suffered no incidents to date. 
- The A350 is a long-range/wide-body aircraft. Airlines considering leasing our aircraft are likely operating both the long-range/wide-body types of aircraft as well as the short-range/narrow-body types.
- We found that the Airbus A220 was the safest short-range/narrow-body type.

### Instructional flights were associated with relatively high incident rates. However, if large-bodied commercial aircraft are used the risk can be avoided:
- When examining the commercial and personal `Purpose.of.flight` data, instructional businesses appear to have a high level of risk.
- However, when we isolate commercial aircraft, our results show that instructional businesses should still be considered as a safe and viable option as long as only larger commercial airplanes are used. 
- This means an instructional business could be a viable option if the purpose is to train commercial pilots.


## Conclusion
We reccommend commercial operations over private. We advise considering instructional businesses they do not entail an especially high risk for heavy aircraft. Out of the largest manufacturers of heavy aircraft, we recommend Airbus, specifically the A350 and A220 models. 


