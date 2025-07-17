# 🦷 Dental X-ray AI Assistant

This project uses deep learning to detect dental caries (cavities) in periapical dental X-ray images.

##  Objective
To assist dentists by automatically identifying signs of tooth decay using computer vision and provide visual evidence via Grad-CAM.

##  Features
- Object detection with YOLOv8
- Real-time predictions on dental X-rays
- Visual explanations (Grad-CAM)
- Streamlit interface for easy use

##  Folder Structure
project/
├── data/
├── notebooks/
├── model/
├── app/
├── reports/
├── README.md


##  Getting Started

1. Clone the repository
2. Install dependencies: `pip install -r requirements.txt`
3. Place dataset in `data/images/`
4. Train model or run Streamlit app

##  To-Do
- [ ] Load and annotate dataset
- [ ] Train YOLOv8
- [ ] Visualize predictions
- [ ] Integrate Grad-CAM
- [ ] Deploy with Streamlit
