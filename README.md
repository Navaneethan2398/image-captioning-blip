# image-captioning-blip
**Project Overview**

This project generates natural language captions for images using a pretrained vision-language model.
The system takes an image as input and produces a descriptive caption explaining the content of the image.

The model used in this project is BLIP (Bootstrapping Language Image Pre-training), which combines computer vision and natural language processing to understand images and generate captions.

**Model Used**

* This project uses the BLIP Image Captioning Base model from Hugging Face.
* BLIP is a vision-language model designed for tasks such as:
* Image captioning
* Visual question answering
* Image-text retrieval

**Technologies Used**

* Python
* Hugging Face Transformers
* PyTorch
* PIL (Python Imaging Library)

**Project Structure**

image-captioning-blip/
│
├── image_cap.py # Python script for caption generation
├── nature.jpg # Example input image
├── requirements.txt # Required Python libraries
└── README.md # Project documentation

**How to Run**

Run the Python script: python image_cap.py
