# Retinal Vessel Segmentation with Deep Learning

Retinal illnesses such as diabetic retinopathy (DR) are the main causes of vision loss. In the early recognition of eye diseases, the segmentation of blood vessels in retina images plays an important role. However, due to the complex construction of the blood vessels and their varying thicknesses, segmenting the retina image is a challenging task.

This repository contains our approach to retinal vessel segmentation using deep learning, leveraging the Kaggle DRIVE 2004 dataset.

---

## Approach

We utilized a U-Net model from the segmentation library, which is a convolutional neural network designed for semantic image segmentation tasks. Key features of our implementation include:

- **Backbone**: VGG19 for feature extraction.
- **Activation Function**: Sigmoid, for binary segmentation.
- **Dataset**: Kaggle DRIVE 2004, specifically curated for retinal vessel segmentation tasks.

---


## Results

Below is an example of the segmentation result:

![Sample Segmentation Result](images/sample_result.png)

---

## References

1. Kaggle DRIVE 2004 Dataset: [Link to Kaggle]([https://www.kaggle.com](https://www.kaggle.com/datasets/zionfuo/drive2004))
2. U-Net Architecture: "U-Net: Convolutional Networks for Biomedical Image Segmentation"

