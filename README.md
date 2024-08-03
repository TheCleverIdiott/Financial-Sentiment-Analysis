### Dataset = https://www.kaggle.com/datasets/sbhatti/financial-sentiment-analysis


# Financial Sentiment Analysis using Machine Learning

This project aims to analyze the sentiment of financial news articles and statements using machine learning models. The primary goal is to classify sentiments into positive, negative, or neutral categories.

## Project Structure

- **Data Preprocessing**: Load and preprocess the dataset, including cleaning text data.
- **Exploratory Data Analysis (EDA)**: Visualize the data distribution and relationships.
- **Model Training**: Train a Bidirectional LSTM model to classify sentiments.
- **Evaluation**: Evaluate the model's performance using various metrics and visualize the results.

## Dependencies

Ensure you have the following dependencies installed to run the project:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `text_hammer`
- `nltk`
- `keras`
- `tensorflow`
- `tqdm`

You can install the required packages using the following command:

```sh
pip install -r requirements.txt
```

## requirements.txt

```plaintext
pandas
numpy
matplotlib
seaborn
text_hammer
nltk
keras
tensorflow
tqdm
```

## Data

The dataset used in this project is stored in a CSV file and contains columns for sentences and their corresponding sentiments.

## Steps to Run the Project

1. **Clone the repository**:
    ```sh
    git clone https://github.com/YourUsername/Financial_Sentiment_Analysis.git
    cd Financial_Sentiment_Analysis
    ```

2. **Install dependencies**:
    ```sh
    pip install -r requirements.txt
    ```

3. **Run the Jupyter notebook**:
    Open `Financial_Sentiment_Analysis_ML.ipynb` in Jupyter Notebook or JupyterLab and execute the cells step-by-step.

## Project Details

- **Data Preprocessing**:
  - Convert text to lowercase.
  - Expand contractions.
  - Remove emails, HTML tags, stopwords, special characters, and accented characters.
  - Tokenize and pad sequences.

- **EDA**:
  - Visualize sentiment distribution using histograms.
  - Analyze word frequency and sentence length distribution.

- **Model Training**:
  - Use a Bidirectional LSTM model with embedding, dropout, and dense layers.
  - Train the model with early stopping and model checkpointing.

- **Evaluation**:
  - Plot training and validation accuracy and loss.
  - Generate a classification report.

## Results

The model's performance is evaluated using accuracy, precision, recall, and F1-score. Visualizations of the model's training process and the most frequent words in the dataset are provided.

## Contributing

Feel free to fork this repository, make improvements, and create pull requests. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
