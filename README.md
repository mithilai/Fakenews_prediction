# Fake News Prediction

This project was my first attempt at Natural Language Processing (NLP), where I explored text preprocessing, feature extraction, and classification techniques to predict fake news.

## Project Overview
The dataset used in this project, which is shared in the repository, includes the following columns:
- **id**: Unique identifier for each entry
- **label**: Indicates whether the news is real or fake
- **author**: Author of the news article
- **news**: Content of the news article

### Preprocessing Steps
1. **Data Cleaning**: Removed the `id` column as it didn't contribute to the prediction task.
2. **Text Merging**: Combined the `author` and `news` columns to create a single text feature.
3. **Stop Words Removal**: Filtered out common stop words.
4. **Stemming**: Applied stemming to reduce words to their root forms.
5. **Feature Extraction**: Converted the cleaned text into a TF-IDF matrix for model training.

### Model Training
I trained a Logistic Regression model on this preprocessed data. The model achieved:
- **Train Accuracy**: ~99%
- **Test Accuracy**: ~53%

While this indicates overfitting, I focused on learning the NLP pipeline rather than tuning the model for this project.

## Learning Outcomes
This project helped me build a foundational understanding of NLP processes like text preprocessing, TF-IDF vectorization, and logistic regression for text classification.

---

Feel free to try out the project, and any feedback is welcome!
