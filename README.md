
# Project Workflow Summary

- **Information Gathering:** Gathered images using Google Earth.
- **Image Collection:** Collected images for the project's dataset.
- **Image Preprocessing:** Prepared and processed images for further use.
- **Annotation:** Annotated the collected images for training the model.
- **Environment Setup:** Configured the environment for model training.
- **Data Training:** Divided collected data into 80% training and 20% testing datasets. Ran 60 epochs during training.
- **Data Testing:** Evaluated model accuracy and performance using the testing dataset.
- **Result Evaluation:** Analyzed model accuracy and metrics.

## Training & Testing Details

- **Data Division:** 80% training, 20% testing
- **Epochs:** Trained for 60 epochs
- **Accuracy:** Reached 76% accuracy at epoch 55, dropped to 60-65% afterward
- **Best Weight:** Stored weights from epoch 55 with 76% precision, 77% recall, and 76% F1 score.
- **Mean Average Precision (mAP@0.50):** Achieved 76%

## Results & Output Summary

- **Mean Average Precision (mAP@0.50):** 76%
- **Class-wise precision:**
  - Not-Used(westland): 80%
  - Arable(cultivated): 73%
  - None_arable (non-cultivated): 70%

The project involved collecting, preprocessing, annotating, and training a model using Google Earth images. The trained model achieved an overall mean average precision of 76%, with varying precision rates for different classes, notably 80% for wasteland, 73% for arable, and 70% for none_arable (non-cultivated). The highest accuracy was attained at epoch 55, and the model's performance slightly declined in subsequent epochs.

 ![detection2](https://github.com/sftSalman/Arable_land_and_nonarable_land_dectection_from_sataleite_images-/assets/33355278/b9e227fa-0b90-4839-a403-df6edecb89e4)
![detection](https://github.com/sftSalman/Arable_land_and_nonarable_land_dectection_from_sataleite_images-/assets/33355278/2b295cd7-ad35-4f60-852c-1f479d8ccdf4)


