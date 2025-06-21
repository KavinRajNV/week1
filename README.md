# week1

# AI Internship – Week 1: E-Waste Image Classification

## Objective
Build and train a Convolutional Neural Network (CNN) to classify electronic waste into categories like keyboard, mobile, mouse, and monitor using TensorFlow and Keras.

## Dataset
- 4 categories: keyboard, mobile, monitor, mouse
- Loaded using `image_dataset_from_directory`

## Model Summary
- CNN with Conv2D, MaxPooling2D, Flatten, Dense, and Dropout layers
- Achieved training and validation accuracy above 85%

## Achievements
- Built a CNN model from scratch using Keras
- Successfully trained on the 4-class dataset
- Saved the model using `model.save("e_waste_classifier_model.keras")`

## Output
- Visualized predictions using matplotlib to compare actual vs. predicted labels

## Files
- `e_waste_classifier_model.keras` – Saved trained model
- `Week1_Code.ipynb` – Contains all code for training and saving the model

## Next Steps (Week 2 Preview)
- Model evaluation with metrics like confusion matrix
- Data augmentation techniques
- Testing with custom or external images
