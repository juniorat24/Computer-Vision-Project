# Face Detection API

This is a FastAPI-based face detection application using OpenCV.


## Installation

1. Install dependencies:
   ```sh
   pip install -r requirements.txt


2. Run the API
   python app.py

## Usage
Send a POST request with an image file to /detect_faces/ to detect faces.

## Deployment
To deploy on a server, use Uvicorn:
*uvicorn app:app --host 0.0.0.0 --port 8000 --reload
	 
