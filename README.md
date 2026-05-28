# Multimodal AI Image Captioning 🚀

This repository contains a lightweight, local web application that bridges the gap between heavy machine learning models and seamless front-end user interfaces using **Gradio**. 

## 🧠 About the Project
This app demonstrates a Multimodal Generative AI pipeline. It uses the Hugging Face BLIP model (Salesforce/blip-image-captioning-base) to take an uploaded image and automatically generate a contextual, descriptive text caption based on the visual features.

## 🛠️ Technologies Used
* **Python 3**
* **Gradio:** For rapid UI prototyping and web app deployment.
* **PyTorch & Torchvision:** For handling deep learning operations and tensor transformations.
* **Hugging Face Transformers:** For implementing the state-of-the-art pre-trained vision-language model.

## 🚀 Installation & Setup

To run this application locally, you will need Python installed. It is highly recommended to use a virtual environment.

**1. Clone the repository:**

```bash
git clone https://github.com/harshmishra-1702/gradio-image-captioning.git
```
```bash
cd gradio-image-captioning
```

**2. Create and activate a virtual environment:**

Windows:
```bash
python -m venv venv
```
```bash
.\venv\Scripts\activate
```

Mac/Linux:
```bash
python3 -m venv venv
```
```bash
source venv/bin/activate
```

**3. Install the required dependencies:**
```bash
pip install gradio transformers torch torchvision pillow requests
```

## 🎮 Usage

Ensure your virtual environment is active, then run the script from your terminal:

```bash
python caption_img.py
```

The terminal will output a local URL (e.g., http://127.0.0.1:5000). Click the link or paste it into your browser to interact with the UI.

(Note: The first time you run the app, it will take a few moments to download the BLIP model weights from Hugging Face).
