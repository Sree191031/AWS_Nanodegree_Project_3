# Customer Segmentation – Arvato Financial Solutions

##**Problem Statement**
“How can the German mail-order company acquire new customers more efficiently, given the access to German demographics data?”<br/>
The problem can be quantified in the following terms:<br/>
Number of current/established customer clusters (customer segmentation unsupervised problem) and probability of being a new customer to the company (supervised problem).<br/>
Machine Learning techniques can be employed in the two main subsections of the project:<br/>
● Using unsupervised learning methods on the data of established customers and the general population’s demographics data, we can create customer segments.<br/>
● Using supervised learning methods on a third dataset, we can train a model to predict the probability of a person becoming a new customer (above a certain threshold, the model will assign the person to be a highly probable new customer), and use this model for future predictions.<br/>

##**Solution**<br />
1.Ultimately, Arvato Financial Solutions’ goal is to enable their client company to gain insight from their current established customer base in order to better target the German population at large, by predicting in advance and with sufficient accuracy who would become a future customer.<br />
<br />
2.To make that possible, after initial data exploration and cleaning, we will first employ unsupervised learning techniques to identify customer segments (customer segmentation): these include applying **PCA (Principal Component Analysis)** for Dimensionality Reduction, and an algorithm such as K-Means Clustering to obtain the meaningful **‘clusters’** of customers.<br />
<br />

3.Then, we will make use of supervised learning techniques for the second part of the project, which consists of predicting future potential clients from the German Population dataset, based partially on insight gained by customer segments. For this task, we will try different supervised
algorithms, such as **DecisionTreeRegressor (from sklearn module in Python), XGBClassifier, RandomForestClassifier (sklearn), or GradientBoostingClassifier (sklearn).**<br />

<br />
4.At this premature stage of the project (Proposal), it is impossible to choose one supervised algorithm over another, so we keep a wide range of choices until actually working on the task. Keeping our options open will help us get to an approach (not necessarily the ones cited above) with satisfying results.<br />
