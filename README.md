# sampling
In this python code, we have used sampling techniques on a credit card fraud detection dataset and then applied various ML models on the dataset to find out which Model,sampling technique combination gives us the best accuracy.

Following 5 sampling Techniques were used:

1.Random Under Sampler 
2.Random Over Sampler 
3.TOMEK links
4.Convenience sampling
5.Simple Random Sampling

The Sample size was calculates using the following formula: n = Z^2(p(1 – p)/m^2) where: n = sample size Z = z-value (for 95% confidence interval, Z = 1.96) p = proportion of the minority class (taken as 0.5 for a balanced dataset) m = margin of error (taken as 0.1 for a sample size of 1000)

Following 5 models were applied on the sampled dataset:

Logistic Regression (M1)
Decision Tree Classifier (M2)
Random Forest Classifier (M3)
KNeighborsClassifier(M4)
GaussianNB (M5)

On execution of the code, following results were obtained: The cells of the table represent accuracy of the applied model using the respective sampling technique.

![image](https://user-images.githubusercontent.com/72308693/219977583-84068d7f-e116-41f0-a81f-53cecdd9ade0.png)

As we can see from the table the Maximum Accuracy obtained is of 99.35%.
