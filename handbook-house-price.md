In case you have chosen the **Project Idea: Heritage Housing Issues**, please consider the following instructions. We also would like to reinforce that the data source for this project is located [here](https://www.kaggle.com/codeinstitute/housing-prices-data).

---

## Repository Template
In case you do not want to build one repo from scratch, we suggest you fork this [repo](https://github.com/Code-Institute-Solutions/milestone-project-heritage-housing-issues). Once you forked you may also personalize and rename the repo if you want to.

---


## Business Case Assessment
You have already conducted a business case assessment, so you can also use that information to build your project README file 

* 1: What are the business requirements?	
    * 1 - The client is interested in investigating how the house attributes are correlated with the Sale Price. The client is interested in the top 5 most relevant variables correlated to Sale Price.
    * 2 - The client is interested to predict the house sales price from her 4 inherited houses, and any other house in Ames, Iowa. 

* 2: Is there any business objective that can be answered with conventional data analysis?		
    * Yes, we can use conventional data analysis to investigate how the house attributes are correlated with the sales price

* 3: Does the client need a dashboard or an API endpoint?		
    * The client needs a dashboard

* 4: What does the client consider as a successful project outcome?		
    * A study showing the most relevant variables correlated to Sale Price.
    * Also, a capability to predict total sales price for the 4 inherited houses 

* 5: Can you break down the project into Epics and User Stories?		
    * Information gathering and data collection
    * Data visualization, cleaning, and preparation
    * Model training, optimization and validation,
    * Dashboard planning, designing, and development
    * Dashboard deployment and release. 

* 6: Ethical or Privacy concerns?	
    * The client found a public dataset	

* 7: Does the data suggest a particular model?		
    * The data suggests a regressor where the target is Sale Price

* 8: What are the model's inputs and intended outputs?
    * The inputs are house attribute information and the output is the predicted sale price

* 9: What are the criteria for the performance goal of the predictions?	
    * We agreed with the client at least 0.8 for the R2 score

* 10: How will the client benefit?		
    * The client will maximize the sales price for the inherited properties

---

## Project considerations
* In case you want to use a spreadsheet to list your variables for the data cleaning and feature engineering steps, you may download the template in this [link](https://docs.google.com/spreadsheets/d/1pucuXPJM3UIaj6vb08NVanujpv0EcHol/edit?usp=sharing&ouid=104188414838408143200&rtpof=true&sd=true). This file will not be assessed and it will not be marked to compose your final grade, it is just an auxiliary file you can use in your workflow
    * In this file, you should list the names of the variables

* Business Requirement 1
    * You may perform a correlation and/or PPS study to investigate the most relevant variables correlated to Sale Price.
    * You visualize these variables against Sale Price, so you can summarize the insights.

* Business Requirement 2
    * You may deliver an ML system that is capable of predicting reliably the summed sales price from the 4 inherited houses
    * You may use either conventional ML or Neural networks to map the relationships between the features and the target
    * You may consider changing the ML task from Regression to Classification if you find a valid rationale for that.

---

## Dashboard expectations
* Your dashboard should contain at least:
    * A project summary, showing the project dataset summary and client's requirements.
    * A page listing your findings related to which features contribute most to house sale price.
    * A page displaying the 4 houses attributes and their respective predicted price. It should have also a text message informing the summed predicted price for all 4 inherited houses. You should add interactive input widgets where you can predict real-time house data provided by a user.
    * A page indicating your project hypothesis and how you validated it across the project.
    * A technical page displaying your model performance. If you deployed an ML pipeline, you have to display your pipeline steps.
