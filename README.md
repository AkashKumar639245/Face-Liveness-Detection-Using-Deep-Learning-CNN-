# Face-Liveness-Detection-Using-Deep-Learning-CNN-

## Project Overview

Face Liveness Detection is a Deep Learning project that uses a Convolutional Neural Network (CNN) to identify whether a face image is **Real or Spoof**.

The main objective of this project is to help prevent face spoofing attacks by distinguishing genuine face images from fake face images.

The model takes a face image as input, processes it using a trained CNN model, and predicts whether the image is real or spoofed.

## Technologies Used

- Python
- Deep Learning
- Convolutional Neural Network (CNN)
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Jupyter Notebook

## CNN Model Architecture

The project uses a CNN model with the following layers:

1. Convolutional Layer (32 filters)
2. Convolutional Layer (64 filters)
3. Max Pooling Layer
4. Dropout Layer
5. Convolutional Layer (64 filters)
6. Max Pooling Layer
7. Flatten Layer
8. Fully Connected Dense Layer
9. Output Layer with Sigmoid Activation

**Model Configuration:**
- Input Image Size: 128 × 128 × 3
- Optimizer: Adam
- Loss Function: Binary Crossentropy
- Batch Size: 12
- Training Epochs: 50
- Activation Function: ReLU and Sigmoid

## Project Structure

```text
FACE-LIVENESS-DETECTION/
│
├── liveness.h5
├── liveness.py
├── model.ipynb
├── Report.pdf
└── README.md
```

## How It Works

1. Load a face image.
2. Resize the image to 128 × 128 pixels.
3. Convert the image into a NumPy array.
4. Normalize the image.
5. Load the trained CNN model.
6. Pass the image to the model for prediction.
7. Display the result as Real or Spoof with a confidence score.

## Installation

Install the required libraries:

```bash
pip install tensorflow numpy matplotlib pillow jupyter
```

## How to Run the Project

**Step 1:** Clone the repository.

```bash
git clone https://github.com/your-username/your-repository-name.git
```

**Step 2:** Open the project folder.

```bash
cd your-repository-name
```

**Step 3:** Place your test image in the project folder with the filename `f2.jpg`.

**Step 4:** Run the Python file.

```bash
python liveness.py
```

**Step 5:** View the prediction in the terminal.

## Prediction Output

The model predicts one of two classes:

- Real – If the model identifies a genuine face image.
- Spoof – If the model identifies a spoofed face image.

It also displays the prediction confidence percentage.

## Future Improvements

- Improve model accuracy using a larger dataset.
- Implement real-time face liveness detection using a webcam.
- Experiment with advanced CNN architectures.
- Improve detection against different types of spoofing attacks.

## Author

**Akash Kumar Singh**

- GitHub: [AkashKumar639245](https://github.com/AkashKumar639245)
- Project: Face Liveness Detection Using Deep Learning (CNN)



