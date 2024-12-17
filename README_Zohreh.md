# YouTube Viral Video Prediction

## Project Overview 🎯
A machine learning project developed in collaboration with Google engineers to predict viral potential of YouTube videos using historical engagement metrics and video metadata. This project aims to help identify trending videos using various ML approaches, supporting YouTube's content recommendation systems.

### Objective
Build and evaluate machine learning models to forecast video virality by analyzing:
* Previous days' engagement metrics
* Video metadata
* Historical trending patterns
* User interaction data (views, shares, comments, likes)

## Technologies Used 🛠️

### Core Technologies
* **Programming Language:** Python
* **Data Processing:** Pandas, NumPy
* **Machine Learning:** Scikit-learn, TensorFlow/Keras
* **Data Visualization:** Matplotlib, Seaborn
* **Text Processing:** NLTK (Natural Language Toolkit)
* **Development Environment:** Google Colab

## Model Implemented 📊
### Random Forest
* Ensemble method for improved prediction accuracy
* Reduces overfitting compared to single decision trees

## Data Processing 📝

### Preprocessing Steps
* Data splitting by time periods (2020-2024)
* Feature engineering and transformation
* Logarithmic transformation of engagement metrics
* One-hot encoding for categorical variables
* Text processing for video titles and descriptions
* Missing value handling
* Feature normalization

## Dataset 🗂️
The project uses the YouTube Trending Videos Dataset from Kaggle, which includes:

* Daily trending video statistics
* Video metadata (title, description, tags)
* Engagement metrics (views, likes, comments)
* Category information
* Publishing channel data

## Key Features 📈
* Time-series based prediction
* Multi-model comparison and evaluation
* Trend analysis across different time periods
* Feature importance analysis
* Engagement metric correlation studies
* Category-based performance analysis

## Model Evaluation 🔍
* Learning curves for training and test data
* Validation set for hyperparameter tuning
* Scatter plots for regression analysis
* Performance metrics comparison across models
* Cross-validation results

## Collaborators 🤝
Project developed under the mentorship of Google engineers as part of the Google AI Studio Challenge Project.

## Resources 📚
* [YouTube Data API documentation](https://developers.google.com/youtube/v3)
* [Kaggle YouTube Trending Videos Dataset](https://www.kaggle.com/datasets/rsrishav/youtube-trending-video-dataset)
* Google Colab notebooks
* Python library documentation

## Future Improvements 🚀
1. Integration of additional metadata features
2. Real-time prediction capabilities
3. Enhanced text analysis of video descriptions
4. Advanced feature engineering
5. Model optimization for specific video categories

## License 📄
[MIT License](LICENSE)

## Acknowledgments 👥

Special thanks to our Google mentors:

* **Anushya Subbiah** - *Software Engineer*
* **Sally Goldman** - *Research Scientist*
* **Vivian Yang** - *Software Engineer*

For their guidance and support throughout the project.

---

### Getting Started

```bash
# Clone the repository
git clone https://github.com/yourusername/youtube-viral-prediction.git

# Install required packages
pip install -r requirements.txt

# Run the Jupyter notebook
jupyter notebook
```

### Project Structure
```
youtube-viral-prediction/
│
├── data/                    # Dataset files
├── notebooks/              # Jupyter notebooks
├── src/                    # Source code
├── models/                 # Trained models
├── requirements.txt        # Dependencies
└── README.md              # Project documentation
```

### Contact
For any questions or feedback, please open an issue in this repository or contact the project maintainers.

---
**Note:** This project was developed as part of the Google AI Studio Challenge Project, focusing on machine learning applications in video trend prediction.

