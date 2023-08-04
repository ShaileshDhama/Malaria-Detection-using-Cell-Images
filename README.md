# Spotting Malaria

## Table of Contents

- [Overview](#overview)
- [Diagnosis Challenges](#diagnosis-challenges)
- [ResNet and Residual Learning](#resnet)
- [Dataset](#dataset)
- [Approach](#approach)
- [Results](#results)
- [Additional Information](#additional-information)
- [Repository Structure](#repository-structure)
- [Citation](#citation)

## Overview <a name="overview"></a>

Malaria is a life-threatening disease caused by parasites transmitted to humans through infected female Anopheles mosquitoes. Malaria was responsible for an estimated 219 million cases and 435,000 deaths in 2017 despite being preventable and curable. Early and accurate malaria diagnosis is crucial for rapid and effective disease management and surveillance.

In this project, we use deep learning techniques to detect the presence of malaria in cell images, specifically using a Residual Network (ResNet) model.

## Diagnosis Challenges <a name="diagnosis-challenges"></a>

Diagnosis of malaria can be difficult, particularly in areas where malaria is not endemic. Healthcare providers may need to be more familiar with the disease and may fail to order the necessary diagnostic tests. In a non-immune individual, symptoms usually appear 10–15 days after the infective mosquito bite, but the initial symptoms may be mild and difficult to recognize as malaria. If not treated within 24 hours, P. falciparum malaria can progress to severe illness, often leading to death.

## ResNet and Residual Learning <a name="resnet"></a>

ResNet, short for residual network, is a type of network designed to overcome the problem of vanishing gradients in deep neural networks by introducing 'skip connections' or 'shortcuts' to allow gradients to flow through the network directly. These networks have been extremely successful and achieved state-of-the-art image classification task performance.

## Dataset <a name="dataset"></a>

The dataset used in this project can be downloaded from [Kaggle](https://www.kaggle.com/iarunava/cell-images-for-detecting-malaria).

## Approach <a name="approach"></a>

The methodology involves the following steps:

1. Data processing & Exploratory Data Analysis
2. Import Libraries
3. Loading and processing data
4. Use ResNet34 Pre-trained model
5. Confusion Matrix
6. Test our model
7. Heatmaps

## Results <a name="results"></a>

Visual outcomes of the project include:

- Sample Labelled Images
- ResNet-34 Model Learning Rate
- Model Learning Outcomes per epoch
- Loss Metrics
- Classification Interpretation from ResNet34 Learning
- Confusion Matrix
- Classification Outcome
- Heatmaps

## Additional Information <a name="additional-information"></a>

For more information, please take a look at the narrative of our analysis in [our Jupyter notebook](./Malaria%20Detection%20using%20Cell%20Images%20Dataset.ipynb).

For any additional questions, please get in touch with **shaileshettyd@gmail.com**.

## Repository Structure <a name="repository-structure"></a>

```plaintext
├── README.md                                           <- The top-level README for reviewers
├── Malaria%20Detection%20using%20Cell%20Images%20Dataset.ipynb
│                                                       <- Narrative documentation of analysis in Jupyter notebook
├── https://www.kaggle.com/iarunava/cell-images-for-detecting-malaria
│                                                       <- Dataset link
└── images                                              <- Images generated from code
```

## Citation <a name="citation"></a>

If you use this project in your work, please cite it as follows:

```bibtex
@misc{Shailesh:2020,
  Author = {Shailesh Dhama},
  Title = {Spotting Malaria},
  Year = {2023},
  Publisher = {GitHub},
  Journal = {GitHub repository},
  Howpublished = {\url{https://github.com/ShaileshDhama/Spotting-Malaria}}
}
```
