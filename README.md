# Human Emotion Detection System 🎭

A real-time human emotion detection system that classifies facial expressions into one of seven emotions: **Angry, Disgusted, Fearful, Happy, Neutral, Sad, Surprised**. Built using **Python**, **OpenCV**, and a **pretrained CNN model**.

---

## Features ✨
- **Real-Time Detection**: Detects emotions in real-time using a webcam.
- **Seven Emotions**: Classifies facial expressions into seven emotions.
- **High Accuracy**: Achieves **~65% accuracy** on the FER-2013 dataset.
- **User-Friendly**: Simple and intuitive interface for easy interaction.

---

## Technologies Used 🛠️
- **Python**: Core programming language.
- **OpenCV**: For face detection and video processing.
- **TensorFlow/Keras**: For building and training the CNN model.
- **Haar Cascade**: For face detection.
- **FER-2013 Dataset**: Contains 35,887 grayscale images of facial expressions.


---
##Dataset 📂
FER-2013: A dataset containing 35,887 grayscale images (48x48 pixels) of facial expressions.

Emotion Classes: Angry, Disgusted, Fearful, Happy, Neutral, Sad, Surprised.

Data Augmentation: Techniques like rotation, flipping, and scaling were used to improve model generalization.

---

##Training Process 🧠
Data Preprocessing: Images were resized, normalized, and augmented.

CNN Model: Built with multiple convolutional layers.

Training: Trained for 50 epochs using categorical cross-entropy loss.

Evaluation: Achieved ~65% accuracy on the validation set.


---

##Pretrained Model 🤖
Why Pretrained Models?:

Save time by avoiding training from scratch.

Leverage learned features for faster deployment.

Provide robust performance in real-world conditions.

Model Used: model.h5 (pretrained CNN model).


---


##Workflow 📊
Capture: Use OpenCV to capture frames from the webcam.

Face Detection: Detect faces using Haar Cascade.

Preprocessing: Crop, resize, and normalize the face.

Emotion Prediction: Feed the processed image into the pretrained model.

Output Display: Display the detected emotion.

---

## Installation and Setup 🛠️
1. Clone the repository:
   ```bash
   git clone https://github.com/bhaskarchowdary826/Human-Emotions-Detector_AI.git

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt

3. Run the emotion detection system:
   ```bash
   python emotion_detection.py


---

##Challenges 🚧
Model Accuracy & Generalization: Improving accuracy for diverse facial expressions.

Real-Time Performance: Ensuring smooth real-time emotion recognition.

Ethical & Privacy Concerns: Addressing privacy issues related to facial data.

---

##Applications 🌍
Mental Health Monitoring: Track emotional well-being.

Gaming: Enhance user experience with emotion-based interactions.

Education: Analyze student engagement in online classes.

Security: Detect suspicious behavior in public spaces.

Customer Service: Improve customer interactions by analyzing emotions.


---

##Future Improvements 🔮
Improve Accuracy: Use larger datasets or advanced models like FaceNet.

Multiple Faces: Detect emotions for multiple faces in a single frame.

User-Friendly GUI: Add a graphical interface for easier interaction.

---

##Contributing 🤝
Contributions are welcome! Feel free to open an issue or submit a pull request.

---

Connect with Me 🌐


