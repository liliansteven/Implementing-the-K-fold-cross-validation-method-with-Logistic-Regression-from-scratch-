# Implementing the K fold cross validation method with Logistic Regression from scratch :-

## K-Fold :-
In each set (fold) training and the test would be performed precisely once during this entire process. It helps us to avoid overfitting. As we know when a model is trained using all of the data in a single short and give the best performance accuracy. To resist this k-fold cross-validation helps us to build the model is a generalized one.

To achieve this K-Fold Cross Validation, we have to split the data set into three sets, Training, Testing, and Validation, with the challenge of the volume of the data.

Here Test and Train data set will support building model and hyperparameter assessments.

In which the model has been validated multiple times based on the value assigned as a parameter and which is called K and it should be an INTEGER.

Make it simple, based on the K value, the data set would be divided, and train/testing will be conducted in a sequence way equal to K time.

# Life Cycle of K-Fold Cross-Validation :- 
![alt text](https://editor.analyticsvidhya.com/uploads/30302K-fold%20lift%20cycle.png)

# What is logistic regression?
Logistic regression is a data analysis technique that uses mathematics to find the relationships between two data factors. It then uses this relationship to predict the value of one of those factors based on the other. The prediction usually has a finite number of outcomes, like yes or no.

For example, let’s say you want to guess if your website visitor will click the checkout button in their shopping cart or not. Logistic regression analysis looks at past visitor behavior, such as time spent on the website and the number of items in the cart. It determines that, in the past, if visitors spent more than five minutes on the site and added more than three items to the cart, they clicked the checkout button. Using this information, the logistic regression function can then predict the behavior of a new website visitor.

# Why is logistic regression important?
Logistic regression is an important technique in the field of artificial intelligence and machine learning (AI/ML). ML models are software programs that you can train to perform complex data processing tasks without human intervention. ML models built using logistic regression help organizations gain actionable insights from their business data. They can use these insights for predictive analysis to reduce operational costs, increase efficiency, and scale faster. For example, businesses can uncover patterns that improve employee retention or lead to more profitable product design.

#### Simplicity 
Logistic regression models are mathematically less complex than other ML methods. Therefore, you can implement them even if no one on your team has in-depth ML expertise.

#### Speed
Logistic regression models can process large volumes of data at high speed because they require less computational capacity, such as memory and processing power. This makes them ideal for organizations that are starting with ML projects to gain some quick wins.

#### Flexibility
You can use logistic regression to find answers to questions that have two or more finite outcomes. You can also use it to preprocess data. For example, you can sort data with a large range of values, such as bank transactions, into a smaller, finite range of values by using logistic regression. You can then process this smaller data set by using other ML techniques for more accurate analysis.

#### Visibility
Logistic regression analysis gives developers greater visibility into internal software processes than do other data analysis techniques. Troubleshooting and error correction are also easier because the calculations are less complex.

# Logistic regression function
Logistic regression is a statistical model that uses the logistic function, or logit function, in mathematics as the equation between x and y. The logit function maps y as a sigmoid function of x.

![alt text](https://d1.awsstatic.com/sigmoid.bfc853980146c5868a496eafea4fb79907675f44.png)

If you plot this logistic regression equation, you will get an S-curve as shown below.

![alt text](https://d1.awsstatic.com/S-curve.36de3c694cafe97ef4e391ed26a5cb0b357f6316.png)
