# Face Detection Project

A Python-based face detection application using OpenCV and Haar Cascades to detect faces, eyes, and body parts in images and webcam feeds.

## Features

- Face and eye detection in images
- Full body, upper body, and lower body detection
- Support for both single and multiple image processing
- Real-time webcam feed detection
- Visualization with both grayscale and RGB outputs

## Requirements

- Python 3.x
- OpenCV (cv2)
- Matplotlib
- Jupyter Notebook

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/faceDetection.git
   cd faceDetection
   ```

2. Install required packages:
   ```
   pip install opencv-python matplotlib jupyter
   ```

## Usage

### Using Jupyter Notebook

1. Open the Jupyter Notebook:
   ```
   jupyter notebook lib.ipynb
   ```

2. Run the notebook cells to:
   - Process images by providing image paths
   - Detect only faces in images
   - Use webcam for real-time detection

### Image Detection

To detect features in images, use the `detect_features()` function:

```python
image_paths = [
    "path/to/your/image1.jpg",
    "path/to/your/image2.jpg"
]
detect_features(image_paths)
```

### Webcam Detection

To start real-time detection using your webcam:

```python
detect_from_webcam()
```
Press 'q' to exit the webcam feed.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
