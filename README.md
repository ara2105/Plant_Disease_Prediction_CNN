# 🌿 Plant Disease Predictor 

A deep learning-based web application for identifying plant diseases from leaf images.  
## Features

- Image classification for plant disease detection
- User-friendly Streamlit web interface
- Supports multiple plant species
- Mobile-responsive design
- Model trained on PlantVillage dataset

## Dataset

This project uses the [PlantVillage Dataset](https://www.kaggle.com/datasets/abdallahalidev/plantvillage-dataset) from Kaggle containing:
- 38 classes of plant diseases
- Images in color, grayscale, and segmented versions
- Example classes: 
  - Apple Cedar apple rust
  - Corn healthy
  - Tomato Early blight

 ###Final Validation Results
| Metric              | Score       |
|---------------------|-------------|
| **Training Accuracy**        | 96.23%      |
| **Validation Accuracy**        | 88.23%      |
| **Loss**            | 0.5658      |
| **Training Time**   | ~9.5 mins   |

## Setup Instructions

1. **Clone this repository**
   ```bash
   git clone https://github.com/yourusername/plant-disease-predictor.git
   cd plant-disease-predictor
   ```
2. **Create a virtual environment**
   ```bash
   conda create -n ML python=3.12
   conda activate ML
   ```

4. **Install requirements**
   ```bash
   pip install -r requirements.txt
   ```
5. **Run the App**
```bash
streamlit run main.py
```
Test different Plant images and have fun!
