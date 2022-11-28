# car_price_prediction
Second practical assignment

  After careful analysis of provided data on more than 400k sales of used vehicles, the team was able to build a linear regression model predicting sale price based on a number of characteristics of each vehicle (model, condition, age, etc.) with average accuracy of +/- 20%. 
  
  In addition to leveraging the model to predict a recommended listing price for a new vehicle, the model's greater value is its ability to identify price impact of specific characteristics on the final price which you will be able to use when making assessments of potential vehicles.
  
  Based on the number of reviewed characteristics, age of the car has the most significant impact on the overall value. Unfortunately, the relationship is not linear so there is no simple rule subtracting a specific amount for each year. Generally, older vehicles have a more significant negative impact on price than newer.
  
  <img width="607" alt="Model performance" src="https://user-images.githubusercontent.com/63613300/204240378-4206841f-2464-4a55-b14e-37fef44ffea9.png">


  As expected, specific models also have a huge impact on price that varies wildly across models (both positive and negative). Some examples include: 
  - Skyline gtr 32 and Eurovan Camper increase price by almost 180%
  - 4runner sport AWD and F-250 super duty lead to almost a x4 price decrease
Note: Specific model impact for cars with few sales may be volatile, use caution. Full model list and their impact is provided in appendix.
    
    
  Manufacturer of the car is another important characteristic impacting car price. Some of the top and bottom makes and their impact are:
  - Saturn, Kia, Mercury and Fiat are almost 40% cheaper
  - Ferrari is the most expensive with almost 180% higher price
  - Porsche, Tesla and Astom-Martin have 85%, 82% and 74% higher price respectively
    
    
  Condition also has a signficant impact on price with Excellent and Like New commanding a 34% and 29% price premium respecitvely, while Salvage and Fair deprecating sale price by 57% and 37% respectively.
        
  Finally, while paint color has a much smaller impact than other variables, some colors do perform better than others with regards to the sale price:
  - Yellow, custom and orange have a 5% and 4% premium respecitvely
  - Brown, green and purple decrease price by 5.5%, 3.7% and 3% respecitvely.
        
        
  Finally, in addition to using the above characteristics when making pricing decisions for upcoming car listings, we recommend:
  - Where possible, taking advantage from potential arbitrage when procuring used vehicles (i.e. if two different colors have the same price but one color has higher impact on final sale, get that color)
  - For further improvements of the model and understanding, create improvements to the process of data collection - as part of the analysis we found a lot of mistyped data entires or simply missing information - out of the initial dataset of over 400k items, we were able to use less than a third for modelling. While that didn't impact the ability to create a model, more data equals better precision and will help with future revisions to the model
