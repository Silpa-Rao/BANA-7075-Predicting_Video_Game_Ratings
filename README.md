# BANA-7075-Predicting_Video_Game_Ratings
This project aims to build an ML system to predict video game ratings using metadata (genre, platform, release year, user/critic scores). 

# 🎮 Predicting Video Game Ratings

This repository contains the source code, notebooks, and presentation for a machine learning project aimed at predicting video game ratings based on metadata. The project was developed as part of the **BANA-7075** coursework at the University of Cincinnati.

---

## 📌 Project Overview

The primary goal of this project is to predict critic ratings for video games using structured metadata. By leveraging machine learning techniques, we aim to uncover the most influential factors contributing to a game’s rating and help guide publishers and developers in data-driven decision-making.

---

## 📂 Dataset Reference

**Source**: [Games Metadata and Ratings (5k+ dataset)](https://www.kaggle.com/datasets/bhanuprakashchegondi/games-metadata-and-ratings-5k-dataset)  
**Author**: Bhanu Prakash Chegondi  
The dataset contains 5,000+ video games and includes:
- Game title, platform, genre, release year
- Developer and publisher
- Critic scores and user review metrics

---

## 🧱 System Architecture


- **Data Collection**: Sourced structured game metadata from Kaggle
- **Preprocessing**: Cleaned data, handled missing values, transformed categorical fields
- **Feature Engineering**: Extracted relevant features such as platform type, normalized scores, one-hot encoding
- **Modeling**: Used tree-based models for prediction (e.g., Random Forest, XGBoost)
- **Evaluation**: Measured model accuracy using RMSE and MAE
- **Visualization**: Created visual summaries and insights for stakeholders

---

## ⚙️ Technologies Used

- **Languages**: Python
- **Libraries**: Pandas, NumPy, Scikit-learn, XGBoost, Matplotlib, Seaborn
- **Tools**: Jupyter Notebooks, Git, PowerPoint

---

## 📈 Modeling Highlights

- **XGBoost** delivered the best performance due to its ability to handle non-linear patterns
- **Feature Importance** showed critic reviews, release year, and platform as key predictors
- Handled categorical encoding with one-hot and frequency-based techniques
- Future gains can be achieved by incorporating game descriptions and review texts using NLP

---

## 🧪 Key Challenges

- High cardinality in fields like *developer* and *platform*
- Incomplete or biased entries in review scores
- Limited computational resources for advanced tuning
- Ensuring full reproducibility and modular coding

---

## 🚀 Future Enhancements

- Add **sentiment analysis** from user reviews using NLP
- Use **embeddings** to encode high-cardinality categorical variables
- Deploy using **Flask** or **FastAPI** for real-time usage
- Build a **CI/CD pipeline** to automate model retraining and monitoring

---

## 📽️ Demo

The final presentation includes a visual walkthrough of the pipeline, model performance, and key findings.  
📂 [Predicting_Video_Game_Ratings_Presentation.pptx](./Predicting_Video_Game_Ratings_Presentation.pptx)


---

## 📁 Repository Structure

---

## 👥 Contributors

**Silpa Prakash Rao**   
**Vivek**   
**Supriya**   
**Suraj**   
**Vanshika**   

MS Business Analytics | MSIS | University of Cincinnati  
Roles: Data Preparation, Modeling, Evaluation, and Presentation

---

## 📄 License

This project is intended for educational use only.  
Dataset provided by [Bhanu Prakash Chegondi on Kaggle](https://www.kaggle.com/datasets/bhanuprakashchegondi/games-metadata-and-ratings-5k-dataset).

