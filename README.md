# CSC173 Activity 02 - Build a Student Pass/Fail Classifier

**Date:** November 03, 2025  
**Name:** Kyla Reambonanza

## Project Overview

Build and train a neural network to predict whether a student will pass or fail based on their study hours and attendance rate.

## Data Preparation

Implementing a simple neural network using a custom dataset using PyTorch along with some other dependencies and the function to generate the dataset.

## Network Architecture

- Input layer: 2 features (study_hours, attendance_rate)
- Hidden layer: 8 neurons with ReLU activation
- Hidden layer: 4 neurons with ReLU activation
- Output layer: 1 neuron with Sigmoid activation (binary classification)

## Implementation Details

1. Load, explore, and visualize the dataset
2. Prepare the data (convert to tensors, split train/test)
3. Design a neural network architecture
4. Define loss function and optimizer
5. Train the model
6. Evaluate performance
7. Visualize results

## Results & Visualization

Test Loss: 0.2438156008720398
Accuracy: 0.90 (27 out of 30 correct)

<img width="500" height="500" alt="image" src="https://github.com/user-attachments/assets/0b47f46d-59da-4092-a4d6-b40dafe0de41" />
<img width="500" height="500" alt="image" src="https://github.com/user-attachments/assets/76e66ac3-0db1-42ba-ab2f-8adb1b1ac128" />

## How to Run

1. Clone the GitHub repository:
   ```
   git clone [repository_url]
   ```
2. Open the Jupyter notebook or Colab file.
3. Run all cells sequentially.
4. Explore training loss plot and decision boundary visualizations.
