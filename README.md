# MachineLearning_RNA_motif_prediction
This is a course project with a main objective to apply the knowledge gained from the course Introduction to Machine Learning. The given project explores both supervised and unsupervised machine learning algorithms to train the models to make predictions on the given data regarding RNA motif’s structure. 

Keras neural network classifier, Decision Tree classifier and Random Forest classifier under supervised learning and KMeans clustering under unsupervised learning were employed.

Major steps of training process include data acquisition, exploration and visualization of the data to help in data processing, splitting the datasets, converting the labels into one-hot-encode vectors, training the model with training sets, making predictions on validation datasets, comparing the accuracy parameters to understand under/overfitting, tuning the model with hyperparameters and then refitting the best model against training data followed by making predictions on test data.

The calculated evaluation metrics such as accuracy, precision score, recall, F1 score and AUC ROC scores of all the supervised models are presented in a tabular form for better comparison.
For Kmeans clustering, silhouette score of the clusters is provided as evaluation metric.

For code refer RNA_motifs_prediction.ipynb
