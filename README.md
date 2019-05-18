# Hate-Speech-Detector
## Machine Learning project deciding whether a tweet contains hatespeech 
<!DOCTYPE html>
<meta charset="utf-8">
<style>
svg {
  display: block;
  height: 400px;
  margin: 50px auto;
}
</style>
<svg viewBox="328 355 335 276" xmlns="http://www.w3.org/2000/svg">
  <path d="
    M 630, 425
    A 195, 195 0 0 1 331, 600
    A 142, 142 0 0 0 428, 570
    A  70,  70 0 0 1 370, 523
    A  70,  70 0 0 0 401, 521
    A  70,  70 0 0 1 344, 455
    A  70,  70 0 0 0 372, 460
    A  70,  70 0 0 1 354, 370
    A 195, 195 0 0 0 495, 442
    A  67,  67 0 0 1 611, 380
    A 117, 117 0 0 0 654, 363
    A  65,  65 0 0 1 623, 401
    A 117, 117 0 0 0 662, 390
    A  65,  65 0 0 1 630, 425
    Z"
    style="fill:#3BA9EE;"/>
</svg>

  Social media provides the chance to people of explaining themselves to whole world. When they want to express their thoughts, emotions, ideas etc. they use social media. In 2019, number of social media users is around 2.77 billion worldwide. Active Twitter users around the world is 330 million.
  Allowing people to express themselves freely may result in offensive behaviors to other people. It is reported that posts including hate speech in social media are increasing every year. Social media companies’ procedures on hate speech show difference in detail but generally they are based on complaints and deleted manually. Twitter has the lowest removal rate on hate speech.
  We want to implement hate speech detection that helps social media companies’ to handle them before the post without any complaint. Best result of this procedure will be people that may offended from the post will not see them and get offended or hurt. 

  Our aim on this project is to determine the intention of writing a tweet whether it contains a hate speech or not. Tweets are written in natural language and also they include shortcuts. Therefore, the models should understand the language used in each post and draw a conclusion from them. Additionally, since words could have different meanings depending on the context they are used, the model should understand the meaning of the posts not just by looking at each word but by analyzing it in the context. 
  We have used a dataset used in a paper which includes 85,966 English tweets: 32,119 labeled as hateful and 53,851 labeled as normal. To use this database, we mailed the author and got the permission of the author.
  For the first part of the preprocessing, we clean the raw data in the dataset, and for the second part which is feature extraction, 3 methods have been used: Pipeline, Word to Vector (Word2Vec), and Bag of Words (BoW). Also we have tried 9 different algorithms to train and test the data: 
- Naive Bayes Classification
- Support Vector Machine (SVM)
- Logistic Regression
- K Nearest Neighbor (kNN)
- Decision Tree Classification
- Random Forest Classification
- Gradient Boosting Classification
- XGBoost
- Recurrent Neural Network (RNN) 

The results after applying these methods have been compared to see which algorithm works best for this type of problem.
