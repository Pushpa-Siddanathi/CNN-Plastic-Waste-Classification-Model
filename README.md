#PROJECT
# CNN Model for Plastic Waste Classification

<h1 align="center">Hi there, I'm Pushpa Siddanathi 👋</h1>
<h3 align="center">Detail Oriented Computer Science Student | JAVA & Software Developer | Hands-on-Experience</h3>

<p align="center">
<a href="https://linkedin.com/in/pushpa-siddanathi"><img src="https://img.shields.io/badge/LinkedIn-Pushpa%20Siddanathi-blue?style=for-the-badge&logo=linkedin" alt="LinkedIn"></a>
<a href="https://github.com/Pushpa-Siddanathi"><img src="https://img.shields.io/badge/GitHub-Pushpa%20Siddanathi-black?style=for-the-badge&logo=github" alt="GitHub"></a>
<a href="mailto:pushpasiddanathi6@gmail.com"><img src="https://img.shields.io/badge/Email-pushpasiddanathi6%40email.com-red?style=for-the-badge&logo=gmail" alt="Email"></a>
<a href="https://dataxpushpa.wixsite.com/myportfolio"><img src="https://img.shields.io/badge/Portfolio-Pushpa%20Siddanathi-ff69b4?style=for-the-badge&logo=appveyor" alt="Portfolio"></a>
</p>

---


This project focuses on building a Convolutional Neural Network (CNN) model to classify images of plastic waste into various categories like organic and recyclable. The primary goal is to enhance waste management systems by improving the segregation and recycling process using deep learning technologies.  

---

## Table of Contents  
- [Project Description](#project-description)  
- [Dataset](#dataset)  
- [Model Architecture](#model-architecture)  
- [Model Deployment](#model-deployment)  
- [Training](#training)  
- [Weekly Progress](#weekly-progress)  
- [How to Run](#how-to-run)  
- [Technologies Used](#technologies-used)  
- [Future Scope](#future-scope)  
- [Contributing](#contributing)  
- [License](#license)  

---

## Project Description  
Plastics are inexpensive, lightweight and durable materials, which are readily be moulded into a variety of products that find use in a wide range of applications. As a consequence, the production of plastics has increased markedly over the last 70 years. However, current levels of their usage and disposables generates various environmental problems. A major portion of plastic produced each year is used to make disposable items of packaging or other short-lived products that are discarded within a year of manufacture. The main goal of our application is to raise awareness about plastic hazards; and want to encourage people to learn the kind of plastic they use and which plastic is easily decomposed in the environment using Convolutional Neural Network. If you don’t act now, in the future years there will be more plastic in the ocean than fish. So, which helped to propose a novel model based on the deep learning mechanism by reading features of different plastic materials and then trained the model. Experimental results show the classifier give the results of the variant of plastic and the details like what it is kind of plastic its made of, whether it is recyclable or not and years taken to decompose, etc.

## Dataset  
The dataset used for this project is the **Waste Classification Data** by Sashaank Sekar. It contains a total of 25,077 labeled images, divided into two categories: **Organic** and **Recyclable**.  

### Key Details:
- **Total Images**: 25,077  
- **Training Data**: 22,564 images (85%)  
- **Test Data**: 2,513 images (15%)  
- **Classes**: Organic and Recyclable  
- **Purpose**: To aid in automating waste management and reducing the environmental impact of improper waste disposal.

### Dataset Link:  
You can access the dataset here: [Waste Classification Data](https://www.kaggle.com/datasets/techsash/waste-classification-data).  

## Model Architecture  
The CNN architecture includes:  
- **Convolutional Layers:** Feature extraction  
- **Pooling Layers:** Dimensionality reduction  
- **Fully Connected Layers:** Classification  
- **Activation Functions:** ReLU and Softmax  

### Model Structure:
<p align="center">
<img src="https://github.com/Pushpa-Siddanathi/CNN-Plastic-Waste-Classification/blob/main/Images/CNN-Architecture.jpg" style="width:80%;">
</p>

## Model Deployment  
The trained CNN model is available on Kaggle:

[Waste Classification CNN Model](https://www.kaggle.com/models/pushpasiddanathi/waste-classification-cnn-model/)

## Training  
- **Optimizer:** Adam  
- **Loss Function:** Categorical Crossentropy  
- **Epochs:** 25  
- **Batch Size:** 32  

## Weekly Progress  

### **Week 1: Libraries, Data Import, and Setup**  
- **Date:** 21st May 2025 - 3rd June 2025  
- **Activities:**  
- Imported required libraries and frameworks.  
- Set up the project environment.  
- Explored the dataset structure.  

- **Notebooks:**  
- [Week1-Libraries-Importing-Data-Setup.ipynb](Week1-Libraries-Importing-Data-Setup.ipynb)  
- [Kaggle Notebook](https://www.kaggle.com/code/hardikksankhla/cnn-plastic-waste-classification)  

### **Week 2: Model Training, Evaluation, and Predictions**  
- **Date:** 4th June 2025 - 20th June 2025  
- **Activities:**  
- Trained the CNN model on the dataset.  
- Evaluated model performance using accuracy and loss metrics.  
- Visualized classification results with a confusion matrix.  

- **Notebooks:**  
- [Week2-Model-Training-Evaluation-Predictions.ipynb](Week2-Fitting-CNN-Model.ipynb)  
- [Kaggle Notebook](https://www.kaggle.com/code/pushpasiddanathi/cnn-plastic-waste-classification)  

### **Week 3: Streamlit App and Model Deployment**  
- **Date:** 21st June 2025 - 1st July 2025  
- **Activities:**  
- Developed a **Streamlit web application** for real-time waste classification.  
- Uploaded the trained model to **Kaggle and GitHub** for public access.  
- Finalized the **project documentation and README formatting**.

- **Notebooks:**  
  - [Week2-Week3-Combined-CNN-Model.ipynb]([Week2-Week3-Combined-CNN-Model.ipynb])  
  - [Week2-Week3-Combined-CNN-Model.ipynb](Week2-Week3-Combined-CNN-Model.ipynb)  
- [Kaggle Notebook](https://www.kaggle.com/code/pushpasiddanathi/cnn-plastic-waste-classification)  


## How to Run  
1. Clone the repository:  
```bash  
git clone https://github.com/Pushpa-Siddanathi/CNN-Plastic-Waste-Classification  
cd CNN-Plastic-Waste-Classification
```  
2. Install the required dependencies:  
```bash  
pip install -r requirements.txt  
```  
3. Run the Streamlit app:  
```bash  
streamlit run app.py  
```  

## Technologies Used  
- Python  
- TensorFlow/Keras  
- OpenCV  
- NumPy  
- Pandas  
- Matplotlib  
- Streamlit  

## Future Scope  
- Expanding the dataset to include more plastic waste categories.  
- Improving model accuracy using transfer learning.  
- Deploying the model as a mobile application.  

## Contributing  
Contributions are welcome! Open an issue or submit a pull request.  

## License  
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
