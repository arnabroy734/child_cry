# Audio Classification to Identify Child Cry

## Overview
This project implements an audio classification model to identify child cries using the YamNet model as a feature extractor, followed by two dense layers for classification.

## Yamnet Model Architecture
- **Feature Extractor:** YamNet
- **Classifier:** Two dense layers
- **Number of Classes:** 3
  - **0:** Normal
  - **1:** Cry
  - **2:** Scream

## Performance
- **Test Accuracy:** 90%

### Class-wise Precision
- **Class 0 (Normal):** 0.918
- **Class 1 (Cry):** 0.81
- **Class 2 (Scream):** 0.92

### Class-wise Recall
- **Class 0 (Normal):** 0.97
- **Class 1 (Cry):** 0.90
- **Class 2 (Scream):** 0.79

