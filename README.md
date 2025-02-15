# Use-of-Computer-Vision-to-inforce-Safety-Violation using YOLO-NAS Object Detection

This repository demonstrates object detection using the YOLO-NAS model with custom class labels. The model predicts objects like "fire," "helmet," "person," "spillage," and "vest" in images, and outputs the results with bounding boxes and confidence scores.

## Installation  

### Prerequisites:
Make sure you have Python 3.6+ and the following libraries installed:

- PyTorch
- SuperGradients

### Install Dependencies:
You can install the required dependencies using pip:

- pip install torch
- pip install super-gradients
- Additionally, you might need to install other dependencies as per your environment.

### Files

- model/ckpt_best.pth: Pre-trained model checkpoint for YOLO-NAS. Download it from the link:  https://drive.google.com/drive/folders/1inm39gX8Izqod6hW4ffRf_zBv_A0ltCf?usp=sharing
- test.jpg: Sample input image for object detection (you can replace it with your own images).
- output.jpg: Image after processing, with bounding boxes drawn around detected objects.

### Usage

1. Clone the repository to your local machine:
- git clone https://github.com/ng-spurs2022/Use-of-Computer-Vision-to-inforce-Safety-Violation
2. Ensure the pre-trained model checkpoint (ckpt_best.pth) is placed in the model/ directory.
3. Prepare an image file (test.jpg) in the same directory (or provide the path to your image).
4. Run the inference.ipynb

### Results

After running the script, you will get the output image with detected objects marked by bounding boxes and class labels. The output image is saved as output.jpg.

### Troubleshooting

If you encounter issues with the model or dependencies, ensure you have the correct versions of libraries and that the model checkpoint is correctly placed in the model/ directory.
For performance issues, make sure you have a compatible GPU for faster inference or fall back to CPU mode if a GPU is unavailable.

### License

This project is licensed under the MIT License - see the LICENSE file for details.