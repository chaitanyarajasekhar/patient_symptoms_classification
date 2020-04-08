# Patient Symptoms and Drug text classification

There are two files in this project, both of them use different approaches.

- medical_symptoms_text_classification.ipynb
- using_tensorflow_pretrained_tex_embeddings.ipynb

I have used ipython notebooks for better code readability.

The overview of the approaches is described below.

1. Load the data and perform some preprocessing to remove some unusable data.

2. Since this is a classification problem examine the class distribution. In the given data 10 classes have the highest occurrence. Based on the class distribution choose a strategy to reduce the data. 

3. Create numeric labels for the alpha numeric classes so that they can be used with any machine learning algorithms. Similarly, the the text needs to be converted into array of numbers to work with machine learning algorithms. This can be done by back of words method in the first file or use a pretrained embedding model.

4. Split the data into train and test data.

5. Train any valid machine learning classification algorithms with training data and test the performance of the classifier with the test data.

6. Generate confusion matrix to visualize the classifier performance.

Since this project has sensitive data more information about it is not disclosed in the file.
