🐶🐱 Cat vs Dog Classifier using SVM
This project builds a binary image classifier that distinguishes between cats and dogs using a Support Vector Machine (SVM) model with optimized preprocessing and feature extraction.

📌 Project Highlights
🔍 Image resizing to 128×128 pixels

🧠 Feature extraction using HOG (Histogram of Oriented Gradients)

🔄 Data normalization with StandardScaler

📉 Dimensionality reduction using PCA (50 components)

⚙️ Model training with SVM (RBF kernel)

🔎 Hyperparameter tuning via GridSearchCV

📊 Random test image prediction included

🗂️ Dataset
The dataset used is publicly available on Kaggle:
👉 Cat and Dog Dataset – Tong Python on Kaggle

Structure:

dataset/
│
├── training_set/
│   ├── cats/
│   └── dogs/
│
└── test_set/
    ├── cats/
    └── dogs/

    
🚀 How to Run
Clone this repository:

bash
Sao chép
Chỉnh sửa
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
Install the required packages:

bash
Sao chép
Chỉnh sửa
pip install -r requirements.txt
Download the dataset from Kaggle and extract it into the dataset/ folder.

Open the notebook and run:

bash
Sao chép
Chỉnh sửa
jupyter notebook SVMCatDogUpdate.ipynb
🧪 Example Output
Random image from test set with prediction:

makefile
Sao chép
Chỉnh sửa
Predicted: Dog ✅
Actual:     Dog
🧠 Libraries Used
scikit-learn

matplotlib

numpy

opencv-python

skimage

📄 File Description
SVMCatDogUpdate.ipynb: Main notebook that performs preprocessing, training, evaluation, and visualization.

✅ TODO (Optional)
 Convert notebook to Python script

 Improve model speed with caching

 Deploy model as a simple web app
