#Beyond the Tweet: Exploring Reddit as an Alternative Resource for Disease Forecasting

##EXECUTIVE SUMMARY 

Disease forecasting, a crucial component of the strategic response to pandemics like Covid-19, increasingly relies on digital data, offering large-scale immediate insights, ultimately helping to save lives [1]. However, Twitters recent paywall restrictions limits this crucial resource [2], requiring exploration of alternative resources to maintain preparedness against future pandemics.

###Aims and Objectives
Our research aims to evaluate Reddits unexplored utility for disease forecasting, employing a case study design, with a longitudinal focus on the initial Covid-19 pandemic period between 1st March – 31st December 2020 in the USA. Our objectives centre on assessing Reddits feasibility for forecasting, how suitable methodologies can be adopted, and to empirically measure Reddits forecasting utility. 

###Methods
Covid-19 data was collected from the World Health Organisation, and Reddit data from an opportunistic dataset from SocialGrep.com. For information extraction, we classify Reddit texts along an ‘Author’ and ‘Contact’ dimension, capturing direct and indirect accounts of Covid-19 infections respectively. We train BERT models to classify Reddit texts, then acquire time-series data summarising temporal changes in Reddit classification label frequency.
We simulate a real-world forecasting exercise, generating overlapping training and test sets using a Rolling-Window approach, then predict Covid-19 incidence 1, 7 and 14-days ahead for both baseline and Reddit-enhanced Random Forest Regression (RFR) models using a Walk-forward testing approach. 

###Findings
Our exploration revealed Reddit provides direct and indirect indicators of Covid-19 incidence and trajectory. Our Reddit-enhanced RFR models improved baseline prediction errors (MAE) by 23.26% and 31.83% for 7 and 14-day forecasts respectively and reduced the MAPE variability to 4.74% from the baseline's 10.18% at 14-day forecasts; indicating our Reddit features produce more robust and accurate Covid-19 forecasting models, particularly at longer forecast horizons.
Of our Reddit features, personal accounts of infection were consistently the strongest predictor to Covid-19 incidence, with a strong correlation of 0.95, whilst suspected/ambiguous and second-hand accounts showed weaker correlations, 0.37 and 0.70 respectively, and less informative for predictions. 

###Limitations
However, no improvement was observed for immediate 1-day ahead predictions, and Reddit features provided little information at a significant Covid-19 peak, questioning predictive reliability. 
Our exploration likewise revealed inherent challenges in Reddits real-world application, as its lengthy texts and lack of geospatial data limits both timely and specific insights, critical requirements for disease surveillance [3].

###Ethics Considerations 
Though Reddit users post content in the public sphere, issues of informed consent arise since users are unaware their posts are utilised for insights and real-world applications. This likewise links to privacy issues, as textual exploration may inadvertently identify individuals who have a right to anonymity. Whilst disease forecasting aims to benefit public health, underrepresented users and communities within forecasting data may produce biased conclusions, potentially harming vulnerable populations [4].

###Conclusion
Despite these challenges, our exploration revealed Reddit provides comparable classification-based indicators to Covid-19 as Twitter, highlighting the importance of investigating alternative digital resources and improving collective preparedness for future pandemics. 


