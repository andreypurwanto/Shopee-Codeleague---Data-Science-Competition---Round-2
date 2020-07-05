# Shopee Codeleague - Data Science Competition - Round 2

## Task
In this competition, a multiple image classification model needs to be built. There are ~100k images within 42 different categories, including essential medical tools like masks, protective suits and thermometers, home & living products like air-conditioner and fashion products like T-shirts, rings, etc. For the data security purpose the category names will be desensitized. The evaluation metrics is top-1 accuracy.

## Approach
We are using 4 trained model by tensorflow (Inception ResnetV2, NesNetLarge, Efficient B7 and Effcient B6). We train and fine tune each of the model, and finally ensemble them using knn classifiers.

## Final Submission
Rank : 74
<br /> 
Test Accuracy : 0.8110
