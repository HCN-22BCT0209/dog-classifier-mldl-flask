# Dog Classifier Flask App

A web-based dog breed classification tool built using **TensorFlow** and **Flask**.  
The model is trained on 120+ dog breeds using **NASNetLarge** and predicts the breed of an uploaded image.

---

## Features

- Upload a dog image and get instant breed prediction
- Classifies among 120+ dog breeds
- Deep learning powered (NASNetLarge backbone)
- Simple, clean Flask-based web UI
- Custom-trained model provided via external link

---

## Model

This project uses a fine-tuned NASNetLarge model trained via transfer learning.

 **Download the trained model file:**

🔗 [Download `nasnet_best_model.h5`](https://drive.google.com/file/d/1gFEzCJUA5OklZYMFw6U0c-DQMazp6lRN/view?usp=sharing)

> After downloading, place the file here:

/model/nasnet_best_model.h5


> Note: If the `model/` folder doesn't exist, create it manually.

---

## Training Notebook

Training was performed on Google Colab.  
You can view or modify the training notebook here:

[`training_notebook/dog_classifier_training.ipynb`](training_notebook/dog_classifier_training.ipynb)

---

## ⚙️ Requirements

You can install dependencies using `requirements.txt` (coming soon), or manually with:

```bash
pip install flask tensorflow numpy
