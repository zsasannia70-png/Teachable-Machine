# Teachable-Machine
Supervised Learning
To create a professional GitHub README for your model, I have drafted a template below.

https://teachablemachine.withgoogle.com/models/sPza353fxT/

Since the Teachable Machine link itself is a "hosted" version (which often doesn't show the class names until you run it), I have used placeholders like `[Class 1]` and `[Class 2]`. **Please replace the bracketed text with the actual labels you trained (e.g., "Dog", "Cat", "Mask On", "Mask Off").**

---

# [Teachable Machine_ Bottle, Pen, Blank]

A custom machine learning model trained using **Google Teachable Machine**. This model is designed to recognize and classify [insert what it classifies, e.g., hand gestures / objects / facial expressions] in real-time using a webcam or image input.

## 🚀 Model Link

You can test the live model here:

[https://teachablemachine.withgoogle.com/models/sPza353fxT/](https://teachablemachine.withgoogle.com/models/sPza353fxT/)

## 📊 How it Works

This model was trained using a supervised learning approach. It categorizes inputs into the following classes:

* **Bottle:** 
* **Pen:** 
* **Blank:**

## Sample Pictures

<img width="373" height="748" alt="image" src="https://github.com/user-attachments/assets/6799b73d-07a1-4499-8e99-2ff64287452b" />

<img width="363" height="737" alt="image" src="https://github.com/user-attachments/assets/a2e4e8d3-515c-4b3c-a4db-6d8ef0126759" />

<img width="377" height="737" alt="image" src="https://github.com/user-attachments/assets/67dc3b10-bfc3-40a3-90a3-420f97efca92" />



## 🛠 Usage

### 1. Web Integration (JavaScript/p5.js)

You can integrate this model into your own website using TensorFlow.js.

```html
<div>Teachable Machine Image Model</div>
<button type="button" onclick="init()">Start</button>
<div id="webcam-container"></div>
<div id="label-container"></div>

<script src="https://cdn.jsdelivr.net/npm/@tensorflow/tfjs@1.3.1/dist/tf.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/@teachablemachine/image@0.8/dist/teachablemachine-image.min.js"></script>
<script type="text/javascript">
    const URL = "https://teachablemachine.withgoogle.com/models/sPza353fxT/";
    // ... (rest of your boilerplate code from Teachable Machine export tab)
</script>

```

### 2. Python Integration

To use this model locally in a Python script (requires `tensorflow` and `opencv-python`):

1. Export the model from Teachable Machine as a **Tensorflow / Keras** model (.h5 file).
2. Use the following snippet:

```python
from keras.models import load_model
from PIL import Image, ImageOps
import numpy as np

# Load the model
model = load_model('keras_model.h5')
# ... refer to the 'Export' tab in Teachable Machine for the full Python snippet

```

## 📂 Repository Structure

* `model/`: Contains the exported model files (if uploaded to GitHub).
* `samples/`: Examples of images the model can classify.
* `index.html`: A simple web implementation to test the model.

## 📝 License

This project is open-source and available under the [MIT License](https://www.google.com/search?q=LICENSE).

---

*Created with ❤️ using Google Teachable Machine.*
