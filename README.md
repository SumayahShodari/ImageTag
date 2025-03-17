# ImageTag

This project utilizes the **BLIP (Bootstrapped Language-Image Pretraining)** model to generate captions for images. The system processes images and their corresponding captions using a dataset, leveraging deep learning to create meaningful text descriptions.

## Features
- **Custom Dataset Loading**: Reads image-caption pairs from a JSON file.
- **BLIP Model**: Uses Salesforce's BLIP model for image captioning.
- **PyTorch Dataset**: Converts images and captions into a format suitable for deep learning training.
- **Training & Evaluation**: Prepares data for model fine-tuning.
-**pre-tuned model**: fine-tuned model the serves a specific need (tagging lost items in the airport).
  
## Technologies Used
- **Jupyter**
- **Python**
- **PyTorch**
- **Transformers (Hugging Face)**
- **BLIP Image Captioning Model**
- **PIL (Python Imaging Library)**
- **JSON for annotation handling**
