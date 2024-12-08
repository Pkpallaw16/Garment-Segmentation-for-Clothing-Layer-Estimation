# Garment Segmentation for Clothing Layer Estimation

Welcome! This repository outlines details of the my Computer Vision based project - Garment Segmentation for Clothing Layer Estimation.

## Project Summary
The project aims to estimate the percentage of human body area covered under clothing layers. In this project, we developed 2 deep learning models (Person segmentation model and Garment segmentation model), a technique to map human and garment masks and lastly, estimated clothing insulation percentage. The models were trained on DeepFashion2 dataset. The project report is available ![here]().

## My Contribution
1. Garment Segmentation Modeling: Trained Garment segmentation (Mask-RCNN) model on DeepFashion dataset which involved image data processing, scaling, model training and evaluation. 
2. Human-Garment mask mapping: Developed Intersection over Union (IoU) and thresholding based algorithm to map human and garment masks between multiple objects for images having more than on human objects. Mapping idea is drawn from ![YOLO paper](https://ar5iv.labs.arxiv.org/html/1506.02640). 
3. Clothing insultation estimate process design: Developed a technique to estimate the human body percentage covered by clothing layer. 
4. Research - I researched several published articles to learn state-of-the-art approaches for the above three tasks. No paper had done similar work as on task #3 hence, #3 is innovative technique.


## Approach
In this project two models are developed and final computation is based on the models outcomes:
1. Person segmentation model development ![image](https://github.com/user-attachments/assets/2716a238-f599-47cc-b065-3c568f358544)
2. Garment segmentation model development ![image](https://github.com/user-attachments/assets/c2fbf9a2-dad5-4ea8-869a-73e7b689305e)
3. Clothing insulation estimation ![image](https://github.com/user-attachments/assets/32b011c0-63f9-479b-8dbd-bc82624980f9)

## Result
The result achieved were of varying degree. Among all the categories of clothes, the best performances were found for the garments “trousers” and “short sleeve top”.

![image](https://github.com/user-attachments/assets/7151d37c-655e-4531-829d-a9af43fc5907)
![image](https://github.com/user-attachments/assets/4dfd8a97-7b34-4f32-b0e8-be84c4aa1932)
![image](https://github.com/user-attachments/assets/1d34e750-c2d1-4d07-8d9d-e1f5dd02c77e)

## Tools & Technologies
- **Programming**: Python
- **Frameworks/Libraries**: torchvision, PyTorch
- **Deep Learning Models**: Mask-RCNN
- **Neural Networks**: ViT, ResNet50, ResNet18, 
- **Data Sets**: Peen-Fudan, DeepFashion2
- **IDE**: Google Colab
