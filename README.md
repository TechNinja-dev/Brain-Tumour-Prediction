# 🧠 Brain Tumor Prediction using Deep Learning

This project is a **Brain Tumor Prediction System** built using **Deep Learning** and deployed with an interactive **Streamlit web UI**.  
It allows users to upload MRI scans and get predictions on whether a brain tumor is present or not.  

---

## 🚀 Features

- Deep Learning model trained on MRI brain scan dataset  
- Streamlit-based user-friendly web interface  
- Image upload functionality for real-time predictions  
- Visualization of prediction results  
- Easy deployment and usage  

---

## 📂 Dataset

The dataset used for training and testing contains MRI brain images with and without tumors.  
You can download the dataset from the link below and place it in the `data/` folder:

👉 [Dataset Link] https://drive.google.com/drive/folders/1C9ww4JnZ2sh22I-hbt45OR16o4ljGxju?usp=sharing

---

## 🛠️ Tech Stack

- **Python 3.x**  
- **TensorFlow / Keras** - for building and training the deep learning model  
- **NumPy, Pandas** - for data preprocessing  
- **Matplotlib / Seaborn** - for visualization  
- **Streamlit** - for building the interactive UI  

---


## 📦 Installation

1. **Clone the repository**
   ```bash
   cd Brain-Tumour-Prediction
   git clone https://github.com/TechNinja-dev/Brain-Tumour-Prediction.git
2. **▶️ Order of Execution**

Run the files in the following order:

**Data Preprocessing**
```bash
python data_preprocessing.py

```
Cleans and prepares the MRI dataset for training.

**Model Definition**
```bash
python models.py
```

Defines the CNN architecture to be used for brain tumor classification.

**Training & Evaluation**
```bash
python train_evaluate.py

```
Trains the model, evaluates performance, and saves the trained weights in models/.

**Streamlit Application**
```bash
streamlit run app.py
```

Launches the web interface for real-time MRI image predictions.


