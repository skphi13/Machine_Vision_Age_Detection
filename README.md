# Machine_Vision_Age_Detection
The supermarket chain Good Seed would like to explore whether Data Science can help them adhere to alcohol laws by making sure they do not sell alcohol to people underage. We will build a model with the ImageDataGenerator and a GPU Platform to train the model. 

## Data Description
- `/datasets/faces/labels.csv`
- `/datasets/faces/final_files/`

## Conclusion

The model trained on 6,073 images and validated on 1,518 images showed steady improvement over 20 epochs, achieving a training mean absolute error (MAE) of 2.01 years and a validation MAE of 5.82 years. Early epochs exhibited fluctuations in validation loss, suggesting potential overfitting or data complexity, but later epochs showed better stabilization. While the model demonstrates reasonable accuracy in predicting real ages, with an error margin of approximately 5–6 years, further improvements could be made through techniques like data augmentation, hyperparameter tuning, or early stopping to enhance generalization and reduce prediction error.
