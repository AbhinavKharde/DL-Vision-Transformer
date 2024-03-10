# Vision Transformer Projects

This repository contains projects developed using the Vision Transformer architecture for various computer vision tasks. Below, you'll find information about Vision Transformers, the datasets used, and accuracy results compared with previous architectures.

## Vision Transformer
Vision Transformer (ViT) is a deep learning architecture proposed by Alexey Dosovitskiy et al. in the paper An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale. Unlike convolutional neural networks (CNNs), which have been the dominant architecture for computer vision tasks, Vision Transformers utilize the transformer architecture, originally proposed for sequence modeling tasks in natural language processing (NLP).

### Key Features of Vision Transformers:
- Utilizes self-attention mechanisms for capturing global dependencies in images.
- Breaks down the input image into fixed-size patches and flattens them into sequences.
- Employs multiple transformer blocks to process these sequences and perform image classification tasks.
- Achieves competitive performance on various image recognition benchmarks.

For more details, please refer to the original paper: An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale. https://ar5iv.labs.arxiv.org/html/2010.11929

### Project 1: Covid-19 and Pneumonia Detection using Vision Transformer
This project focuses on detecting Covid-19 and pneumonia from chest X-ray images using the Vision Transformer architecture. The dataset consists of 5379 images divided into two classes: Covid-19 and pneumonia. With 1142 Covid-19 images and 4237 pneumonia images, the Vision Transformer model achieved impressive training accuracy of 99.96%. The testing accuracy reached 99.91%, showcasing the effectiveness of the Vision Transformer in accurately identifying respiratory diseases from chest X-ray images.

### Project 2: Covid-19 and Pneumonia Variants Detection using Vision Transformer
In this project, the goal is to detect different variants of Covid-19 and pneumonia from chest X-ray images. The dataset comprises 9208 images distributed across four classes: Covid-19, normal, bacterial pneumonia, and viral pneumonia. With a diverse dataset including 3001 Covid-19 images, the Vision Transformer model achieved a training accuracy of 93.23%. While the testing accuracy reached 88.56%, the model effectively differentiated between various respiratory conditions, aiding in targeted diagnosis and treatment.

### Project 3: Grapevine Leaf Disease Detection using Vision Transformer
This project focuses on detecting diseases in grapevine leaves using the Vision Transformer architecture. The dataset consists of 4062 images categorized into four classes: black measles, black rot, leaf blight, and healthy leaves. With a training accuracy of 98.97%, the Vision Transformer model demonstrates exceptional performance in identifying various diseases affecting grapevine leaves. The testing accuracy of 99.14% underscores the model's effectiveness in early disease detection, facilitating timely interventions to preserve grapevine health.

### Project 4: Pneumonia and Normal X-ray Dataset 
In this project, the objective is to distinguish between pneumonia and normal conditions using X-ray images of the chest. The dataset comprises 5856 images divided into two classes: normal and pneumonia. With 1583 normal images and 4273 pneumonia images, the Vision Transformer model achieved a training accuracy of 96.98%. The model's testing accuracy of 93.02% underscores its efficacy in accurately diagnosing pneumonia from X-ray images, enabling prompt medical intervention for affected individuals.

### Project 5: RSNA Dataset (Lung Opacity) using ViT
This project aims to detect lung opacity from chest X-ray images using the Vision Transformer architecture. The RSNA dataset consists of 26684 images classified into two classes: lung opacity and no lung opacity. With 6012 lung opacity images, the Vision Transformer model achieved a training accuracy of 82.19%. The testing accuracy of 80.70% demonstrates the model's ability to identify lung opacity, a crucial indicator of various respiratory conditions, aiding in early diagnosis and treatment planning.
