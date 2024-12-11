# HuggingFace News Classification

📰 A news article classification project using HuggingFace Transformers and the AG_News dataset. This project demonstrates advanced training techniques to mitigate overfitting and achieve high accuracy.

## 💡 Project Overview
This project showcases:
- Implementation of a news classification model using HuggingFace's BERT.
- Mitigation of overfitting through Dropout, Early Stopping, and Learning Rate adjustments.
- Accurate predictions for test data, including a real-world example.

## 🔧 Key Skills and Tools
- HuggingFace Transformers
- AG_News Dataset
- Advanced Model Training Techniques (Dropout, Early Stopping, Learning Rate Scheduling)
- Multi-class Classification with CrossEntropyLoss

## 🚀 How to Use
1. Clone the repository:  
```bash
   git clone https://github.com/Choi0619/HuggingFace-News-Classification.git
   ```
2. Install required libraries:  
```bash
   pip install transformers datasets evaluate accelerate scikit-learn
   ```
3. Open the Jupyter Notebook:  
```bash
   jupyter notebook HuggingFace_AG_News_Classification.ipynb
   ```

## 🔄 Modifications and Solutions
### Observed Issue:
During initial training, **Training Loss** decreased, but **Validation Loss** increased, leading to overfitting. Accuracy also stagnated or decreased after a few epochs.

### Solutions:
- **Dropout**: Randomly deactivates neurons during training to reduce model complexity.
- **Early Stopping**: Halts training when validation performance does not improve.
- **Learning Rate Adjustment**: Slowed down the learning rate for better convergence.

## 📊 Results
- **Test Accuracy**: 91.43%  
  - The model achieved **91.43% accuracy** on the test dataset.
- **Prediction Example**:  
  - For the provided news article, the model classified it as **LABEL_0** with **98.66% confidence**.

## 👤 Author
[Gyuhwan Choi](https://github.com/Choi0619)
