# **Student Career Prediction Using Machine Learning**

## **Overview**

This project applies machine learning, particularly a deep neural network (CNN), to predict the most suitable career path for students based on academic data. By processing student records and utilizing classification models, the system provides personalized career recommendations.


## **Features**

- Upload student academic data for career prediction.
- Data preprocessing and visualization.
- Implementation of a deep learning model (CNN).
- Career classification based on student performance.
- Interactive web interface for easy accessibility.

## **Installation**

1. Clone the repository:

```sh
git clone https://github.com/Raghavendra-Remella/Student-Career-Prediction-Using-Machine-Learning.git
cd Student-Career-Prediction-Using-Machine-Learning
```

2. Create a virtual environment (recommended for dependency management):

```sh
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:

```sh
pip install -r requirements.txt
```

## **Usage**

1. Run the Flask application:

```sh
python app.py
```

2. Open your browser and go to:

```
http://127.0.0.1:5000/
```

3. Upload student academic records and receive career predictions.

## **Machine Learning Model**

- **Deep Neural Network (CNN):**
  - Built using the Keras Sequential API.
  - Features multiple dense layers with ReLU activation.
  - Output layer applies softmax activation for multi-class classification.
  
- **Training Process:**
  - StandardScaler is used for feature scaling.
  - Trained on labeled student data with categorical cross-entropy loss.
  - Optimized using the Adam optimizer.
  - Evaluated on test data and visualized using Matplotlib.

## **Model Training Steps**

1. **Data Preprocessing:** Reads and scales input features.
2. **Model Definition:** Implements a deep CNN with 10 layers.
3. **Training:** Runs for 1000 epochs with a batch size of 512.
4. **Evaluation:** Computes accuracy on test data.
5. **Saving the Model:** Trained model is stored as **model.h5**.

## **Contributing**

Contributions are welcome! If you have ideas for improvement, feel free to fork the repository, make changes, and submit a pull request.

