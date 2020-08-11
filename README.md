# Binary_Classification
Cleaning and Dealing with im-balanced dataset using smote and achieving good results on both train-validation datasets

# Thoughts and observations:
all my thougths and observations are discussed through the process in the notebook

# Side-notes:
<ul>
  <li>Variables 17,14 are the same variable but scaled</li>
  <li>Variables 4,5 are the same variable but shifted</li>
  <li>Variables 19 are the same as the label but they are not the same in the validation set</li>
   <li>After PCA, we can drop more than 80% of the features and still have >90% of the variance of the data!</li>
  <li>The data is imbalanced so the accuarcy metric is not the best metric , we should care for F-beta score</li>
</ul>

# To-Do

<ul>
  <li>Adding microservice for prediction task (currently learning how microservices work)</li>
  <li>Getting more insights from the data</li>
</ul>
