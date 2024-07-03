## Assignment: Introduction to Computer Vision with Python
## Objective
In this assignment, students will learn the basics of computer vision using Python. They will use the OpenCV library to perform simple image processing tasks such as reading, displaying, and manipulating images.

## Prerequisites
Basic knowledge of Python programming
Basic understanding of image concepts (pixels, color channels)
Tools and Libraries
Python 3.x
OpenCV library (opencv-python)
## Instructions
### Setup Environment

Install Python 3.x from python.org.
Install OpenCV library using pip:
bash
Copy code
pip install opencv-python
## Clone the Assignment Repository

Clone the assignment repository from GitHub Classroom:

`git clone <your-github-classroom-repo-url>`
Navigate to the cloned repository:

`cd <repo-name>`
### Task 1: Read and Display an Image

Write a Python script read_display.py that reads an image named sample.jpg from the repository and displays it in a window.
Use the following OpenCV functions:
cv2.imread()
cv2.imshow()
cv2.waitKey()
cv2.destroyAllWindows()
### Task 2: Convert Image to Grayscale

Write a Python script convert_grayscale.py that reads sample.jpg, converts it to grayscale, and displays the grayscale image.
Use the following OpenCV functions:
cv2.cvtColor()
Save the grayscale image as grayscale_sample.jpg.
### Task 3: Resize the Image

Write a Python script resize_image.py that reads sample.jpg, resizes it to half of its original dimensions, and displays the resized image.
Use the following OpenCV functions:
cv2.resize()
Save the resized image as resized_sample.jpg.
### Task 4: Draw Shapes on the Image

Write a Python script draw_shapes.py that reads sample.jpg and draws the following shapes on the image:
A red rectangle
A blue circle
Green text saying "OpenCV"
Use the following OpenCV functions:
cv2.rectangle()
cv2.circle()
cv2.putText()
Display the image with the drawn shapes and save it as shapes_sample.jpg.
## Submission

Ensure all the scripts (read_display.py, convert_grayscale.py, resize_image.py, draw_shapes.py) and the resulting images (grayscale_sample.jpg, resized_sample.jpg, shapes_sample.jpg) are committed and pushed to your GitHub Classroom repository.
Complete the README.md file with your name, student ID, and a brief description of each task.
