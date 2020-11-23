# Instructions
It seems that the Covid pandemic will be an issue the World will deal with for at least the near future.  The pandemic has shown to hold serious implications for the economy, education and mental and physical healthcare.  It stands to reason that the ability to forecast Covid cases could provide society with the information it needs to, among other things, apply valuable resources (financial, medical, etc) in a timely, efficient and effective manner.  This project focuses on providing these invaluable forecasts through the use of the time series models and methods we have studied this semester.  

## Goal 1: Data Collection

As we all know, much of the data scientist’s (time series analyst’s) initial work on a project is gathering and cleaning the correct, or at least useful, data.  Currently it seems that the media and the government prefer to report the total number of cases and deaths per time period and geographic region.  Lately however, we have been hearing more about the “positivity rate” (aka “percent positive”, “positive percentage” and other names).  Research this statistic and decide which measure you feel is more telling about the current severity of the pandemic and the progress that the nation (or certain locals) are making in curbing it.  Report specifically on:
  a.	What the “positivity rate” statistic is.
  b.	Where you found raw data and information on the total number of cases, total number of deaths and the “positivity rate”.  
  c.	Provide an initial exploratory data analysis using data for your given state and the nation as a whole.  (Every group will be assigned their own State although each group will also analyze the nation as a whole.). The EDA should simply include a slide or two with time series plots, answers to the questions above and any other tables or charts that help convey the information you have gathered and that you think will be important in providing the forecasts.

## Goal 2: Univariate Analysis

This analysis will be focused on providing both short- and long-term forecasts for your given state and the nation as a whole using only the single time series (no additional explanatory variables).  The short-term forecasts will be forecasts for the next 7 days while the long-term forecasts will be for the next 3 months. Note: you may use different models for the short- and long-term forecasts.  This analysis should address:
  a.	Stationarity versus Non-Stationarity and any concerns you may have about the integrity of the data (if any.) 
  b.	Any non-stationary modeling of the data (differencing, etc.) if any.
  c.	Model IDing of any stationary models. 
  d.	Model Building
  e.	Comparing / Assessing / Evaluating Candidate Models (ASE, AIC, etc.)
    i.	At least 1 ARMA / ARIMA type model
    ii.	At least 1 MLP / RNN (neural network) type model
    iii.	At least 1 ensemble model (this can be a simple average of the forecasts of the models above.)
    iv.	Note: Rolling Window ASE required.
  f.	Effectively producing, presenting and explaining your short- and long-term forecasts (including confidence intervals).  

## Goal 3: Multivariate Analysis

This analysis is very similar to the univariate analysis although you are now able to add explanatory variables to the model.   This analysis will be focused on providing both short- and long-term forecasts for your given state and the nation as a whole using the time series realization and at least 1 exogenous / explanatory variable of your choosing.  The short-term forecasts will be forecasts for the next 7 days while the long-term forecasts will be for the next 3 months. Note: you may use different models for the short- and long-term forecasts.  This analysis (one for the short term and one for the long-term forecasts) should address:
  a.	Stationarity versus Non-Stationarity and any concerns you may have about the integrity of the data (if any.) 
  b.	Any non-stationary modeling of the data (differencing, etc.) if any.
  c.	Model IDing of any stationary models. 
  d.	Model Building
  e.	Comparing / Assessing / Evaluating Candidate Models (ASE, AIC, etc.)
    i.	At least 1 VAR and / or MLR with correlated errors type model
    ii.	At least 1 MLP / RNN (neural network) type model
    iii.	At least 1 ensemble model (this can be a simple average of the forecasts of the models above.)
    iv.	Note: Rolling Window ASE required.
  f.	Effectively producing, presenting and explaining your short- and long-term forecasts for both your given state and the nation as a whole (including confidence intervals).    


## Intended Audience:

