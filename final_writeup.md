
# Project Write-Up
## Target Sales Campaign: Predicting Potential Subscribers


### Abstract

This project inspected an dataset provided by [sushovan patra](https://www.kaggle.com/edith2021/bank-marketing-campaign) and fit the dataset into a real-world business scenario: identify customers who are likely to subscribe to the monthly customized vitamin plan. 



### Design

This project was inspired by my own real-life experience of subscribing to all kinds of services. I will often start a trial and cancel the service before a monthly payment happen. Thus, I came up with this idea of building classification models to predict true valuable long-term customers. 

<details><summary>Impact hypothesis</summary>
<p>

The hypothesis of this project is that demographic data can help identify long-term customers. And by utilizing classfification models, a soft prediction can be made to show the possibilty of subscription. 

</p>
</details>



<details><summary>Solution paths</summary>
<p>

**Suggested solution path:**
Build and pick the best classification model by:
- Data cleaning
- Exploratory data analysis
- Feature engineering
- Building baseline models
- Conducting cross validations for all models
- Using GridSearch to find the best hyperparameters
- Testing models' performance

</p>
</details>



<details><summary>Measures of success</summary>
<p>

- Technical: successfully build the interactive visualization and classfification models with decent performance 
- Non-technical: a reasonal model is build to make the prediction

</p>
</details>



### Data

This dataset is public available for research. The details are described in [Moro et al., 2011].
Please include this citation if you plan to use this database:

[Moro et al., 2011] S. Moro, R. Laureano and P. Cortez. Using Data Mining for Bank Direct Marketing: An Application of the CRISP-DM Methodology.
In P. Novais et al. (Eds.), Proceedings of the European Simulation and Modelling Conference - ESM'2011, pp. 117-121, Guimarães, Portugal, October, 2011. EUROSIS.

Available at: [pdf] http://hdl.handle.net/1822/14838
[bib] http://www3.dsi.uminho.pt/pcortez/bib/2011-esm-1.txt


### Algorithms

The algorithms in this project include: 

<details><summary>Feature Engineering</summary>
<p>

- Converting categorical features to numerical variables.
- Selecting subsets of the whole dataset to build baseline models. 
- Iterating the logistic regression model building and scoring process for all features and picking the best features combination.
- Handling imbalance data. 
</p>
</details>



<details><summary>Models</summary>
<p>

Logistic regression, k-nearest neighbors, random forest classifiers, XGBClassifier, decision tree classifier were used before settling on random forest, xgb and decision tree as the models with strongest cross-validation performance. 

</p>
</details>



<details><summary>Model Evaluation and Selection</summary>
<p>

The entire training dataset of 59,400 records was split into 80/20 train vs. holdout, and all scores reported below were calculated with 5-fold cross validation on the training portion only. Predictions on the 20% holdout were limited to the very end, so this split was only used and scores seen just once.

</p>
</details>


### Tools

- Tableau for interactive visualizaiton and EDA
- Pandas and NumPy for data manipulation 
- Matplotlib and seaborn for plotting
- Scikitlearn for modeling

### Communication

In addition to the slides and visuals presented, Subscription Prediction_Classification Project will be embedded on my website and blog.
