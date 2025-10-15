# Face-Mask-Detection
This project detects whether a person is wearing a mask or not using Computer Vision and Deep Learning. It combines CNN (Convolutional Neural Network) features with SIFT (Scale-Invariant Feature Transform) and Bag of Visual Words (BoVW) for better accuracy.
The model classifies images into two categories:
1) With Mask 
2) Without Mask 

# Libraries Used
1) Python
2) OpenCV
3) TensorFlow / Keras
4) NumPy
5) scikit-learn
6) Matplotlib

#  Dataset Structure
dataset/

 ├── with_mask/
 
 └── without_mask/
Each folder contains images of people with and without face masks.

# How to Run
1) Clone the repository:
git clone https://github.com/<your-username>/face-mask-detection.git
cd face-mask-detection

2) Install dependencies:
pip install tensorflow opencv-python scikit-learn matplotlib numpy

3) Update dataset path in the notebook:

data_dir = '/path/to/dataset'

4) Run the Google Collab Notebook


# Output

Shows training accuracy and validation accuracy graphs


<img width="567" height="438" alt="ACCURACY" src="https://github.com/user-attachments/assets/17036c2a-a7cc-4604-87ec-0cedd0988c69" />

Displays sample test images with actual and predicted labels


<img width="1186" height="683" alt="RESULTS" src="https://github.com/user-attachments/assets/17b3cc03-aacc-48cc-b7cc-0057759a4145" />

