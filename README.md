# deep-learning-challenge
## Overview
We are trying to help Alphabet Soup, a non profit foundation, to get a tool that helps select the applicants for funding with the best chance of success in their ventures. We are helping them by using our machine learning skills, neural networks and by then using the features that come with the dataset they have provided for us. Once applied we can help Alphabet Soup decide/predict the best applicants.

## Results
* Data Preprocessing
  * Our target variable is the column 'IS_SUCCESSFUL' from the application_df
  * Our features for the model are each of the columns in application_df not including 'IS_SUCCESSFUL'(the target variable),'EIN' and 'NAME'
  * The necessary variables that were removed were both the 'EIN' and 'NAME' columns since they are not targets or features.

* Compiling, Training, and Evaluating the Model
  * For my first try I referred to the starter code and chose what was given. There were two hidden layers one had 80 and the other 30 which gave me an accuracy of 72.40%. Then I proceeded to attempt to recreate it and use more layers this time thinking I could go into the right direction which improved to an accuracy of 73.71%. I had made many attempts to get a higher accuracy but it seemed to get lower each time. Even by adding layers it lowered. I believe my mistake could've stemmed from not using random_state appropriately thus giving me different accuracies at every attempt afterwards thus I was not able to reach the target model of 75%.

## Summary
After many attempts my highest accuracy was 73.71%. The best recommendation to get closer or to even achieve the target model would most likely be by tuning, possibly do some more data clean up and using the same random_state to use the same sets to get a better result. 
