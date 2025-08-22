1. Artificial Intelligence Project – License Plate Detection
This project demonstrates how Artificial Intelligence and Computer Vision can be used to detect vehicle license plates from images.

Technology Used: OpenCV, Haar Cascade Classifier, PIL, NumPy, Matplotlib

Workflow:
  Load an image from a URL or local storage.

  Convert it to grayscale for better feature extraction.

  Use a pre-trained Haar Cascade (haarcascade_russian_plate_number.xml) to detect license plates.

  Draw bounding boxes around detected license plates.

  Display the results using Matplotlib.

🔹 Use Case: This project can be extended to real-time license plate detection using live video feeds, which has applications in traffic monitoring, parking systems, and security.

2. Deep Learning Project – Cassava Leaf Disease Classification

This project applies Deep Learning (Convolutional Neural Networks) to classify cassava plant leaves into different disease categories using the Cassava dataset.

Technology Used: TensorFlow, Keras, TensorFlow Datasets (TFDS), NumPy, Matplotlib

Workflow:

Load the Cassava dataset from TensorFlow Datasets.

Preprocess the images (resize to 150x150, normalize pixel values).

Build a CNN model with convolutional, pooling, flatten, and dense layers.

Train the model on labeled training data and validate performance.

Evaluate accuracy and visualize results.

🔹 Use Case: Helps farmers and agricultural experts identify diseases early, leading to better crop management and improved yield.
