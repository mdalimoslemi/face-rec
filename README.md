# Python Face Recognition

A simple web application built with Flask that allows users to upload images and detects faces in them, highlighting the faces with green rectangles.

## Features

- Upload image files (JPG, JPEG, PNG)
- Face detection using OpenCV
- Display of original and processed images
- Count of faces detected

## Installation

1. Clone this repository:
```bash
git clone https://github.com/yourusername/Python-face-recognition.git
cd Python-face-recognition
```

2. Create a virtual environment (optional but recommended):
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

## Usage

1. Start the Flask application:
```bash
python app.py
```

2. Open your web browser and navigate to `http://127.0.0.1:5000`

3. Upload an image containing faces

4. View the processed image with green rectangles around detected faces

## Technologies Used

- Flask
- OpenCV (cv2)
- HTML/CSS
- Werkzeug

## License

[MIT](LICENSE)