Your intended audience is the head health official in the state you are researching.  This is usually the Director of the Department of Public Health but may vary per state (find out who this person is and address him/her in your introduction and conclusion.)  You can assume that this person directly advises the Governor of that State on COVID-19 related topics such as the reopening schedule for businesses and schools as well as the controversial topics such as mandatory mask ordinances, social distancing and even complete lockdowns.  You can assume this person has taken an introductory course in statistics and another in time series and are familiar with ACFs, spectral density plots, ARMA/ARIMA models, AIC, ASE, and the tests that are associated with these models (ie Dickey-Fuller Test).   However, they may be not be as familiar with VAR modeling and deep learning models as you may assume they were not as accessible when they went to school.  Your goal is not to convince them of any political or medical opinion, rather to educate them on the facts (and some methods) so they can make their own decision for the best interest of the state.  

## Rubric:
Initial Project Presentation: 5%
	EDA see below
Initial Project Documentation: 5%
	EDA see below

Final Project Presentation: 40%
  •	Communication and presentation of your findings are critical to being a successful data scientist.  You will be graded individually on:
    o	Presenting at least 3 minutes
    o	Voice inflection
    o	Slide Organization / Content
    o	Visualization (including clear, visually appealing and labeled plots).
    o	Composure: This will include not reading off of the slides and smoothness of delivery.  
    o	Pace: Not going a second over 8 minutes.  Your client is very strict on this point.    

Final Project Documentation 50%
  •	Knit RMD: 10% (Same grade for both team members.)
    o	Well organized and documented RMD knit to pdf or html.  
  •	Results / Analysis: 40% (Same Grade for both team members.) (Double check the entire project, not just your part.)
    o	Correct Interpretation
    o	Creating Useful Models
    o	Performing a Complete Analysis: Model ID, Model Building, Forecasting, Cross Validation
    

## Deliverables

EDA: 
Sunday November 22nd at 11:59pm Central Time
Deliverable:
  1.	4-minute (max) YouTube video:  (As a group, each student must present for at least a minute.) 
    a.	Identify yourself and your partner (if applicable).  Goal 1
    b.	Describe the Data Set / Time Series (Who, What, When, Where, Why and How) Goal 1
    c.	Stationary / Non-Stationary Goal 2
    d.	ACFs and Spectral Densities just to explore Goal 2
    e.	At least 2 (total) candidate ARMA / ARIMA models (univariate) Goal 2
      a.	The models in factored form or at least separate the stationary and non-
      stationary factors with standard deviation or variance of the white noise.
      b.	AIC
      c.	ASE (Rolling window)
      d.	Visualization of Forecasts (Short and Long Term / State and National) 
    f.	Strategy / Plans for the rest of the analysis.
  2.	Submit your slides to 2DS under Initial Project Documentation and make sure your video URL is on the Google Doc. 

Final Project Documentation and Presentation:
 Saturday, December 5th at 11:59am Central (“am” as I will need the rest of the day to start grading them before the final exam.)

  1.	Addressing a summary of Goal 1 and fully addressing Goal 2 and 3.  
  2.	PowerPoint Presentation (1 per group)
  3.	RMD or Jupyter Notebook (1 per group) 
  4.	8-minute (or less) You-Tube video presenting your PowerPoint (or Presi or LaTex) slides. (1 per group but each student must speak for at least 3 minutes.) 
  5.	Post that video to you-Tube (or provide Zoom link) and the (private) link to the Google-Doc and submit your ppt and Rmd File (or Jupyter notebook) to 2DS.  Please leave the link on the Google Doc for a week so others can learn from your presentation.  Please check out at least 3 of your peer’s presentations and please watch your own presentation as well.   It is often very useful (although always a bit awkward for me at least ;) to watch yourself present!
  6.	Submission
    a.	The link to your you-tube presentation on the Google-Doc
    b.	your pptx (or slides in whatever form (pdf, Prezi, etc.) (Put in “Final Project Documentation.”)
    c.	an R markdown (RMD) or Jupyter notebook or equivalent (Put in “Final Project Documentation.”) this file should contain all of your EDA, modeling and forecasting code and be very organized and well commented.
