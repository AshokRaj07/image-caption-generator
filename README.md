# 🖼️ Image Caption Generator

An AI-powered image captioning application that generates natural-language descriptions of images using pretrained vision-language models.

## About

The Image Caption Generator is a Python-based application that uses deep learning and computer vision to understand image content and generate meaningful text descriptions.

The application integrates pretrained BLIP and Qwen2-VL models and provides an interactive interface built using Streamlit.

Users can upload their own images or select sample images and generate captions automatically.

## Features

- Upload images in JPG, JPEG, PNG, and WebP formats.
- Select sample images.
- Generate captions using pretrained BLIP models.
- Generate captions using Qwen2-VL.
- View alternative generated captions.
- Regenerate captions.
- Adjust advanced model settings.
- Optional comparison with a Flickr8k CNN + LSTM baseline.

## Technologies Used

- Python
- Streamlit
- PyTorch
- Torchvision
- BLIP
- Qwen2-VL
- Pillow

## Project Structure

```text
image-caption-generator/
│
├── app.py
├── blip_captioner.py
├── qwen_captioner.py
├── requirements.txt
├── README.md
├── .streamlit/
├── examples/
└── images/
```

## How It Works

1. The user uploads an image or selects an example.
2. The application processes the selected image.
3. A pretrained vision-language model analyzes the image.
4. The model generates a natural-language description.
5. The generated caption and alternative captions are displayed.
6. Users can regenerate captions or experiment with advanced settings.

## Installation

Clone the repository:

```bash
git clone https://github.com/YOUR-USERNAME/image-caption-generator.git
```

Navigate into the project directory:

```bash
cd image-caption-generator
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

## Run the Application

Start the Streamlit application:

```bash
streamlit run app.py
```

The application will open in your web browser.

## Model Information

The application supports:

- **BLIP:** A pretrained vision-language model used for image understanding and caption generation.
- **Qwen2-VL:** A vision-language model capable of processing image inputs and generating textual descriptions.
- **Flickr8k CNN + LSTM:** An optional baseline implementation using ResNet50 for image feature extraction and an LSTM decoder for caption generation.

## Screenshots

![Image Caption Generator](images/image11.jpeg)

## Future Improvements

- Add more image-captioning models.
- Improve caption quality and accuracy.
- Support batch image captioning.
- Add downloadable captions.
- Improve model comparison and evaluation.

## Learning Outcomes

- Understanding vision-language models.
- Working with pretrained deep-learning models.
- Image preprocessing using Python.
- Integrating PyTorch models into web applications.
- Building interactive applications using Streamlit.
- Understanding image caption generation.

## Note

Generated captions may not always accurately represent every detail in an image. Results should be verified.
