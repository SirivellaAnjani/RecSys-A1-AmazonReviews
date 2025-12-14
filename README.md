Assignment Requirements:


CP8339 Assignment 1
Due: Oct. 11, 2025
In this assignment, you are going to use the Amazon review dataset 2023 (https://amazon-reviews2023.github.io/). Pick one category (e.g., Amazon_Fashion, Baby_Products, Video_Games), and
download the dataset. When downloading the dataset, you can download review only, review and
meta, or rating only (there is an option for ratings only file). Perform any necessary data preprocessing steps. On the processed dataset, run a few baseline recommendation models, such as
item-based collaborative filtering (itemKNN), user-based collaborative filtering (userKNN),
matrix factorization (or any of the variations such as SVD, SVD++, NMF, or generalized latent
factor models such as factorization machines), then choose one more advanced model (e.g., deep
learning models) to run. Report the results using two types of evaluation metrics – error metrics
such as RMSE, MAE, accuracy metrics such as precision, recall, F1, AUC, etc. You should run at
least three models.
For the advanced model, you can choose to use the rating data only, or you can add review data or
even meta data. Make sure the model you choose has the capability of processing and using the
data you have included in your dataset.
You can use a recommender system library such as RecBole1
, Recommenders2
, EasyRec3
, or any
other libraries that you know. You can also use any machine learning or deep learning libraries.
The requirement for the final report:
1) The description and basic statistics of the dataset should be provided;
2) The pre-processing steps performed on the dataset should be explained;
3) The environment running the experiments (e.g., hardware configuration, software packages
used, etc.) should be specified;
4) There should be a brief description for each tested model and the selected parameter values (if
there is a parameter tuning phase, explain the steps);
5) The selected evaluation metrics should be defined;
6) The results from all the tested models should be included in a big table, if necessary, you can
also include other tables or figures to show the results;
7) Some analyses and discussions on the results could be provided;
8) Any additional observations, findings, discussions could be included.
The code and the final report should be uploaded to D2L.
1 https://recbole.io/
2 https://github.com/recommenders-team/recommenders
3 https://github.com/alibaba/EasyRec
