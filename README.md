# OptiCool-MachineLearning
# 👓 OptiCool 😎 - Stay in Style, See with Confidence (Team CH2-PS291) - ML Repository

Opticool Machine Learning Repository for Bangkit Capstone Project. Building face shape classifier Model
## 😎The Coolers of Machine Learning Bangkit Academy Capstone Team CH2-PS291
|            Member           | Student ID |        Path        |                    Role                    |                                                       Contacts                                                      |
| :-------------------------: | :--------: | :----------------: | :----------------------------------------: | :-----------------------------------------------------------------------------------------------------------------: |
| Rizky Intan Nurlita  | M008BSX1236 |  Machine Learning  |Machine Learning Engineer |[rizkyintan](https://github.com/rizkyintan)|
| Sayyidan Muhamad Ikhsan | M008BSY1064  |  Machine Learning  | Machine Learning Engineer | [sayyidan-i](https://github.com/sayyidan-i) |
| Ahmad Rosikh Al Muttaqy | M312BSY1903  |  Machine Learning  | Machine Learning Engineer | [creamysausage](https://github.com/creamysausage) |

## Tech Stack
![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-%23D00000.svg?style=for-the-badge&logo=Keras&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![PIL](https://img.shields.io/badge/PIL-%23150458.svg?style=for-the-badge&logo=pypi&logoColor=white)
![PIL](https://img.shields.io/badge/MATPLOTLIB-%23150458.svg?style=for-the-badge&logo=&logoColor=white)

## About 
We have model, eyeglassess frame, and recomendation algorithm in this repository
### Face Shape Classifier
- [Face Shape Classifier](https://github.com/Capstone-OptiCool/ML/blob/main/face_shape_classifier_fix.ipynb) 
(image classification) use MobileNet as the base model for transfer learning that is taken from [Keras](https://keras.io/api/applications/mobilenet/). The model also contains an additional layer that received output from the based model. We use datasets [Face Shape Image Dataset](https://drive.google.com/drive/folders/19dP85vtcz_JzkQMs6e9Z01WZzWchGOJo?usp=drive_link) that contains 3,981 face images.

### Eyeglasses Frame
- we scrapping around to get the eyeglasses 


  
## Model Performance
### Face Shape Classifier
#### Model Training Performance
![trainingaccuracy](assets/train_accuracy.png)
#### Performance after Fine Tuning
![finetuning_disease](assets/train_result.png)


### Performance Summary
Models | Accuracy | Val Accuracy
------------ | ------------- | -------------
Face Shape Classifier | 99.8 % | 83.5 %


## Run the ipynb in Google Colab
Dont need to install anything just follow the steps below
1. Download or clone this repository.
2. Open google colab
3. Import the ipynb file
4. Run the code

## Run in Local

1. Download the ipynb file or clone this repostitory
2. Run this locally using ex: jupyter notebook
3. Install all the dependencis
  ```
  ! pip install -r requirements.txt
  ```
4. Run all the code

## References 
1. 

