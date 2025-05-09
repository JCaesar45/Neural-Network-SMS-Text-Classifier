````markdown

# Neural Network SMS Text Classifier

Welcome to the **Neural Network SMS Text Classifier** project! In this guide, you'll build a machine learning model that classifies SMS messages as either "ham" (normal message) or "spam" (advertisement or unsolicited message). Follow the instructions below to complete the project using Google Colaboratory.

## Project Setup

### Step 1: Create a Google Colab Notebook

1. Visit the provided [Google Colaboratory link](https://colab.research.google.com).
2. Make a copy of the notebook into your own Google Drive or download it locally.

### Step 2: Enable Link Sharing (if using Google Colab)

If you're submitting a Google Colaboratory link, ensure you enable link sharing:

1. Click the "Share" button in the upper right corner of the notebook.
2. Under "Get Link", change the option to "Anyone with the link".
3. Copy the shareable link for submission.

## Project Instructions

### Dataset

You will be using the **SMS Spam Collection dataset** which is already divided into training and testing sets. Make sure to import the dataset correctly in your notebook.

### Function Definition

You need to implement a function named `predict_message`. This function will take a string message as input and will output a list containing:

1. A probability score (number between 0 and 1) indicating the likelihood of the message being "ham" (0) or "spam" (1).
2. The classification result as either the string "ham" or "spam".

### Implementation Steps

1. **Import the necessary libraries** and data in the first two cells of the notebook. 
2. **Create and train your machine learning model** using the training data. 
3. **Define the `predict_message` function** according to the specifications.
4. **Test your model** with the provided test cell at the end of the notebook.

### Example Code Skeleton

```python
# Cell 1: Import Libraries and Load Data
import pandas as pd
from sklearn.model_selection import train_test_split
from sklearn.feature_extraction.text import CountVectorizer
from sklearn.naive_bayes import MultinomialNB
import numpy as np

# Load the SMS Spam Collection dataset
data = pd.read_csv('path/to/dataset.csv') # Make sure to provide the correct path
# Split data into training and testing datasets

# Cell 2: Create and Train Your Model
# Your code here: Preprocess, vectorize, and train the model

# Cell 3: Define `predict_message` Function
def predict_message(message):
    # Your model prediction logic here
    # Return a list: [likelihood, 'ham'/'spam']
    pass

# Cell 4: Test Your Model
# Your testing code here
```

## Additional Resources

During the project, you may need to refer to video challenges or seek additional learning materials specific to machine learning and natural language processing. Be proactive in exploring resources similar to real-world project scenarios.


Good luck, and happy coding!
