# face-mask-detection
Face Mask Detection Using Deep Learning
# Face Mask Detection Using Deep Learning

## Project Overview
This project involves developing a deep learning model to detect whether individuals in images are wearing masks correctly, incorrectly, or not at all. The project leverages PyTorch and utilizes a pre-trained Faster R-CNN model. 
I also trained the model using High-Performance Computing (HPC) infrastructure was used to expedite the training process which I got access as a uni student. However, here I have trained it using free google colab T4 Gpu.

## Tech Stack
- Python
- PyTorch
- Google Colab
- torchvision
- Fast R-CNN

## Project Description
1. **Data Preparation:**
   - Downloaded and extracted a dataset of masked face images.
   - Organized the dataset into training and validation directories.
   - Applied data transformations and augmentation techniques to enhance model robustness.

2. **Model Development:**
   - Utilized a pre-trained Faster R-CNN model.
   - Customized the model to classify faces into three categories: with mask, without mask, and mask worn incorrectly.

3. **Training and Evaluation:**
   - Trained the model using the prepared dataset..
   - Evaluated model performance using standard metrics.
   - Fine-tuned the model based on evaluation results.

4. **Results:**
   - The system accurately detects mask usage, showing promising results for real-world applications.

