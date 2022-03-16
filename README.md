# Building A KNN From Scratch!
![This is an image](https://i.imgur.com/6H25wTM.png)
<br/>(Depicted: A simple data visual I created using matplotlib!)

<br/>

> ## 🤔 Purpose
Why re-invent the wheel? Well, for a while now, I've been wanting to learn more about how to apply machine learning models to my personal coding projects. However, my first few attempts at using ML libraries (like scikit-learn) WITHOUT a tutorial didn't work out. It was at that moment that knew I knew I was way out of my depth. So, by creating and implementing ML models from scratch (starting with a simple KNN algorithm), I hope to un-black box these models and gain a more fundamental understanding of the mathematical and statistical concepts behind them. As a result, I may hopefully apply them to novel use cases and tweak them as needed to best fit future scenarios.

<br/>

> ## ⚙️ Process
1.  WITHOUT looking at any code, I scoured the internet for articles and videos which included detailed yet digestable explanationß of the KNN formula. Sources I referenced heavily include [this article](https://machinelearningmastery.com/tutorial-to-implement-k-nearest-neighbors-in-python-from-scratch/) and [this video](https://www.youtube.com/watch?v=4ObVzTuFivY).
3. Opened up Jupyter notebook and began coding my first simple KNN algorithm, which consisted of a Euclidian distance calculator and could only handle datasets with two features, one target, and two classes.
4. Learned to use the pandas library in order to manipulate csv files using python. A key takeaway was learning how to translate categorial target values into numerical ones in order for the KNN algorithm to properly read the dataset.
5. Learned to use the matplotlib plotting library in order to better visualize and understand the KNN algorithm's workings from another angle.
6. Tested my model on a classic use case scenario: iris speciies classification! I used this [datast](https://www.kaggle.com/rutujavaidya/iris-dataset?select=Iris.csv) taken from Kaggle.
7. After further readings, I learned to implement additional features to my model, such as a function that checked the accuracy of the algorithm's predicted values as compared to the actual values, as well as a function which identified an optimal k value for a specific dataset that would return the most accurate predicted values.
8. With my newfound understanding of the KNN algorithm, I applied the KNN algorithm from the scikit-learn to the iris database. This helped in verifying the usability and accuracy of my algorithm. This also set me up well in learning how to fit and train future models with scikit-learn's library.

<br/>

> ## 👍 Victories and 👎 Challenges
1. 👎 Haven't yet figured out how to create a generalized KNN algorithm that can not only take a single unclassified data point, but also an array of unclassified data points.
2. 👎 Still learning the scikit-learn library's syntax and the understanding what exaclty certain functions are doing.
3. 👍 Created a KNN algorithm that can classify a datapoint in a three-class set consisting of four features and one target value. [insert link to file here]
4. 👍 Created simple data visualizations using matplotlib that depict the instance before and after a data point is classified. [insert images here]
5. 👍 Trained and implemetned scikit-learn's KNN algorithm. [insert link to file here]


<br/>

> ## 🔭 Conclusion
To re-iterate, the goal of this project was not to write the cleanest code, nor was it to write the most efficient KNN algorithm. The goal was to pull back the layers of this unfamiliar concept so that I can gain the confidence and intuition needed to apply KNN models to new and unfamiliar scenarios. So, in that regard, I think that this project was pretty successful, and, not to mention, also extremely rewarding! Moving forward, I'd like to continue ceating ML models from scratch, inclduing decision trees, random forests, genetic algorithms, and neural netoworks.
