# Object Detection Project with YOLOv8

## Setup Instructions

1. Extract all files from the zip
2. Run `python setup_env.py` to create a virtual environment with all required packages
3. Activate the virtual environment:
   - Windows: `venv\Scripts\activate`
   - Linux/Mac: `source venv/bin/activate`
4. Run the model: `streamlit run load_model.py`

## Files Included
- `best_model.pt`: The trained YOLOv8 object detection model
- `load_model.py`: Code to load and make predictions with the model
- `requirements.txt`: Required Python packages
- `setup_env.py`: Script to set up virtual environment

## How to Use
After running the Streamlit app, you can upload an image to detect objects based on your trained classes.
The app will display the image with bounding boxes around detected objects.
