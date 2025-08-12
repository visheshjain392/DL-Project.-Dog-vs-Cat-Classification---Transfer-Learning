🐶🐱 Dog vs Cat Classification – Transfer Learning
📌 Overview
This project uses Transfer Learning to classify images as either Dog or Cat. It leverages pre-trained deep learning models from TensorFlow/Keras for high accuracy while reducing training time. The dataset is sourced from Kaggle and processed using Google Colab for a GPU-accelerated workflow.

🚀 Features
Transfer Learning with TensorFlow/Keras pre-trained models.

Data Augmentation using ImageDataGenerator.

Visualization of dataset samples and training progress.

Evaluation with accuracy metrics and predictions.

Runs efficiently on Google Colab with GPU.

📂 Dataset
The dataset is the Dogs vs Cats dataset from Kaggle.

Downloaded directly in Colab using kagglehub.

Images split into training and testing sets using train_test_split.

🛠️ Technologies Used
Python

TensorFlow / Keras

NumPy, Matplotlib, PIL

scikit-learn

OpenCV (cv2_imshow)

Google Colab (GPU)

📖 How to Run in Google Colab
Open Notebook

Click this link to open the Colab notebook.

Enable GPU

Go to Runtime > Change runtime type > GPU.

Install and Setup Kaggle

python
Copy
Edit
!pip install kagglehub
import kagglehub
Run All Cells

Go to Runtime > Run all.

📊 Results
The trained model achieves high accuracy on test data with clear separation between dog and cat classifications.

📸 Sample Predictions
Image	Prediction
Dog image	🐶 Dog
Cat image	🐱 Cat

📜 License
This project is for educational purposes only.
