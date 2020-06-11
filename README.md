# Invisible-cloak

A simple project using OpenCV to create the famous Harry Potter's invisble cloak effect.
The code has been given in the jupyter notebbok file (invisible cloak.ipynb). The code is well commented at each step and is easy to understand.

This project uses the technique which is opposite to the green screening. In green screening, we remove background but here we will remove the foreground frame.
Simple steps involved are:
1. Capture and store the background frame .
2. Detect the colored cloth(here we are using red colored cloth) in each frame.
3. Replace out the colored cloth by generating a mask in each frame. 
4. Generate the final output for the magical effect.

To know more about the above steps refer to: https://opencv-python-tutroals.readthedocs.io/en/latest/py_tutorials/py_imgproc/py_colorspaces/py_colorspaces.html
This link will also help you to find the HSV(hue, saturation, Value) values for other colors as well.

Some instructions while capturing video:
1. While making the video, try to first capture the background for atleast say 15-20 seconds, for a clear background capture.
2. Try to keep moderate brightness level during video capture, neither too dull nor too bright.
3. Adjust the color values according to the color of the cloth.

Once you run the code, wait for a few seconds and then you will be invisible.

Hope you Like it!
Thanks.
