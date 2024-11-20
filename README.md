# 🌹 **Classification of Leaf Diseases in Roses**  
## **Prediction of Leaf Diseases in Roses with ResNet50**

## 📋 **Objective**
The goal of this project is to develop a machine learning model capable of accurately predicting leaf diseases in rose plants. Early detection of leaf diseases is essential for maintaining the health and quality of rose cultivation, reducing pesticide use, and ensuring optimal yields. By using advanced image classification techniques, the project aims to provide reliable disease identification to assist growers in making timely decisions.

## 💡 **Why Use ResNet50?**
ResNet50 is chosen for this project due to several advantages:

- **Residual Learning**: Efficiently handles deeper networks by solving the vanishing gradient problem.
- **High Accuracy**: Well-suited for image classification with excellent accuracy even with moderately sized datasets.
- **Efficiency**: Provides a balance between model complexity and computational efficiency.
- **Transfer Learning**: Access to pre-trained models for rapid development and improved performance with limited data.

## 📊 **Project Workflow**
1. **Data Collection & Preparation**: Gathering and preparing rose leaf images for training and validation.
2. **Model Development**: Utilizing ResNet50 for leaf disease classification.
3. **Training & Evaluation**: Fine-tuning the model and evaluating performance metrics.
4. **Visualization & Analysis**: Analyzing results and visualizing prediction outcomes.
5. **Deployment**: Integrating the trained model for practical use.

## 📁 **Dataset**
The dataset used in this project includes images of rose leaves, categorized by different diseases. The data forms the foundation for training and testing the model.

- **Dataset Link**: [Access the Dataset Here]((https://www.kaggle.com/datasets/warcoder/rose-leaves-disease-detection)) 

## 📷 **Sample Images**
| Fresh Leaf | Black Spot Leaf | Downy Mildew |
|:------------:|:-------------:|:-------------:|
| ![Healthy](https://github.com/user-attachments/assets/80c07b0d-2b57-457a-9cab-595a83edf0a1)
 | ![Diseased](https://github.com/user-attachments/assets/7935a67f-0e57-49c2-a563-6918d4529ef7)
|
![Disease](https://github.com/user-attachments/assets/b5f6f09f-2a38-4ffd-8e2e-cc985702fc8b) |


## 🚀 **Technologies Used**
- **Programming Language**: Python
- **Deep Learning Framework**: PyTorch / TensorFlow / Keras
- **Model Architecture**: ResNet50
- **Visualization**: Matplotlib, Seaborn
- **Data Handling**: Pandas, NumPy

## 🛠️ **How to Use**
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/reponame.git
   cd reponame
   ```
2. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```
3. **Run Training**:
   ```bash
   python train_model.py
   ```
4. **Make Predictions**:
   ```bash
   python predict.py --image path_to_image.jpg
   ```

## 📊 **Results**
The project demonstrated high accuracy in predicting various leaf diseases using ResNet50 with PyTorch. Below are the key findings and classification metrics:

- **Overall Accuracy**: 94%
- **Detailed Classification Report**:

| Class          | Precision | Recall | F1-Score | Support |
|----------------|-----------|--------|----------|---------|
| Black Spot     | 0.98      | 0.88   | 0.93     | 50      |
| Downy Mildew   | 0.97      | 1.00   | 0.98     | 31      |
| Fresh Leaf     | 0.90      | 0.96   | 0.93     | 57      |

- **Macro Average**:
  - Precision: 0.95
  - Recall: 0.95
  - F1-Score: 0.95

- **Weighted Average**:
  - Precision: 0.94
  - Recall: 0.94
  - F1-Score: 0.94

The high precision and recall values indicate the model's strong ability to correctly identify various leaf conditions, particularly with **Downy Mildew**, which achieved a perfect recall score.

## 📝 **Conclusions**
The ResNet50-based model provides a reliable solution for early detection of rose leaf diseases, significantly aiding in the timely and effective management of crops.

## 🤝 **Contributing**
Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch (`feature/your-feature`).
3. Commit your changes.
4. Push to the branch.
5. Create a Pull Request.
