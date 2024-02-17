Background Removal using GrabCut
This Python script removes the background from an image using the GrabCut algorithm. The code processes an input image with an alpha channel (RGBA) or without it (RGB) and removes the background to leave only the foreground object(s).

Requirements
Python 3.x
OpenCV (cv2)
NumPy (numpy)
Matplotlib (matplotlib)
Usage
Make sure you have the required libraries installed. You can install them via pip:

Copy code
pip install opencv-python numpy matplotlib
Place the image you want to process in the same directory as the script, or specify the correct path to the image.

Run the script. It will automatically load the image, remove the background, and display the result.

Instructions
Ensure that the image you want to process is in RGB or RGBA format.
Adjust the coordinates of the rectangle in the script to fit the foreground object accurately and remove any remaining unnecessary background.
You can customize the script further based on your specific requirements or integrate it into larger projects.
