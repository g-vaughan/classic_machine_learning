# Classic Machine Learning

This repository is where I document my journey of learning, experimenting, and applying machine learning techniques to real-world datasets. It's less of a polished product and more of a place to track my growth, explore new ideas, and build a portfolio of hands-on projects.

## Notebooks:
1) 📽️⭐ Recommender Systems - Content and Collaborative Filtering (2025)
   
   This notebook implements and evaluates several recommendation approaches using a movie dataset. It includes popularity-based filtering by recommending all-time top-rated and currently trending movies based on IMDB’s Bayesian average formula. Content-based filtering is performed by creating a combined text “soup” from genres, credits, and keywords vectorised with CountVectorizer, alongside TF-IDF vectorised movie descriptions, with adjustable feature weighting. Collaborative filtering is implemented by training an SVD matrix factorisation model on user ratings to capture latent user and movie factors. Together, these methods demonstrate practical techniques for building personalised recommendation systems.
   
2) ❤️‍🩹**Predicting Heart Failure** - Classic ML, Binary classification (2025)
   
     This notebook aims to predict the likelihood of heart failure using clinical patient data. It explores classic machine learning algorithms implemented with Scikit-learn and provides explanations of their advantages, limitations, and key parameters. The final model, built with XGBoost, achieved an accuracy of 85% on the training set and 90% on the holdout set, indicating strong performance without signs of overfitting.
   

## Reports:
1) 🎄👕**Finding festivity in knitwear** - CNNs for image classification (2023)
   
   This report aims to train an image classification model to classify Christmas jumpers from everyday knitwear. Models explored include CNNs trained from scratch with a range of depths and pre-trained CNNs: AlexNet, VGG and GoogLeNet. To reduce overfitting, all models were run on a greyscale version of the dataset, with success. The final model was a fine-tuned version of the GoogLeNet architecture, achieving an accuracy of 93.67%. Exploring the misclassified examples exposed flaws in the dataset and suggests that this accuracy can be expected to change significantly when tested with a more robust dataset.
