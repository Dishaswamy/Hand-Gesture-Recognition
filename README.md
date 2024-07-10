# Hand-Gesture-Recognition

Objective:

To develop and deploy a robust real-time hand gesture recognition model capable of accurately identifying various hand gestures, such as thumbs up, thumbs down, live long, and thank you, using a combination of TensorFlow, Keras, and OpenCV. This project aimed to enhance human-computer interaction through intuitive gesture-based controls.

Process:

Data Collection and Annotation:
Initiated the process of capturing various hand gestures using a webcam accessed via OpenCV. This involved recording numerous samples of each gesture to ensure a diverse and comprehensive dataset.
Utilized the LabelImg library to label the collected images, providing precise annotations for each hand gesture. This step was crucial for training the detection model with accurately labeled data.

Model Selection and Preparation:
Downloaded pretrained models from the TensorFlow Model Zoo. These models provided a strong foundation, leveraging pre-learned features for efficient training.
Installed and configured the TensorFlow Object Detection (TFOD) API, setting up the necessary environment and dependencies for model training and evaluation.
Selected the SSD (Single Shot MultiBox Detector) MobileNet V2 FPNLite 320x320 model for its balance of speed and accuracy, making it ideal for real-time applications on devices with limited computational resources.

Training and Deployment:
Configured the training pipeline using the SSD MobileNet V2 FPNLite 320x320 model, tailoring the setup to the specifics of the hand gesture dataset.
Trained the model on the annotated dataset, iteratively refining the model parameters to optimize detection performance.
Deployed the trained model in a real-time detection system, integrating it with OpenCV for live video feed processing.

Result:

Achieved high accuracy in real-time detection of hand gestures, with the model demonstrating robust performance in identifying the specified gestures (thumbs up, thumbs down, live long, and thank you) under various conditions. The deployment proved effective for intuitive and responsive human-computer interaction, validating the success of the hand gesture recognition model.
