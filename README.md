# Political Bias Detection: Mapping Media Perspectives with AI

This project leverages deep learning to classify news articles by political bias, aiming to enhance media literacy and transparency. Our multiclass model accurately identifies bias across the political spectrum — from left to right — using NLP techniques and performance benchmarking.

---

## 🔍 Project Highlights

- **Deep Learning Model (TensorFlow/Keras)**  
  Achieved **83% test accuracy** in a 5-class classification task.
  
- **Baseline Comparison**  
  Logistic Regression implemented as a benchmark model to evaluate gains from deep learning.

- **Comprehensive Evaluation**  
  Includes **classification reports**, **confusion matrices**, and **precision-recall curves** to assess model performance across all classes.

- **Smart Preprocessing Pipeline**  
  Tokenization, lowercasing, and vectorization for clean and effective input.

- **Key Insight**  
  Class imbalance influenced some model misclassifications — prompting further tuning.

---

## 🗂️ Classes Defined

- **Class 0** – Left  
- **Class 1** – Center-Left  
- **Class 2** – Center  
- **Class 3** – Lean Right  
- **Class 4** – Right

---

## 🧪 Exploratory Insights

- **Class Distribution**: Uneven, with Center and Center-Left dominating.
- **Text Length**: Average word count consistent across classes — good baseline for modeling.
- **Confusion Matrix**: Most errors occurred between adjacent political leanings (e.g., Left vs. Center-Left).
- **Precision-Recall**: Lower performance on minority classes (Left & Right) — classic sign of imbalance.

---

## 📈 Model Results

- **Deep Learning (TF/Keras)**  
  83% accuracy with clear class separation in embeddings.

- **Logistic Regression**  
  Served as a useful baseline with significantly lower accuracy (~70%).

- **Top Improvements from DL Model**:  
  - Better handling of contextual word relationships  
  - Less confusion between Center and polar classes

---

## ✅ Recommendations

- **Class Balancing**: Implement oversampling or weighted loss functions.
- **Model Monitoring**: Track performance drift as media language evolves.
- **User Interface**: Build a simple input interface to analyze articles in real-time.
- **Explainability**: Add attention maps or SHAP values to show **why** an article was classified a certain way.

---

## ⚙️ Tools Used

- Python (Pandas, NumPy, Scikit-learn)  
- TensorFlow & Keras (Deep Learning)  
- Matplotlib & Seaborn (Visualizations)  
- Jupyter Notebook (Exploration & Prototyping)  
- SciPy (Statistical Analysis)  

---

## 💻 Getting Started

1. Clone the repo:
   ```bash
   git clone (https://github.com/quadrillionaiire/Political-Bias-Detection.git)
   cd political-bias-classifier
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. (Optional) Run model training notebook or launch the analysis report.

---

## 📊 Visual Highlights

- Confusion Matrix by Class  
- Precision-Recall Curves  
- Word Clouds for Each Bias Category  
- Training & Validation Accuracy/Loss Trends

---

## 🧾 Non-Technical Summary

This AI model reads news content and predicts political leaning — Left, Center, or Right. It helps readers understand bias in the media and brings transparency to journalism using deep learning and natural language processing.

---

## 🧠 Technical Summary

We trained a deep neural network to classify political bias from text using a labeled dataset. After cleaning and vectorizing the text, we built and evaluated both baseline (logistic regression) and advanced (deep learning) models. Despite class imbalance, our top model achieved 83% accuracy and is primed for real-world application.

---
