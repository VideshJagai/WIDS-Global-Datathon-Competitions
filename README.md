# WIDS-Global-Datathon-Competitions


          ****WiDS Challenge Datathon Competition 2023.****

Theme of  Challenge: Adapting to Climate Change by Improving Weather Forecasts.

- This year International Datathon Challenge , organised by the WiDS Worldwide Team at Stanford University, Harvard University IACS, Arthur, and the WiDS Datathon Committee.

- The dataset was created in collaboration with Climate Change AI (CCAI) whereby individuals able to submit forecast of temperatures and precipitation for one year.

Our group team name is Data Buddies. The following below are listed participants: 

i)  Nicholas Smith

ii)	 Kimberly Gillette

iii)	Lilliam Norori

iv)	 Videsh Jagai


•	Data Ingestion, Data Pre-processing,  Data Summary: Nicholas Smith.

•	Data Manipulation and Visualisation: Nicholas Smith., Lilliam Norori, Videsh Jagai.

•	Feature Engineering and Data Modelling: Nicholas Smith,  Kimberly Gillette, Lilliam Norori, Videsh Jagai

 Problem Description: Extreme weather events are sweeping the globe and range from heat waves, wildfires and drought to hurricanes, extreme rainfall and flooding. These weather events have multiple impacts on agriculture, energy, transportation, as well as low resource communities


 Proposal: Accurate long-term forecasts of temperature and precipitation are crucial to help people prepare and adapt to these extreme weather events.

 Relevance: The availability of meteorological data offers an opportunity for data scientists to improve sub-seasonal forecasts by blending physics-based forecasts with machine learning. Sub-seasonal forecasts for weather and climate conditions would help communities and industries adapt to the challenges brought on by climate change.

Two datasets:

 train_data.csv: The training dataset, where target variablecontest-tmp2m-14d__tmp2m, the arithmetic mean of the max and min observed temperature over the next 14 days for each location

 From deciphering the relevance of our feature columns feature engineering; function (def location_feature(train, test): ) , targeted scalability of latitude/longitude  and proceeding in concatenation of both train & test data (  train_and_test = pd.concat([train, test], axis=0)). Highlighting the allocated unique column feature termed ‘loc group’ distinguishing clearly its location in relation to the target variable.



 Models Incorporation Performance: Various diverse models such as : XGBoost, RandomForestRegressor, Catboost, Lasso and Gradient boosting ensemble. It is underscored that the final prediction is an ensemble of two models. The ensemble_preds variable is a weighted average of the two models predictions. Combining them can lead to a robust and accurate prediction












