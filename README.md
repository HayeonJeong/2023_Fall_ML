# Project: Comparison and Optimization of Machine Learning Models using Hand-made and Original MNIST Datasets
## Project Goal
To compare the inference results between the hand-made MNIST dataset and the original MNIST dataset, identify the reasons for performance degradation in the hand-made dataset, and improve recognition performance by training and optimizing a machine learning model using the combined datasets.

## Project Steps
1. Data Collection and Conversion:
    - Write digits 0-9 and symbols +, -, x, /, = by hand, scan or photograph them, and convert each data instance to a 28x28 grayscale image similar to MNIST instances.
    - Each person submits 4 images per digit (total 400 digits, 40 per digit) and 4 images per symbol (total 400 symbols, 80 per symbol).
    - Use the provided image conversion code to convert to npz files and submit with 380x380 resolution images.
    - The conversion code is for digits; adjust the label in cell 1 for operation symbols.

2. Hand-made Test Dataset Composition:
    - Select 1 image per person from the 40 images to create a hand-made test dataset (total 60 instances per team: 4 images x 15 people).
    - Train the provided machine learning model with the original MNIST dataset and compare predictions and scores on both the hand-made test dataset and the original MNIST test dataset.

3. Analyze Performance Degradation:
    - Analyze the reasons for performance degradation in the hand-made dataset using various methods.
    - Compare dataset characteristics through image properties and attribute calculations to infer causes.

4. Model Optimization:
    - Use the original MNIST dataset and the machine learning algorithms learned in class to find the best performing model.
    - Add the provided hand-made dataset (excluding the test dataset) and optimize the chosen machine learning model.
    - Do not use Tensorflow or Pytorch for neural networks, but scikit-learn's NN is allowed.

5. Final Model Evaluation:
    - Evaluate the final model using a separate hand-made MNIST test dataset.
    - Additional points awarded based on performance.