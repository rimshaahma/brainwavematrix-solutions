

# AI Projects at BrainWaveMatrix Solutions

This repository contains two AI projects completed during my remote internship at **BrainWaveMatrix Solutions**. These projects focus on **Fake News Detection** and **Text-to-Image Generation** using machine learning and deep learning techniques. The projects are available as ZIP files for download.

## Projects Overview

### 1. Fake News Detection

The **Fake News Detection Model** classifies news articles as either real or fake using machine learning techniques. It involves text preprocessing, vectorization, and classification models to identify fake news.

#### Key Features:
- **Data Preprocessing**: Text cleaning and preparation.
- **Vectorization**: Count Vectorization or TF-IDF.
- **Models**: Logistic Regression, Random Forest, and SVM.
- **Evaluation**: Accuracy, precision, recall, and confusion matrix.

#### Libraries Used:
- `pandas`
- `scikit-learn`
- `nltk`
- `numpy`
- `joblib`

#### Steps to Set Up:
1. Download and extract the ZIP file for Fake News Detection.
2. Install required libraries:
   ```bash
   pip install pandas scikit-learn nltk joblib
   ```
3. Load the dataset (fake.csv and true.csv) and train the model.
4. Implement the function to classify input news articles as REAL or FAKE.

[Download the Fake News Detection Project (ZIP)]

---

### 2. Text-to-Image Generation

The **Text-to-Image Generation** application generates images based on text descriptions using a pre-trained model (e.g., Stable Diffusion). The application is deployed using Flask for the user interface.

#### Key Features:
- **Web Interface**: Simple UI created using Flask.
- **Text-to-Image Generation**: Uses Stable Diffusion to generate images.
- **Image Handling**: Saving and managing generated images using Pillow.

#### Libraries Used:
- `flask`
- `torch`
- `diffusers`
- `transformers`
- `Pillow`

#### Steps to Set Up:
1. Download and extract the ZIP file for Text-to-Image Generation.
2. Install required libraries:
   ```bash
   pip install flask torch diffusers transformers pillow
   ```
3. Create the project directory and structure it as follows:
   ```bash
   my_text_to_image_project/
   ├── app.py
   ├── templates/
   │   └── index.html
   └── static/
       └── generated_image.png
   ```
4. Run the Flask app:
   ```bash
   python app.py
   ```
5. Open the application in your browser at `http://127.0.0.1:5000/` to generate images from text descriptions.

[Download the Text-to-Image Generation Project (ZIP)]

---

## Conclusion

These two projects demonstrate the application of machine learning and deep learning techniques in real-world scenarios. The **Fake News Detection** model focuses on classifying news articles, while the **Text-to-Image Generation** project uses deep learning models to create images from text descriptions. Both projects are available in ZIP format for easy download and setup.

Feel free to download the ZIP files and follow the setup instructions to explore the projects in detail.

