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

- **Training Loss:**
Epoch: 0, Loss: 0.7333691716194153
Epoch: 10, Loss: 0.7006592154502869
Epoch: 20, Loss: 0.6811805963516235
Epoch: 30, Loss: 0.6556774377822876
Epoch: 40, Loss: 0.6177041530609131
Epoch: 50, Loss: 0.5639956593513489
Epoch: 60, Loss: 0.49665507674217224
Epoch: 70, Loss: 0.42875686287879944
Epoch: 80, Loss: 0.37690436840057373
Epoch: 90, Loss: 0.340363085269928

- **Test Loss:** 0.2438156008720398
- **Accuracy:** 0.90 (27 out of 30 correct)

<img width="500" height="500" alt="image" src="https://github.com/user-attachments/assets/14e295f8-501d-4ebc-bdae-bee749260700" />
<img width="500" height="500" alt="image" src="https://github.com/user-attachments/assets/4e65fbc7-c9e6-4bcf-a097-8277abfab7b8" />

## How to Run

1. Clone the GitHub repository:
   ```
   git clone [repository_url]
   ```
2. Open the Jupyter notebook or Colab file.
3. Run all cells sequentially.
4. Explore training loss plot and decision boundary visualizations.
