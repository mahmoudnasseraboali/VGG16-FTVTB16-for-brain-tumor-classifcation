# A-Hybrid-of-the-VGG-16-and-FTVT-b16-Models-to-Enhance-Brain-Tumors-Classification-Using-MRI-Images
The accurate classification of brain tumors from magnetic resonance imaging (MRI) scans
 is pivotal for timely clinical intervention, yet remains challenged by tumor heterogeneity, morpho
logical variability, and imaging artifacts.This paper presents a novel hybrid approach for improved
 brain tumor classification proposes a novel hybrid deep learning framework that amalgamates the
 hierarchical feature extraction capabilities of VGG-16, a convolutional neural network (CNN), with
 the global contextual modeling of FTVT-b16, a fine-tuned Vision Transformer (ViT), to advance
 the precision of brain tumor classification.To evaluate the recommended method’s efficacy, two
 widely known MRI datasets were utilized in the experiments. The first dataset consisted of 7.023
 MRI scans categorized into four classes—gliomas, meningiomas, pituitary tumors, and no tumor.
 The second dataset was obtained from Kaggle which consisted of 3000 scans categorized into two
 classes, consisting of healthy brains and brain tumors.The proposed framework addresses critical
 limitations of conventional CNNs (local receptive fields) and pure ViTs (data inefficiency), offer
ing a robust,interpretable solution aligned with clinical workflows. These findings underscore the
 trans-formative potential of hybrid architectures in neuro-oncology, paving the way for AI-assisted
 precision diagnostics. Future work will focus on multi-institutional validation and computational
 optimization to ensure scalability in diverse clinical settings. The proposed framework was run on
 these two different datasets and demonstrated outstanding performance, with accuracy of 99.46% 
 and 99.90%, respectively.

# Dataset

  The Kaggle database website is the
 open-access dataset used in this study [27]. Gliomas, meningiomas, pituitary, and no tumor
 are four distinct groups into which the 7,023 images captured by MRI of the human brain
 are classified. This dataset’s main goal is to help researchers create a highly accurate model
 for detect and classify brain tumors.Demographic representation of the kaggle dataset
 shown in Figure 6.
 The second dataset, named Brain Tumour Detection 2020 (BR35H) , is an MRI dataset
 obtained from the Kaggle website at (kaggle.com/datasets/ahmedhamada0/brain-tumour
 detection, accessed on 19 September 2023). We refer to this dataset as dataset2, consisting of
 two classes, with 1500 images of the tumor class and 1500 images of normal or non-tumor
 cases.
 
# Methodology

 We suggest a hybrid of VGG-16 with fine tuned vision transformers model to enhance brain tumors classification using MR images. The system includes choosing 27 capabilities from layer order 3 of VGG-16, which incorporates 13,696 capabilities, to reap the first-class category performance. The typical structure of VGG-16 with fine-tuned Vision Transformers models is: 
1-The input image is split into several patches.
2-The images were flattened and furnished with class labels.
3-The outcomes of transformers community were dispatched to the multilayer perception modules. 
Constructing the Fused Model Constructing the model fusion of VGG-16 and FTVT-b16 includes many steps:
-Feature Extraction: Initial function extraction takes the area via the VGG-16 backbone, which analyzes the MRI images and extracts deep features.
-Attention Mechanism: function input to the FTVT-b16 model, which makes use of its self-attention layers to create awareness of salient features and contextual cues that signify distinctive tumor types.
-Integration Layer: An integration layer merges the outputs of each model at the same time as leveraging strategies, inclusive of concatenation or weighted averaging to create a unified feature representation.
-Classification: The final features from the mixing layer are being fed into fully connected layers for the final types of tumor types, inclusive of gliomas, meningiomas, and pituitary tumors.

# Results
![image](https://github.com/user-attachments/assets/73b190e5-a5d9-49cc-81e1-e5fe80d5dc65)

![image](https://github.com/user-attachments/assets/3b3a3c8a-8f62-401e-acbd-c0ad026ca80a)

![image](https://github.com/user-attachments/assets/782c3451-6a60-483b-af7e-ed6aee6f6bf1)

![image](https://github.com/user-attachments/assets/f175ffae-46bc-47a7-b042-e631a08d5870)

![image](https://github.com/user-attachments/assets/20e83ef4-5f15-46ae-9e58-41e76da58368)





