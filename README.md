# 🔐 Python Face Verification System

A Python computer vision project that compares two facial images and determines whether they are likely to contain the same person.

## 📌 About the Project

I created this project to learn Python and explore how facial verification systems work.

The application allows a user to upload two images, detects the faces, compares their facial features, and returns one of three results:

- ✅ Likely Match
- ⚠️ Uncertain
- ❌ Likely Not a Match

## 🛠️ Technologies Used

- Python
- DeepFace
- ArcFace
- RetinaFace
- Google Colab
- GitHub

## ✨ Features

- Upload two images for comparison
- Automatic face detection
- Facial feature comparison
- Similarity distance calculation
- Custom verification thresholds
- Error handling for unclear images

## 🧠 What I Learned

While testing the project, I discovered that the original model could produce false-positive matches.

I improved the program by examining facial-distance scores and implementing more conservative decision thresholds.

This project helped me learn about:

- Python libraries
- Computer vision
- Facial verification
- Machine learning models
- Decision thresholds
- False positives
- Debugging

## 🚀 Running the Project

The project was developed using Google Colab.

Open `Face_Verification_System.ipynb` and run the notebook cells to test the application.

## ⚠️ Disclaimer

This project was created for educational and portfolio purposes. Facial verification systems can make mistakes and should not be used as the sole basis for high-stakes identity decisions.
