# Board_Game_Geek_Analysis_ML
Machine Learning analysis of board game user ratings and ownership reports based on data from Board Game Geek. Creates models that can predict average user reviews and ownership numbers based on factors and mechanics of a board game. Also looks into factors that potentially contribute to successful board games, to help make design/publishing decisions.

BGG_Data_Set.xlsx is the original data, obtained from IEEE 

Data Cleaning and Overview.Rmd is script for data cleaning/seperating dummy variables and getting the data into a workable form

clean_data.rda Is the data file after cleaning

Rating_ML.Rmd is the machine learning code for predicting ratings

Owners_ML.Rmd is the machine learning code for predicting ownership

Owners_ML_logTransform.Rmd is the machine learning code for predicting ownership that has been log transformed. This was found to be a more accurate way than without the log transform, as the data here is right-skewed.

a_insights_shap_functions.r is code used to extract SHAP values to determine variable importance. - originally published at https://liuyanguu.github.io/post/2018/10/14/shap-visualization-for-xgboost/ - minor changes have been made in order to display values in the color scheme of BGG

Final Report - Machine Learning.pdf is the final report and discussion of the project

HTML versions of Rmd files are included as well.
