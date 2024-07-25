# (Computer Vision 05/2024) Car Damage Detection and Classification
<div align="center">
  <img src="https://storage.googleapis.com/kagglesdsdata/datasets/278578/575693/data1a/training/00-damage/0028.JPEG?X-Goog-Algorithm=GOOG4-RSA-SHA256&X-Goog-Credential=databundle-worker-v2%40kaggle-161607.iam.gserviceaccount.com%2F20240724%2Fauto%2Fstorage%2Fgoog4_request&X-Goog-Date=20240724T055913Z&X-Goog-Expires=345600&X-Goog-SignedHeaders=host&X-Goog-Signature=5fef52fc6e2fa84b8c9cdca45d9d32c0744bba2355379cd6e4b20c96a218c6d9c089bdeb9980a651d3344d7f3b6f1b649a9da0f893b0dec752e4393bc8d4adcb4e0039c37fbfb23b6fec86ba6aa7058ccd2247442d35bf245072b8e406889ac27dec4ab8321658806efd09bcc694f072ba56e6ada0b1ef55c0e53e8f0409e5fb78b1259c724e7844c69e087fc012f70c66d40b9afbcc01a5481b5800c77d0bbf87a2a1054a4d6a1b458c9bccd660fc819a175dc13eea6d4c1555bdd0e91f73afad5a2e8b6395b727603ad426bec1748f37ffa0205b0fdbb4aa67cb83d510035fe5d597579953740bc46cc1a89d3b087684648fde0b248ee9b14766157fc6fc5c" alt="Car Damage Detection">
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
<div align="center">
  <img src="./Binary.png" alt=" Binary Classification Accuracy">
</div>
For the binary classification task:
* Compare the performance of DenseNet121, MobileNet-v2, ResNet-50, and CLIP against a baseline model.
* Conduct rigorous evaluations and metrics comparisons to assess the models’ effectiveness in accurately classifying vehicle damages.

### Multiple classification (identifies the type and location of damages (front, side, rear))
<div align="center">
  <img src="./Multi-class.png" alt=" Multiple Classification ROC Curve">
</div>
For the multiple classification task:
* Utilize ResNet-50 and CLIP models to categorize damages into different classes.
* Manually relabel datasets to ensure high-quality training data for multiclass classification, emphasizing the importance of data relevance and accuracy in our methodologies.
