# Naive Bayes Classifier
The Naive Bayes Classifier technique is based on the so-called Bayesian theorem and is particularly suited when the dimensionality of the inputs is high. Despite its simplicity, Naive Bayes can often outperform more sophisticated classification methods.
Typical applications include filtering spam, classifying documents, sentiment prediction etc. It is based on the works of Rev. Thomas Bayes (1702–61) and hence the name.
![NaiveBayes](http://www.statsoft.com/textbook/graphics/NaiveBayesIntro1.gif)
To demonstrate the concept of Naïve Bayes Classification, consider the example displayed in the illustration above. As indicated, the objects can be classified as either GREEN or RED. Our task is to classify new cases as they arrive, i.e., decide to which class label they belong, based on the currently exiting objects.

Since there are twice as many GREEN objects as RED, it is reasonable to believe that a new case (which hasn't been observed yet) is twice as likely to have membership GREEN rather than RED. In the Bayesian analysis, this belief is known as the prior probability. Prior probabilities are based on previous experience, in this case the percentage of GREEN and RED objects, and often used to predict outcomes before they actually happen.
![NaiveBayesIntro2](http://www.statsoft.com/textbook/graphics/NaiveBayesIntro2.gif)
Since there is a total of 60 objects, 40 of which are GREEN and 20 RED, our prior probabilities for class membership are:
![NaiveBayesIntro3](http://www.statsoft.com/textbook/graphics/NaiveBayesIntro3.gif)