# Sentiment Analysis on Movie Reviews

## Overview
This project uses a machine learning model to classify movie reviews as positive or negative using the "IMDB Dataset of 50k Movie Reviews" from Kaggle.

## Dataset
The dataset used in this project can be found here:  
[IMDB Dataset of 50k Movie Reviews](https://www.kaggle.com/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)

## Features
- **Text Preprocessing**: Tokenization, stopword removal, punctuation removal.
- **Vectorization**: Transformation using CountVectorizer and TfidfVectorizer.
- **Model Training**: Logistic Regression, Support Vector Machines (SVM), and Random Forest.
- **Evaluation**: Accuracy, confusion matrix, and classification report.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/lokesh-aj/Sentiment-Analysis-on-Movie-Reviews.git
   cd Sentiment-Analysis-on-Movie-Reviews
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Open the Jupyter Notebook:
   ```bash
   jupyter notebook Model.ipynb
   ```
2. Run all the cells to train and evaluate the model.
3. Test the model with a sample review:
   ```python
   pre = LRmodel.predict(["This movie was fantastic!"])
   print(pre)
   ```

## Technologies Used
- Python
- Scikit-learn
- Spacy
- Pandas & NumPy
- Matplotlib

## Contributing
Contributions are welcome! Fork the repository and submit a pull request with improvements.

## License
This project is licensed under the MIT License.

## Contact
For any queries, reach out at [lokeshvyas.prof@gmail.com](mailto:lokeshvyas.prof@gmail.com).

