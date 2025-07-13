🌸 Flower Recognition using CNN | Machine Learning Project Overview: I developed a flower recognition model using a Convolutional Neural Network (CNN) to classify images of different flower types such as sunflower, rose, and daisy. 
link for dataset:-https://www.kaggle.com/datasets/alxmamaev/flowers-recognition

Steps Followed:

1.Dataset Collection:

Downloaded a publicly available flower image dataset from Kaggle.

The dataset included labeled images of flowers like sunflower, rose, and daisy.

2.Preprocessing Pipeline (Local Machine using Spyder):

Created a consolidated.py script for organizing and preprocessing the dataset.

Built a folder structure:

images/: Original downloaded images.

clean_data/: Processed data outputs.

The consolidated.py script:

Read and resized all images.

Converted image-label pairs into pickle files:

images.p – Pickled NumPy array of image data.

labels.p – Corresponding class labels.

3.Training the Model (on Google Colab):

Uploaded images.p and labels.p to Google Colab for training.

Built and trained a CNN model using TensorFlow/Keras to classify the flower types.

Evaluated model performance using accuracy and loss metrics.

Tools & Libraries Used:

*Python, OpenCV, NumPy, Pandas

*TensorFlow/Keras for deep learning

*Matplotlib for visualization

*Google Colab (for model training)

*Spyder IDE (for data preprocessing)
