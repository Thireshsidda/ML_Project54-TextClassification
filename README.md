# ML_Project54-TextClassification

### Text Classification Project README

### Overview
This project focuses on classifying consumer complaints into different product categories using deep learning techniques. The dataset used for this project is the "Consumer Complaints" dataset, which contains various fields such as product, issue, consumer complaint narrative, etc. The objective is to develop a model that can accurately predict the product category based on the text of the consumer complaint narrative.

### Project Structure
#### The project follows the below structure:

##### Data Preparation:

The dataset is loaded from the provided CSV file (Consumer_Complaints.csv).

Data cleaning is performed to remove null values and irrelevant columns.

Train-test split is done to create training and validation datasets.

##### Text Preprocessing:

Text data is tokenized and converted into sequences.

Padding is applied to ensure all sequences have the same length.

Word embeddings are loaded and used to represent words numerically.

##### Model Building:
A deep learning model architecture is defined using Keras.

The model consists of an embedding layer, LSTM layer, and dense layers.

GloVe word embeddings are used as pre-trained word vectors.

##### Model Training:

The model is trained on the training data with a defined number of epochs and batch size.

Training progress is monitored using validation data.

##### Model Evaluation:
The trained model is evaluated on the validation dataset.

Evaluation metrics such as accuracy, precision, recall, and F1-score are calculated for each product category.

##### Analysis:
The predictions are analyzed to understand the model's performance.

Confusion matrix is generated to visualize the classification results.

##### Results Visualization:
Training and validation accuracy/loss plots are created to visualize the model's learning progress over epochs.

### How to Run
Clone Repository: Clone this repository to your local machine.

Install Dependencies: Ensure all dependencies mentioned in the requirements.txt file are installed.

Download Pre-trained Embeddings: Download the GloVe word embeddings file (glove.6B.50d.txt.gz) and place it in the project directory.

Run Notebook: Open and run the text_classification.ipynb notebook using Jupyter Notebook or any compatible platform.

Review Results: After running the notebook, review the model's performance metrics, analysis, and visualization plots.

### Notes
Experiment with different hyperparameters, architectures, and preprocessing techniques to improve model performance.

Ensure that the dataset file (Consumer_Complaints.csv) and the pre-trained word embeddings file (glove.6B.50d.txt.gz) are in the project directory.

Customize the code and parameters as per your requirements and resources.

Feel free to reach out for any questions or assistance.
