# **Student Career Prediction Using Machine Learning**

## **📌 Overview**

This project utilizes machine learning, specifically a neural network (CNN), to predict the most suitable career path for students based on academic data. The system processes student data and applies classification models to provide career recommendations.


```

## **⚙️ Features**

✅ Upload student academic data\
✅ Preprocess and visualize data\
✅ Apply deep learning models (CNN)\
✅ Generate career predictions\
✅ User-friendly web interface

## **🛠 Installation**

1️⃣ Clone the repository:

```sh
git clone https://github.com/Raghavendra-Remella/Student-Career-Prediction-Using-Machine-Learning.git
cd Student-Career-Prediction-Using-Machine-Learning
```

2️⃣ Create a virtual environment (optional but recommended):

```sh
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3️⃣ Install dependencies:

```sh
pip install -r requirements.txt
```

## **🚀 Usage**

1️⃣ Run the Flask application:

```sh
python app.py
```

2️⃣ Open a browser and go to:

```
http://127.0.0.1:5000/
```

3️⃣ Upload student data and get career predictions.

## **🧠 Machine Learning Model Used**

- **Neural Network (CNN):** A deep learning model with multiple dense layers trained using categorical cross-entropy loss and the Adam optimizer.
- **Training:** Uses **StandardScaler** for feature scaling and **Keras Sequential API** for model definition.
- **Performance Visualization:** Training and validation loss & accuracy plotted using Matplotlib.

## **📊 Model Training Process**

1️⃣ Data Preprocessing: Loads and scales training/testing data.\
2️⃣ Model Definition: A 10-layer deep neural network.\
3️⃣ Training: Trained with 1000 epochs and batch size of 512.\
4️⃣ Evaluation: Model performance assessed on test data.\

## **📌 Contributing**

Contributions are welcome! If you'd like to improve the project, feel free to fork the repository and submit a pull request.



