# 📰 News Category Classification (World, Sports, Business, Technology)

This project classifies news articles into **four categories**:  
- 🌍 World  
- 🏅 Sports  
- 💼 Business  
- 💻 Technology  

## 📊 Dataset
Dataset: `train.csv` (news articles with labels)  
- `label = 0 → World`  
- `label = 1 → Sports`  
- `label = 2 → Business`  
- `label = 3 → Technology`  

⚠️ The dataset is too large to store on GitHub. Download it separately and place it in the `data/` folder.  

## 🛠️ Features
- Text preprocessing: HTML removal, stopword removal, lemmatization, lowercasing
- Feature extraction: **TF-IDF** and **Word2Vec**
- Classical ML models: Logistic Regression, Random Forest, XGBoost, LightGBM
- Deep Learning models: **ANN, LSTM, GRU, Conv1D**
- WordClouds for category-specific keywords
- Final Conv1D model saved as `my_CONV1_model.keras`

## 🚀 How to Run
Clone repo:
```bash
git clone https://github.com/your-username/News-Category-Classification.git
cd News-Category-Classification
Install dependencies:

pip install -r requirements.txt


Run notebook:

jupyter notebook notebooks/NewsClassification.ipynb
