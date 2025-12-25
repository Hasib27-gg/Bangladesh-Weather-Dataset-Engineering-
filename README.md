# An general guide through the engineering of this dataset

## [1] What is this?:
Hello! I am Hasib saying 👋. As a 7th grader , I am still beginner into Machine Learning and Deep Learning territory . This is just a
repo, contaning how I achieved 0.838 accuracy on a particular dataset. Eventhough this is not polished, I tried my best to get deep
intuation into the dataset. 


## [2] The dataset:
**Check the External Dependencies for the direct link to the dataset in kaggle.**
This is a tabular dataset, containing 10 years of weather information of Bangladesh. The dataset is divided into three parts: train.csv,
test.csv and sample_submission.csv. This dataset is very small, compared to the aggressive enginnering in the notebook. The dataset is also
quite straight forward , conating no null data. Additionally, the dataset is quite imbalanced, about 26% positive results. \n
## NOTE: The datasets have a massive exploit: The sample submission contains all the actual values for testing the model, meaning that we actually knew the answers and we didn't need to spend any time on enginnering :( .

## [3] The engineering & stratigies:
**Check the Engineering Pipeline for full walk through the code.**
At first, feature enginnering required for the dataset , like simplifying the names of columns, checking if null columns exists , 
converting the datetime to days , filtered the dataset by dropping unecessary columns etc. to make the dataset fittable and predictable.
Then used various model selection stragy to makeup the model. The actual model is hybrid , meaning the predictor model is made up base and meta
models. 

## [4] The result and submission:
I couldn't submit to the actual kaggle competition. However, I checked the accuracy through using the sample submission as it contains all the
actual values and obviously my model. I got, 0.838% accuracy, better than most contestants in the actual competition , but I know it's horrable.

## [5] How to use the code in my computer:
**Check the Requirements for all information and guide . If you don't follow, the code may break / raise Error.**

Please inform if you find any bug or significant improvement in the code or the model enginnering
