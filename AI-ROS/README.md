# 🤖 AI-ROS Tasks

## Task 1: Image Recognition Model
**Goal:** Train an image classifier (2 classes) using Teachable Machine, export to Keras, and run predictions via a Python script.

**Tools:** Teachable Machine, TensorFlow/Keras, `tf_keras`, Google Colab

**Steps:**
1. Trained model on Teachable Machine with 2 classes.
2. Exported model → TensorFlow → Keras (`keras_model.h5`, `labels.txt`).
3. Wrote `Image Recognation Model(Task1).ipynb` to load the model and predict image class.
4. Fixed a Keras version-compatibility issue by installing `tf_keras` (legacy Keras 2) and setting `TF_USE_LEGACY_KERAS=1`.

**Result:**
```
Predicted class: Class 1
Confidence score: 96.82%
```

**Files:** `Image Recognation Model(Task1).ipynb`, `keras_model.h5`, `labels.txt`, `Output.pdf`

**Status:** ✅ Completed

---

## Task 2: _(coming soon)_

---

## Task 3: _(coming soon)_
