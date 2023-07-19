# CactiViT-materials
This repository contains the dataset that we prepared and employed in our [article](https://doi.org/10.1016/j.aiia.2023.07.002).

# About our work
The cactus is a plant that grows in many rural areas, widely used as a hedge, and has multiple benefits through the manufacture of various cosmetics and other products. However, this crop has been suffering for some time from the attack of the carmine scale Dactylopius opuntia (Hemiptera: Dactylopiidae). The infestation can spread rapidly if not treated in the early stage. Current solutions consist of regular field checks by the naked eyes carried out by experts. The major difficulty is the lack of experts to check all fields, especially in remote areas. In addition, this requires time and resources. Hence the need for a system that can categorize the health level of cacti remotely. To date, deep learning models used to categorize plant diseases from images have not addressed the mealy bug infestation of cacti because computer vision has not sufficiently addressed this disease. Since there is no public dataset and smartphones are commonly used as tools to take pictures, it might then be conceivable for farmers to use them to categorize the infection level of their crops. In this work, we developed a system called CactiVIT that instantly determines the health status of cacti using the Visual image Transformer (ViT) model. We also provided a new image dataset of cochineal infested cacti. Finally, we developed a mobile application that delivers the classification results directly to farmers about the infestation in their fields by showing the probabilities related to each class. This study compares the existing models on the new dataset and presents the results obtained. The VIT-B-16 model reveals an approved performance in the literature and in our experiments, in which it achieved 88.73% overall accuracy with an average of +2.61% compared to other convolutional neural network (CNN) models that we evaluated under similar conditions.

# The labeling strategy used
![Architecture of the data labeling used](https://github.com/AnasBerka/CactiViT-materials/blob/master/ArchiLabel%_%CactiViT.png?raw=true)

# Cite us

```
@article{BERKA202312,
title = {CactiViT: Image-based smartphone application and transformer network for diagnosis of cactus cochineal},
journal = {Artificial Intelligence in Agriculture},
volume = {9},
pages = {12-21},
year = {2023},
issn = {2589-7217},
doi = {https://doi.org/10.1016/j.aiia.2023.07.002},
url = {https://www.sciencedirect.com/science/article/pii/S2589721723000223},
author = {Anas Berka and Adel Hafiane and Youssef Es-Saady and Mohamed {El Hajji} and Raphaël Canals and Rachid Bouharroud},
keywords = {Cactus, Cochineal, Smartphones, Classification VIT, Deep learning},
}
```
