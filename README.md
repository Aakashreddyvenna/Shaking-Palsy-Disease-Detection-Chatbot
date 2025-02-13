Here's an improved **GitHub project description** with **XGBoost results** and more details about the chatbot:  

---

# **Shaking-Palsy Disease Detection Chatbot**  

## 📌 Overview  
This project is an **AI-powered chatbot** designed to assist in the **early detection of Parkinson’s disease (Shaking Palsy)** by analyzing variations in **voice pitch**. The chatbot interacts with users to collect voice-related input and utilizes machine learning models to predict the likelihood of Parkinson’s disease.  

### 🗣️ How the Chatbot Works  
- The **chatbot** serves as a virtual assistant for individuals experiencing **early symptoms** of Parkinson’s disease.  
- It **collects and processes voice-related features** such as **MDVP, jitter, and shimmer**.  
- Uses **machine learning models** to analyze the data and provide **risk assessments**.  
- Offers **basic guidance** based on the prediction results, helping users decide if they should seek medical consultation.  

## 🚀 Features  
✅ **Early Detection** – Uses voice pitch analysis to identify early-stage Parkinson’s disease.  
✅ **AI-Driven Predictions** – Employs various **machine learning models** for accurate diagnosis.  
✅ **Chatbot Interface** – Provides an interactive experience for users to **input data easily**.  
✅ **High Accuracy** – **XGBoost model achieves 100% accuracy**, ensuring **reliable results**.  

## 🔬 Machine Learning Models & Performance  
| Model                 | Accuracy  | Precision | Recall  | F1-Score |
|----------------------|-----------|-----------|---------|---------|
| Logistic Regression  | 88.89%    | 100.00%   | 94.12%  | 89.74%  |
| SVM (Linear)        | 88.89%    | 100.00%   | 94.12%  | 89.74%  |
| Decision Tree       | 93.94%    | 96.88%    | 95.38%  | 92.31%  |
| Random Forest      | 93.94%    | 96.88%    | 95.38%  | 92.31%  |
| K-Nearest Neighbors | 94.12%    | 100.00%   | 96.97%  | 94.87%  |
| **XGBoost**         | **100.00%** | **96.67%** | **98.31%** | **97.43%** |

## 🛠️ Technologies Used  
- **Python** (Core Language)  
- **Machine Learning** (scikit-learn, XGBoost)  
- **Natural Language Processing (NLP)** (For chatbot interactions)  
- **Data Processing** (NumPy, Pandas)  
- **Visualization** (Matplotlib, Seaborn)  
- **Flask/FastAPI** (For chatbot API, if applicable)  

## 📥 Installation & Usage  
1. **Clone the repository**  
   ```bash
   git clone [https://github.com/Aakashreddyvenna/Shaking-Palsy-Disease-Detection-Chatbot
   cd Shaking-Palsy-Disease-Detection-Chatbot]
   ```
2. **Install dependencies**  
   ```bash
   pip install -r requirements.txt
   ```
3. **Run the chatbot and detection model**  
   ```bash
   python main.py
   ```
4. **Interact with the chatbot** to input voice pitch data and receive predictions.  

## 📌 Future Enhancements  
🚀 **Integrate Deep Learning models (LSTMs, CNNs) for enhanced prediction.**  
🚀 **Deploy the chatbot as a web/mobile application for wider accessibility.**  
🚀 **Collect and analyze real-world patient data for improved accuracy.**  

## 🤝 Contributing  
Want to contribute? Feel free to submit a **pull request** or raise an **issue**!  

---

This **version emphasizes** both the **machine learning accuracy** and the **chatbot's role** in the project. Let me know if you'd like any refinements! 🚀😃
