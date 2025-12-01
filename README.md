# Semantic_Segmentation_CamVid
semantic segmentation model on the CamVid dataset using a ResNet-based architecture.

## Deadlines
- Presentation (Dec. 03, 2025)
- Report Due (Dec. 14, 2025)

## Dataset
CamVid Dataset [CamVid](https://www.kaggle.com/datasets/carlolepelaars/camvid). The dataset consists of urban driving videos with frame-level pixel
annotations for multiple classes, such as road, car, and building. Dataset is already split into training, validation, and
test sets. 

## Model Choice
Using a ResNet Backbone with a segmentation head, Fully Convolutional Network (FCN), combining ResNet’s feature extraction capability
with a segmentation layer. 

## Implementation Requirements
- Using data augmentation to improve model robustness.
- Train your model on the CamVid dataset, tracking training and
validation performance.
- Measure model performance using metrics such as Intersection over Union (IoU) and pixel accuracy.

## Deliverables
- **Code:** A clean, well-documented Python codebase implementing the
model, data preprocessing, and evaluation.

- **Report:** A brief report (2-3 pages) that includes:
  - An introduction to semantic segmentation and the chosen model.
  - Data preprocessing and augmentation details.
  - Description of the training procedure and hyperparameters.
  - Evaluation metrics and results.
  -  A discussion on model performance and possible improvements.

- **Presentation:** A short presentation (7-10 minutes) summarizing your approach, results, and insights.
  
- **Demo:** A short demo where a user gives an image as input, and the
model should return the segmentation map which can further be
visualized.
