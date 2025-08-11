# Boston Housing Price Prediction with MLP

🎯 هدف پروژه: پیش‌بینی قیمت خانه‌ها در شهر بوستون با استفاده از مدل شبکه عصبی چندلایه (MLP) در Keras/TensorFlow.



## 🌐 لینک ها

- [دیتاست پروژه](https://storage.googleapis.com/tensorflow/tf-keras-datasets/boston_housing.npz)
  فایل دیتاست مورد استفاده در پروژه

- [مشاهده پروژه در Google Colab](https://colab.research.google.com/drive/1si1WV5-vf5eo2qGkl0RcVXJmfHK_NPVq?usp=sharing)
 اجرای آنلاین کد پروژه در محیط Google Colab

- [مشاهده پروژه در GitHub](https://github.com/eliram88/Boston_house_price_prediction)
  سورس کد و مستندات پروژه در GitHub



## 🔧 ابزارهای استفاده‌شده

- Python (Numpy, Tensorflow, Matplolib, Keras)
- Google Colab
- Google Drive
- GitHub for version control



## 📊  دیتاست

- **Source:** Boston Housing dataset from `keras.datasets`
- **Samples:** 506 records  
  - 404 for training  
  - 102 for testing  
- **Features:** 13 ویژگی شامل میانگین تعداد اتاق‌ها، سن ساختمان، میزان جرم، فاصله تا مراکز کاری و ...  
- **Target:** قیمت خانه (به هزار دلار)



## 📊 مراحل پروژه

### 🛠 Preprocessing | پیش‌پردازش

- Normalizing numerical features to range [0, 1] for better training stability.
- Splitting data into training, validation, and testing sets.


### 🧠 Model Design | طراحی مدل

- MLP (Multi-Layer Perceptron):

   - Input Layer → 13 features
   - Dense Layer → 64 units, relu activation
   - Dense Layer → 64 units, relu activation
   - Output Layer → 1 unit (for regression)


### ⚙ Training | آموزش
 
 - Optimizer: RMSprop  
 - Loss: Mean Squared Error (MSE)  
 - Metric: Mean Absolute Error (MAE)  
 - Batch Size: 16  
 - Epochs: 20  


### 📈 Results | نتایج

- Validation MAE: ~3.03 هزار دلار  
- Test MAE: ~3.23 هزار دلار   
- Validation Loss Curve: loss steadily decreases until convergence.



## 🚀 نحوه اجرا

1) Install dependencies | نصب کتابخانه‌ها
```bash
pip install tensorflow numpy matplotlib
```

2) Run Jupyter Notebook | اجرای نوت‌بوک
```bash
jupyter notebook
```
Open the file Boston_house_price_prediction.ipynb and run all cells.



## 📁 ساختار فایل‌ها
```bash
Boston_house_price_prediction/
│
├── 📁 notebook/
│   └── Boston_house_price_prediction     # Data analysis & model training
│
├── 📄 README.md                          # Project documentation
│
├── requirements.txt		         # Project Libraries
```



## 🧑‍💻 توسعه‌دهنده

این پروژه توسط یک علاقه‌مند به تحلیل داده و یادگیری ماشین طراحی و اجرا شده  
با هدف شرکت در موقعیت های "تحلیلگر داده / دیتا ساینتیست".

✨ هدف: توسعه نمونه کار قابل ارائه، تمرین تحلیل واقعی، یادگیری مدل‌سازی حرفه‌ای و تفسیر مدل
