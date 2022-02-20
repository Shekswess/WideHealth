# Widehealth competion ML project

-This is a project that is made for my winter machine learing school (WideHealth Winter School on e-Health & Pervasive Technologies)

-This is a pretty good ML portfolio project

-This project was build with help of my team from FEEIT

-We were 6th place of 12 groups, with accuracy of 81%

-Longer description for the project:

We were given a cleaned data set. The values of the data set were filtered, then we added a lot of features(statistical, time-domain). After 
clearning and joining the data on csv files, we are doing the validation, after that the same procedure and then training the data, smothening the predictions
using the cr library builded by the people of Stefan Jozef institute in Ljubjana and getting the end result. For the model XGBoost is used.

The evaluation metric for this competition is Mean F1-Score. The F1 score, commonly used in information retrieval, measures accuracy using the precision and recall statistics.

The submission files should contain two columns: index and activity_id. The first value in each row (in the index column) is the index of the window (from the segmented test data) for which a prediction is made. The second value is the prediction for the activity being performed by the user during the indexed window. The prediction, for each window, should be an integer number produced using the following mapping values:
 
{
    'lying': 1,
    'walking': 2,
    'transition': 3, 
    'sitting': 4, 
    'standing': 5, 
    'kneeling': 6, 
    'allfours': 7, 
    'bending': 8, 
    'cycling': 9, 
    'running': 10
}
 
# Working with the project

-You need to have installed Anaconda pack and work with Jupyter Notebooks, or with python3 or you can work with kaggle. Plus you need to have installed 
XGBoost and cr-features libraries.

-To start the project, just download the data set, do some little changes in the code (the location of the data set) and run all the code boxes.


# More detailed information about the whole winter school, the competition and the lectures can be found on:

## https://www.kaggle.com/c/winter-school-2022-ar-challenge/overview/evaluation
## https://widehealth.eu/winter-school-pervasive-technologies/

P.S the train and filtered train data need to be added or find them on kaggle

