# MLNN Team Templates
## File Organization
 - *decimal-dataset.csv*: microarray dataset where there are 12 columns. Each column = 1 mouse. The first three columns are the control group. The next three columns are non-drinkers. The next three columns are late-drinkers. The last three columns are early-drinkers.
 - *SVM Feature Selection.ipynb*: A simple SVM model for analyzing the microarray dataset. The last section is waiting for someone to complete the problem we discussed about the filtration method (learning vs. memorizing). This project uses a Leave-One-Out method to split the training vs. test dataset. Learn more by reading about LOO on Sklearn's site. 
 - *mousedrinkingdatasetfixed*: Clean dataset of the 120 mice drinking behavioral set. The mice (N=150) are set in rows (Not columns like the other dataset!). The first column is the class label (A=Control, B=Non-drinker, C=drinker)
 - *mousedrinking.ipynb*: time series analysis of mouse drinking behavioral data. Can be worked on to be more sophisticated. 


## Tasks that can be done
- Remake the SVM feature selection dataset filtration method so that the Chi2 test is done AFTER you split the dataset into training vs. test. 
- Cross-reference your algorithm methods on larger datasets- "https://www.sciencedirect.com/science/article/pii/S1532046404000693" use this as a primer. If you can't access the article, log in thru Rutgers VPN or something
- Is the “method” important to us, or is the “result” more important? Try expressing this in different testable ways.
- Work on Mouse Drinking behavioral dataset and tweak algorithms to get even better results. Most of the algorithms are on "default" settings. They can be further customized by changing parameters, potentially giving us even stronger results
- Use Bayesian methods (cool algorithmic way of solving the problem) for the mouse drinking dataset. "https://towardsdatascience.com/what-is-bayes-rule-bb6598d8a2fd" Use this as a primer on Bayes.
- Unsupervised Learning methods- "Will machine learning cluster/categorize the mice into a surprising, insightful way that we have not considered?" Test this by using clustering algorithms instead of classification algorithms
- Continuous vs. Class Labels- Our labels are A/B/C/D- non-numerical classes. Can we synthesize numerical values to each mouse (amount they drink, tendancy to drink, rate of drinking, anything) and then use that data to apply regression/numerical predictive algorithms. This is a bit tricky since each of the "mice" in the N=12 microarray dataset is actually a synthesis of multiple mice put together. You would have to work your way backwards, connecting the drinking dataset to the microarray dataset. 
- Visualization- can we visualize our results in meaningful, insightful ways? There are lots of beautiful, unique python libraries to express unique facets of data.
- Statistical analysis on data- useful for describing the nature of the data we have available- helps us make decisions on how to use different algorithms on dataset.
