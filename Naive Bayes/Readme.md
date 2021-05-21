# Naive Baeyes Algorithm
It is a very simple classificiation based on **Baeyes Theorem**.
Assumptions:
- ### IID:
It states that all the features which are used in classification are independent and identical from each other.
    - **Independent**: This means that each feature is purely independent of each other and one does not effect another.
    - **Identical**: This means that we are assuming that each of the feature is obtained from the same distribution , in this case Mullitvariate Gaussian.
#### Baeyes Theorem:
$$P(A|B) = \frac{P(B|A)P(A)}{P(B)}$$
For machine learning , naive baeyes can be written as :
$$P(class|data) = \frac{P(data|class)P(class)}{P(data)}$$
- P(class) : Prior Probability , it is the probability of class in the given dataset.
- P(data): Total probability 
- P(data|clas) : Likelihood Probability , probability of class having a given data value associated to it.
- P(class| data) : Posterior Probability , probability of data having a particular class

![](https://i.ytimg.com/vi/eho8xH3E6mE/hqdefault.jpg)
