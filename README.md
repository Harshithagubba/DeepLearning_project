
# Water Level Classification in Bottles

This repository features a project focused on classifying the water level in a bottle into three categories: **Full**, **Half**, and **Overflowing**. The project leverages a **Convolutional Neural Network (CNN)** to achieve accurate classification based on images of bottles.

## 📦 **Project Overview**

- **Objective**: Develop a CNN model to classify water levels in a bottle as Full, Half, or Overflowing.
- **Dataset**: Images of bottles at different water levels.
- **Technologies**: TensorFlow, Keras, Flask, NumPy, PIL

## 📂 **Repository Structure**

1. **Project Initialization and Planning Phase**
   - Initial setup and planning documents.

2. **Data Collection and Preprocessing Phase**
   - Data collection scripts and preprocessing methods for bottle images.

3. **Model Development Phase**
   - Code and notebooks related to the development of the CNN model.

4. **Model Optimization and Tuning Phase**
   - Scripts for tuning and optimizing the model for better performance.

5. **Project Executables**
   - Includes the trained model (`x.h5`) and other executable scripts.

6. **Documentation**
   - Contains the `README.md` file and additional documentation, including a video demo.

7. **app.py**
   - Main Flask application file to serve the model and handle predictions.

8. **index.html**
   - The HTML file providing the user interface for the web application.

## 🚀 **Getting Started**

### Prerequisites

- Python 3.x
- Flask
- TensorFlow
- Keras
- Pillow
- NumPy

### Installation

1. **Clone the Repository**

    ```bash
    git clone https://github.com/Harshithagubba/DeepLearning_project.git
    cd DeepLearning_project
    ```

2. **Install Dependencies**

    It’s recommended to use a virtual environment. Install the required packages using:

    ```bash
    pip install -r requirements.txt
    ```

3. **Run the Application**

    Ensure the `x.h5` file is in the project directory. Start the Flask application with:

    ```bash
    python app.py
    ```

    Access the application at `http://127.0.0.1:5000/`.

## 🌐 **Usage**

1. Open your browser and go to the Flask application URL.
2. Upload an image of a bottle.
3. Click "Predict" to see the water level classification (Full, Half, Overflowing).

## 📁 **File Descriptions**

- **app.py**: Flask application script for handling model predictions.
- **index.html**: User interface for the web application.
- **model.h5**: Trained CNN model file.
- **Project Phases**: Organized documents and scripts by project phase.

## 🤝 **Contributing**

Contributions are welcome! Please fork the repository and submit a pull request with any improvements. For bug reports or feature requests, open an issue in this repository.


## 📧 **Contact**

For any questions or additional information, please contact me at [harshithagubba20@gmail.com].
