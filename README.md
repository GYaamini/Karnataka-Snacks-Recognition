## About The Project

Food being an inseparable part of human's life, it is difficult for people to recognize and to find the recipe of traditional snacks descended by their ancestors. In this project, a food recognition system is implemented with 12 snacks originated in Karnataka, India where each snack has challenges like high inter-class similarities, high intra-class dissimilarities, image noise, and etc. The project is carried out using ResNet50 transfer learning technique.
To demonstrate the project, an android mobile application is developed which recognises the snack and gives recipe in Kannada and English.

---
# Deep Learning Approach for Karnataka Snacks Recognition
Dataset Classes  |  ResNet50 Output
:-------------------------:|:-------------------------:
![input](https://github.com/user-attachments/assets/81bc042c-1c42-4779-93b4-bbdf9be33c18) | ![Result1](https://github.com/user-attachments/assets/a2740160-c733-4bd5-95ed-de19c2ae1ee7)

Deep Learning Models Comparision | Test Accuracy Comparision  |  ResNet50 70-30 Data Split Confusion Matrix
:-------------------------:|:-------------------------:|:-------------------------:
![DL](https://github.com/user-attachments/assets/30035e7f-84b2-4726-aa8d-34cd11624c3d) | ![Resnet50 final](https://github.com/user-attachments/assets/a2ecf55c-2352-4dc9-ae55-9b2da26b576d) | ![ResNet50 - 7030 final](https://github.com/user-attachments/assets/fbbb464c-dca5-4b14-8252-2ac19baf83f2)

## Key Contributions  
- Proposed a novel Food Recognition transfer-learning model for recognising food with high intra-class dissimilarities and inter-class similarities within Karnataka Style Snacks.
- Manual Data Collection
- Achieved 94.5% test accuracy in handling unique regional variations and cultural food differences which is yet to be explored.  

## Tools Used  
`Python` `Tensorflow` `ResNet50`

## Resources  
- [Paper PDF](https://ieeexplore.ieee.org/document/10706576)
- DOI: 10.1109/CCEM60455.2023.00029

---
## Mobile App Usage

### Install the ನನ್ನ ತಿಂಡಿ.apk (Nanna Tindi) and input an image
[ನನ್ನ ತಿಂಡಿ.apk](https://drive.google.com/file/d/1Sl6U7PquFg4cWA97nV7f4RtgCGhP2BNE/view?usp=sharing)

---
![SnackRecognition and Recip](https://github.com/user-attachments/assets/1cf91e05-976c-4067-8f6c-6c4d7d1f560a)


### if the snack is recognised, the recognition and the recipe is presented as:

![Snack](https://github.com/user-attachments/assets/ca81e82c-7694-485c-bc4e-4a388e28e24f)

### if not, the result screen would be:

![NotASnack](https://github.com/user-attachments/assets/310ab2b2-205a-481e-b22e-f0e08cb9e08a)

---
