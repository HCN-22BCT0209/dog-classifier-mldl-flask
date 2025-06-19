## Model Variants

This project provides two NASNetLarge-based models:

1. **Flatten Variant** – Uses a `Flatten()` layer before the final Dense layer  
2. **Global Average Pooling Variant** – Uses a `GlobalAveragePooling2D()` layer for reduced size and better generalization

---

### Download Trained Models

| Model Type               | Download Link                                                                                      | Suggested Path                            |
|--------------------------|----------------------------------------------------------------------------------------------------|--------------------------------------------|
| Flatten Variant          | [nasnet_flatten_best_model.h5](https://drive.google.com/file/d/1Ig2W2miWW2k_V98Jjh2GbBd74lePeOiW/view?usp=drive_link)           | /model/nasnet_flatten_best_model.h5        |
| GlobalAvgPooling Variant | [nasnet_globalavgpool_best_model.h5](https://drive.google.com/file/d/14F6iP_naBj4FB13dIeab5yZgH69GkIAn/view?usp=drive_link)     | /model/nasnet_globalavgpool_best_model.h5  |

> Note: If the `/model/` folder doesn’t exist, please create it manually before placing the `.h5` files.

---

### Training Notebook

Training for both variants was performed on Google Colab using transfer learning.  
You can view or edit the notebook here:

`training_notebook/dog_classifier_training.ipynb`
