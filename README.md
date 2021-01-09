# U.S-Health-Insurance-Regression-Analysis

## Inspiration
For insurance companies, it is often the case that they charge different premiums to two parties who are asking to be covered for the very same thing. It all comes down to how likely a party is to claim the insurance they are being covered for, and when they do, how expensive will it be. The very same logic is used by health insurance companies. We were interested in the effects different variables have on insurance costs as well as if we could accurately predict the costs using various predictor variables such as age, smoking habit, and the number of children. 

## What it does

 This project analyzes a dataset containing basic health information on 1338 medical patients and the charges billed to their insurance companies for that particular year (Dataset: [link](https://www.kaggle.com/mirichoi0218/insurance)). The report will begin by analyzing the basic relationship between variables, looking for significant insights both visually and statistically. Using the knowledge attained from the data analysis, a multiple regression linear model will be constructed for the purpose of predicting future charges to insurance companies based on the variables in the data set. 

## Challenges I ran into

One challenge I ran into when dealing with the dataset is the assumptions of regressional models. Using real-world data it may be difficult at times to always meet the assumptions of regression techniques and given the handful of transformation techniques learned at the time, I faced troubles particularly getting the normality assumption to hold for this data. However, with more complex techniques and concepts, I'm confident I'd be able to meet these assumptions for a better predictive model. 
 
## Accomplishments that I'm proud of

I'm proud of the thoroughness of the project as I believe we were able to explore many different models that had different characteristics and see how they performed against each other. The model was able to predict the insurance costs for the test set of individuals with an RMSE of 4341.8. 

## What I learned
I learned that it may not always be simple to meet regression assumptions and how this can pose a challenge when implementing models. I also learned about the importance of understanding your data by using data visualization and exploration methods before implementing any model(s). 
## What's next for U.S Health Insurance Regression Analysis

With more complex data transformation techniques I'd look into using those to improve the normality assumption for the data that would extend further than log or Box-Cox transformations. Also, exploring some more datasets could be useful such as looking at smoking frequency rather than if they smoked or not to be able to improve our model. 
