# NLP-Project-3_Data-Annotation-and-zero-shot-evaluation
-Data Annotaion and Analysis of Fine-tuned dehatebert-mono-english model on the Uncleaned and Cleaned data of the hatespeech


## Project Overview
This project analyses and evalutaes cohen's kappa between two annotators in the data and then detects hate/offensive speech in tweets using the **Twitter-roberta-base-sentiment** model. Tweets were collected from **X (formerly Twitter)** using various hashtags like `#USElection2024`, `#cancerfree`, `#positivity`, `#funny`, `#racist`, and others. The data was annotated to classify tweets as **Hate/Offensive (1)** or **Neutral (0)**.

## Data Source
- Data collected from **X (formerly Twitter)** using hashtags and it's search:
  - `#USElection2024`, `#cancerfree`, `#positivity`, `#peace`, `#cr7`, `#funny`, `#appreciation`, `#racist`
- Annotated by:
  - **Annotator-1**: Me
  - **Annotator-2**: Sriram Theerdh Manikyala 
- **Gold labels**: Based on the best label from both annotators.

## Model
- **Model**: [Twitter-roberta-base-sentiment](https://huggingface.co/cardiffnlp/twitter-roberta-base-sentiment)

## Instructions

1. **Run the - **File**: `1.Data_cleaning_and_basic_analysis.ipynb`:
   
2. **Run the  - **File**: `2.training_and_evaluation.ipynb`:
  

3. **Refer to the Documentation**:
   - Additional details on my entire project is mentioned detailedly in my documentation.


