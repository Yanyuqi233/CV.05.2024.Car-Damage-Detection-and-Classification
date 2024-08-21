# (Computer Vision 05/2024) Car Damage Detection and Classification
<div align="center">
  <img src="./Images/0024.jpeg" alt=" car image " width="50%" height="auto">
</div>

## Motivation and Goal
The **need for accurate vehicle damage assessment in the fleet management and insurance industries** drives our project. Leveraging our team’s expertise in data science and machine learning, we aim to **develop robust models** using curated datasets from platforms like Kaggle.

## Innovation
Our approach is innovative in several ways:
* Move beyond binary classification to include multiple classification tasks, categorizing damages into frontal, side, and rear categories for deeper insights. 
* Integrate deep learning models such as **DenseNet121, MobileNet-v2, ResNet-50, and CLIP** to improve classification accuracy and generalization.
* **Advanced preprocessing techniques** are employed to optimize model performance and avoid overfitting.

## Approaches
### Binary classification (distinguishes between nondamaged and damaged cars)
For the binary classification task:
* Compare the performance of DenseNet121, MobileNet-v2, ResNet-50, and CLIP against a baseline model.
* Conduct rigorous evaluations and metrics comparisons to assess the models’ effectiveness in accurately classifying vehicle damages.

### Multiple classification (identifies the type and location of damages (front, side, rear))
For the multiple classification task:
* Utilize ResNet-50 and CLIP models to categorize damages into different classes.
* Manually relabel datasets to ensure high-quality training data for multiclass classification, emphasizing the importance of data relevance and accuracy in our methodologies.

## Result and Discussion

### Binary classification
<div align="center">
  <img src="./Images/Binary a.png" alt=" Binary Classification Accuracy" width="50%" height="auto">
</div>
The trained, mature models perform well in solving this classification problem.

### Multiple classification
<div align="center">
  <img src="./Images/Multi-class.png" alt=" Multiple Classification ROC Curve" width="50%" height="auto">
</div>
The ResNet50 model performs well overall.

<div align="center">
  <img src="./Images/CLIP.png" alt=" Multiple Classification ROC Curve" width="50%" height="auto">
</div>
Poor accuracy with multi-damage localization but better than traditional ML methods.

Existing pre-trained traditional models (MobileNet, etc.) already perform well.
CLIP models are harder to train and require more data.
