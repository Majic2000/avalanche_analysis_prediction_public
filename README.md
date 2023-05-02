# capstone 2023 - Avalanche analysis and prediction system - WORK IN PROGRESS

CODE IS COMMENTED ALL THROUGHOUT!

This ripo has been made to display my capstone that i did in ~7 days. Its about an avalanche prediciton system and evaluation of features most critical to an avalanche developed during my time at the DIGITAL FUTURES ACADEMY. 

--- INTRODUCTION:
Many past research in avalanhce prediction and analysis outlines time series data and weather build up. Most of said reserach connects to real time weather stations and data about avalanches within an area or resort that one works with, creating machine learning solutions that work with the build up of weather data and past occurances to predict the danger or avalanche activity given within the trained area. Gerenually for single reseracgers, gethering avalanche data if not wroking with an area is a time consuming task, it is infact possible to get said data but is behind many security measures and excess time which i did not have for this project. 
As such i thought of a new take on this problem: The general public.

--- BACKGROUND AND BREIF EXPLINATION
This capstone goest over public observations of avalanhces from the nwac.ac website (north west avalanche center). meaning that data has been gathered from anyone that is aware of the website and lives around that area. The public report on the textures of snow, covering its locations, date, weather and snowpack observations amongst others. Said data has been extracted using selenium and beautiful soups, inputted into pandas data frame and cleaned up. NLP TECHNIQUES were used in order to extract most dominant bigram and trigram word pairings and have been used to categories each entry from the user annoteted sentance observation. After feature extraction and feature engineering, models such as the XGBoost, SVM and Decision trees were experimented with. Results shown are promising reaching nearly 60% accuracy with a 76% recall (being one of the aims due to safety), the imballance of the data is still there and needs futher evaluation. With the data that was accessible, the initial project did well. 

--- TO IMPROVE:
1. Right now the input to model is pratically non-parametric due to categorising snow texture from user via NLP, need to collect 7/14/30 days of past eather data leading up to the observation to try to evaluate it further, group one input as 7 days.
2. Jackson hole avalanche center from america has been emailed to ask for their data for the improvenment of this project. Would mean more accurate data of yes no examples.
3. If step 3 does not improve the problem then for step 2, attempt thesame with different data set, frther implement it as a time series task and evaluate.
4. TO BE PLANNED 

--- FINALLY:
THIS IS A WORK IN PROGRESS, WAS MADE IN A WEEK DURING MY CAPSTONE FOR THE ACADEMY, HOWEVER IS SOMETHING THAT I KEEP IMPROVING UPON.
IF AND WHEN I GET THE JACKSON HOLE DATA I WILL MAKE A NEW DIRECTORY AND TEST IT THERE.

