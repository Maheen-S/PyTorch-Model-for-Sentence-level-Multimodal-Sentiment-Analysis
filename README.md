# PyTorch-Model-for-Sentence-level-Multimodal-Sentiment-Analysis
Task 01: Sentence-level Sentiment Analysis
This project focuses on developing a PyTorch model for conducting sentiment analysis on a dataset containing both textual captions and corresponding images. The model is designed to integrate both modalities to accurately predict sentiment labels at the sentence level.

Steps:
1. **Data Preparation**: The dataset is downloaded and preprocessed to clean captions, tokenize words, resize, and normalize images. Visual features are extracted using a pre-trained CNN model.
2. **Train/Test Split**: The dataset is split into training and testing sets using an 80-20 split. The majority of the data is used for training the model, while the rest is used for testing.
3. **Model Architecture**: A multimodal architecture is designed, incorporating components for processing text (e.g., LSTM, GRU) and extracting visual features (e.g., CNN).
4. **Training the Model**: The model is trained on the training dataset, with parameters like learning rate and batch size adjusted to optimize performance.
5. **Evaluation**: The trained model is used to predict sentiment labels for captions in the testing dataset. Performance is evaluated using metrics like accuracy, precision, recall, and F1-score.

Task 02: Word-level Sentiment Analysis
In this task, word-level sentiment analysis is conducted using a custom feature vector approach within a multimodal architecture.

Steps:
1. **Data Preparation**: The dataset is prepared for word-level sentiment analysis, ensuring each word is associated with its corresponding sentiment label.
2. **Model Architecture**: A multimodal architecture capable of performing word-level sentiment analysis is designed, with components for processing textual and visual information.
3. **Feature Vector Creation**: A custom feature vector creation method is implemented to capture relevant information about each word's sentiment.
4. **Training the Model**: The multimodal model is trained on the training dataset, with parameters adjusted as necessary.
5. **Evaluation**: The model's performance is evaluated on the testing dataset, comparing predictions to ground-truth sentiment labels.

Acknowledgements
- The dataset used in this project is sourced from [here](https://drive.google.com/file/d/1BW0DKYWtDdPMoVjuuCJ_E8TMDzSxjASb/view?usp=sharing).
- Portions of the code architecture are inspired by [PyTorch](https://pytorch.org/) documentation and tutorials.
