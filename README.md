# Object Detection with MobileNet SSD

Welcome to my implementation of an object detector as part of The Sparks Foundation's Computer Vision and Internet of Things Internship. In this project, I leveraged the MobileNet SSD architecture to identify objects in images, videos, and via webcam.

## Features

- **Object Detection:** Utilizing the MobileNet SSD model to identify and classify objects in images, videos, and real-time via webcam.
- **Class Labels:** Detection includes a variety of common objects such as aeroplane, bicycle, car, person, and more.
- **User-Friendly:** Easily adaptable functions for predicting on images, videos, and live webcam feed.

## Getting Started

1. **Clone Repository:**
   ```bash
   git clone https://github.com/your-username/your-repository.git
   ```

2. **Download Pre-trained Model:**
   - Download the MobileNet SSD model from [here](https://gist.githubusercontent.com/mm-aditya/797a3e7ee041ef88cd4d9e293eaacf9f/raw/3d2765b625f1b090669a05d0b3e79b2907677e86/MobileNetSSD_deploy.prototxt.txt) (config) and [here](https://github.com/chuanqi305/MobileNet-SSD/blob/master/deploy.prototxt) (weights).
   - Place the downloaded files in the `Model` directory.

3. **Install Dependencies:**
   ```bash
   pip install opencv-python numpy matplotlib
   ```

4. **Run the Code:**
   - Open and run the `object_detection.py` script to start predicting on images, videos, or via webcam.

## Usage

### 1. Webcam Prediction

```python
predict_from_webcam(model=model)
```

### 2. Image Prediction

```python
image_path = 'path/to/your/image.jpg'
predict_image(image_path, model)
```

### 3. Video Prediction

```python
video_path = 'path/to/your/video.mp4'
predict_video(video_path)
```

Feel free to explore and contribute to this project. If you encounter any issues or have suggestions, please open an issue or submit a pull request. Happy coding# Object Detection with MobileNet SSD

Welcome to my implementation of an object detector as part of The Sparks Foundation's Computer Vision and Internet of Things Internship. In this project, I leveraged the MobileNet SSD architecture to identify objects in images, videos, and via webcam.

## Project Overview

- **Intern:** Oloyede Opeyemi Iremide
- **Internship Period:** December 2023

## Features

- **Object Detection:** Utilizing the MobileNet SSD model to identify and classify objects in images, videos, and real-time via webcam.
- **Class Labels:** Detection includes a variety of common objects such as aeroplane, bicycle, car, person, and more.
- **User-Friendly:** Easily adaptable functions for predicting on images, videos, and live webcam feed.

## Getting Started

1. **Clone Repository:**
   ```bash
   git clone https://github.com/your-username/your-repository.git
   ```

2. **Download Pre-trained Model:**
   - Download the MobileNet SSD model from [here](https://gist.githubusercontent.com/mm-aditya/797a3e7ee041ef88cd4d9e293eaacf9f/raw/3d2765b625f1b090669a05d0b3e79b2907677e86/MobileNetSSD_deploy.prototxt.txt) (config) and [here](https://github.com/chuanqi305/MobileNet-SSD/blob/master/deploy.prototxt) (weights).
   - Place the downloaded files in the `Model` directory.

3. **Install Dependencies:**
   ```bash
   pip install opencv-python numpy matplotlib
   ```

4. **Run the Code:**
   - Open and run the `object_detection.py` script to start predicting on images, videos, or via webcam.

## Usage

### 1. Webcam Prediction

```python
predict_from_webcam(model=model)
```

### 2. Image Prediction

```python
image_path = 'path/to/your/image.jpg'
predict_image(image_path, model)
```

### 3. Video Prediction

```python
video_path = 'path/to/your/video.mp4'
predict_video(video_path)
```

Feel free to explore and contribute to this project. If you encounter any issues or have suggestions, please open an issue or submit a pull request. Happy coding
