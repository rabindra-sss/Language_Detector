# Language Detection Model
The model is built using Python and NLP libraries
<br/>
## Dataset
The dataset contains text samples from 17 different languages. It is imbalanced, with a higher number of English samples. To address this, down sampling was applied to create a balanced dataset.
## Model Training
For preprocessing the text data, we converted it to lowercase and removed special characters, punctuation, and stop words. Features are extracted using Bag of Words and N-grams. The dataset is then split into training and testing sets, and the models (Naive Bayes and Logistic Regression) are trained on the training data.
## Results
The Logistic Regression model achieved a language detection accuracy of 97.26%.
