# NLP-Project-3_Data-Annotation-and-zero-shot-evaluation
-Data Annotaion and Analysis of Fine-tuned dehatebert-mono-english model on the Uncleaned and Cleaned data of the hatespeech


## Project Overview
This project detects hate speech in tweets using the **Twitter-roBERTa-base-sentiment** model. Tweets were collected from **X (formerly Twitter)** using various hashtags like `#USElection2024`, `#cancerfree`, `#positivity`, `#funny`, `#racist`, and others. The data was annotated to classify tweets as **Hate/Offensive (1)** or **Neutral (0)**.

## Data Source
- Data collected from **X (formerly Twitter)** using hashtags:
  - `#USElection2024`, `#cancerfree`, `#positivity`, `#peace`, `#cr7`, `#funny`, `#appreciation`, `#racist`
- Annotated by:
  - **Annotator-1**: Me
  - **Annotator-2**: Sriram Theerdh Manikyala (roommate)
- **Gold labels**: Based on the best label from both annotators.

## Model
- **Model**: [Twitter-roBERTa-base-sentiment](https://huggingface.co/cardiffnlp/twitter-roberta-base-sentiment)
- **Pre-trained** for sentiment analysis, used here for detecting hate speech.

## Instructions

1. **Run the Data Cleaning and Analysis Notebook**:
   - **File**: `1.Data_cleaning_and_basic_analysis.ipynb`
   - This notebook performs data cleaning (removes URLs, mentions, special characters) and analyzes the dataset (Cohen's Kappa score for inter-annotator agreement).

2. **Run the Model Training and Evaluation Notebook**:
   - **File**: `2.training_and_evaluation.ipynb`
   - This notebook evaluates the performance of the model on both cleaned and uncleaned datasets using **Accuracy** and **F1 Score**.

3. **Refer to the Documentation**:
   - Additional details on methodology, data collection, and model evaluation are provided in the repository’s documentation.

## Conclusion
This project demonstrates the use of **Twitter-roBERTa-base-sentiment** for hate speech detection and shows how text cleaning improves model performance.

## License
This project is licensed under the MIT License.
