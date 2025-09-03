# Boston Housing Price Prediction with MLP


🎯 Project Goal: Predicting housing prices in the city of Boston using a Multi-Layer Perceptron (MLP) neural network built with Keras/TensorFlow.


## 🌐 Links

- [Dataset](https://storage.googleapis.com/tensorflow/tf-keras-datasets/boston_housing.npz)  
  Boston Housing Dataset

- [View project in Google Colab](https://colab.research.google.com/drive/1si1WV5-vf5eo2qGkl0RcVXJmfHK_NPVq?usp=sharing)  
  Google Colab Notebook: Run the project online

- [View project in GitHub](https://github.com/eliram88/Boston_house_price_prediction)  
  GitHub Repository: Source code and documentation



## 🔧 Tools & Libraries

- Python (Numpy, Tensorflow, Matplolib, Keras)
- Google Colab
- Google Drive
- GitHub for version control



## 📊  Dataset

- **Source:** Boston Housing dataset from `keras.datasets`
- **Samples:** 506 records  
  - 404 for training  
  - 102 for testing  
- **Features:** 13 attributes, including average number of rooms, age of buildings, crime rate, distance to employment centers, etc
- **Target:** House price (in thousands of dollars)



## 📊 Project Stages

### 🛠 Preprocessing

- Normalizing numerical features to range [0, 1] for better training stability.
- Splitting data into training, validation, and testing sets.


### 🧠 Model Design

- MLP (Multi-Layer Perceptron):

   - Input Layer → 13 features
   - Dense Layer → 64 units, relu activation
   - Dense Layer → 64 units, relu activation
   - Output Layer → 1 unit (for regression)


### ⚙ Training
 
 - Optimizer: RMSprop  
 - Loss: Mean Squared Error (MSE)  
 - Metric: Mean Absolute Error (MAE)  
 - Batch Size: 16  
 - Epochs: 20  


### 📈 Results | نتایج

- Validation MAE: ~3.03k USD 
- Test MAE: ~3.23k USD   
- Validation Loss Curve: loss steadily decreases until convergence.



## 🚀 How to Run

1) Install dependencies 
```bash
pip install tensorflow numpy matplotlib
```

2) Run Jupyter Notebook 
```bash
jupyter notebook
```
Open the file Boston_house_price_prediction.ipynb and run all cells.



## 📁 Project Structure
```bash
Boston_house_price_prediction/
│
├── 📁 notebook/
│   └── Boston_house_price_prediction     # Data analysis & model training
│
├── 📄 README.md                          # Project documentation
│
├── requirements.txt		          # Project Libraries
```



## 🧑‍💻 Developer

This project was developed by a data analysis and machine learning enthusiast with the goal of:

- Gaining practical experience in real-world regression problems
- Building a professional portfolio project
- Learning how to design, train, and interpret neural networks for predictive modeling
