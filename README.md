Google Colab notebook link: **https://drive.google.com/drive/folders/1LE16HVWnezuFSzdQaACjpgO588GHjVMR?usp=share_link**

The goal of this activity is to create a tool for the fictional nonprofit foundation Alphabet Soup that can help it select the applicants for funding with the best chance of success in their ventures. It uses machine learning and neural networks to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup. The data comes from a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years.

**Step 1: Preprocess the Data**
- Used Pandas and scikit-learn to preprocess the dataset
    - Identified targets and features
    - Encoded categorical variables
    - Split data into training and testing
    - Scaled data

**Step 2: Compile, Train, and Evaluate the Model**
- Used TensorFlow to design a neural network to create a binary classification model that can predict if an Alphabet Soup-funded organization will be successful based on the features in the dataset
  - Assigned the number of input features and nodes for each layer using TensorFlow and Keras
  - Created hidden layer and output layer
  - Trained the model
  - Evaluated the model to determine the loss and accuracy

**Step 3: Optimize the Model**
- Optimized the model to achieve a target predictive accuracy higher than 75%
    - Adjusted the input data to ensure that no variables or outliers were causing confusion in the model
