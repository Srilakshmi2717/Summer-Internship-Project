README FILE - Team 6 - Srilakshmi H, Poorna Prakash S (B. Tech AI and DS)

Overview
This project implements various segmentation models (U-Net, E-Net, DeepLab v3+, and Attention U-Net) for image segmentation tasks. It includes training, evaluation, and visualization of the models' performance using different metrics.

Steps to Execute
1. Clone the Notebook
1.1. Open the notebook on Kaggle: https://www.kaggle.com/code/srilakshmi2717/summer-internship-project
1.2. Click on the "Copy & Edit" button to create a copy of the notebook in your own Kaggle account.
1.3. Dataset link - https://www.kaggle.com/datasets/humansintheloop/semantic-segmentation-of-aerial-imagery

2. Set Up Kaggle Environment
2.1. Ensure that the necessary libraries are available. The key libraries required for the project include:
- TensorFlow
- Keras
- NumPy
- Matplotlib
- OpenCV
- Scikit-learn
- PIL (Python Imaging Library)
2.2. If any libraries are missing, install them using the Kaggle environment.

3. Upload the Dataset
3.1. Download the dataset and upload it to your Kaggle environment.
3.2. Ensure that the dataset is correctly referenced in the notebook by checking the file paths.

4. Run the Notebook
4.1. Step-by-step execution is required:
4.2. Data Preprocessing: This includes loading the dataset, resizing images, and applying any data augmentation techniques.
4.3. Model Definition: The four models (U-Net, E-Net, DeepLab v3+, Attention U-Net) are defined using the appropriate architecture and configuration.
4.4. Training: Train each of the models on the dataset. Monitor the training loss and accuracy as shown in the plots.
4.5. Evaluation: Evaluate the performance of each model using metrics like Class-wise IoU and loss functions.

5. Visualizations
5.1. Visualizations for training accuracy and loss, as well as segmentation results, are generated at each step.
5.2. These include plotting the predictions and comparing the results to the ground truth.

6. Model Comparison
6.1. The results of the four models are compared based on the evaluation metrics. Each model’s performance is analyzed to select the best-performing model for the given task.

7. Save and Export
7.1. Once the model is trained and evaluated, save the trained model for future use.
7.2. You can export the model weights or the entire model as needed.

8. Run the Final Evaluation and Summarize Results
8.1. Final comparison of results and detailed insights are presented in the notebook.
