# YOLOv5 Object Detection App

A lightweight, browser-based object detection app using a custom-trained YOLOv5 model. Built with Gradio and hosted on Hugging Face Spaces, this project supports detecting multiple objects like **Animals**, **Traffic Lights**, and **Waste Containers** with bounding boxes and confidence scores.

---

## 🚀 Demo

👉 [Try the Live App](https://huggingface.co/spaces/rajeev1/yolov5-object-detector)

![demo-preview](preview.gif) <!-- Optional: Add a preview GIF or screenshot here -->

---

## ✨ Features

* Upload single
* Detect objects with bounding boxes
* Show class names and confidence scores
* Export detection results as JSON
* Fast and intuitive interface using Gradio

---

## 📦 Tech Stack

* [YOLOv5](https://github.com/ultralytics/yolov5)
* [Gradio](https://www.gradio.app/)
* [Hugging Face Spaces](https://huggingface.co/spaces)
* Python, PyTorch, OpenCV, PIL

---

## 🛠️ Usage (Local Setup)

### 1. Clone the Repo

```bash
git clone https://github.com/your-username/yolov5-object-detection-app.git
cd yolov5-object-detection-app
```

### 2. Install Requirements

```bash
pip install -r requirements.txt
```

### 3. Add Model Weights

Place your `best.pt` YOLOv5 model in the root directory.

### 4. Run the App

```bash
python app.py
```

The app will be available at: `http://localhost:7860`

---

## 🧠 Custom Classes

This model is trained to detect:

* Animal
* Traffic Light
* Waste Container

You can change these inside `app.py`:

```python
class_names = ["Animal", "Traffic Light", "Waste Container"]
```

---

## 📁 Project Structure

```
├── app.py                 # Gradio app interface
├── best.pt                # Trained YOLOv5 model
├── yolov5/                # Cloned YOLOv5 repo folder
├── requirements.txt       # Python dependencies
├── README.md              # Project documentation
```

---

## 🌐 Hosted On Hugging Face Spaces

This app is also hosted on [Spaces](https://huggingface.co/spaces/rajeev1/yolov5-object-detector).
No need to install anything — just open and use!

---

## 🤝 Contributing

Feel free to fork the repo, improve the app or add new features.

---

## 📄 License

MIT License
