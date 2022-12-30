# invisibility-cloak

# Invisible Cloak with OpenCV

This project uses the OpenCV library to create an "invisible cloak" effect, where a person wearing a cloak appears to disappear when viewed through the camera. The cloak is achieved by replacing the pixels in the frame that are within a certain range of colors with the background frame.

## Prerequisites

To run this project, you will need to have the following libraries installed:

- OpenCV
- Numpy

You will also need a webcam or video capture device to use the script.

## Running the Script

To run the script, use the following command:

python invisible_cloak.py


The script will open a window showing the webcam feed, and you can hold up a cloak in front of the camera to see the invisible cloak effect in action.

## Customizing the Color Range

The color range of the cloak can be customized by modifying the `lower_color` and `upper_color` variables in the script. These variables should be set to the lower and upper bounds of the HSV color range that you want to include in the cloak. You can use a tool like [Color Picker](https://htmlcolorcodes.com/color-picker/) to help find the appropriate HSV values for your cloak.

## Additional Notes

Note that the invisible cloak effect may not work perfectly in all lighting conditions, as the color range detection can be affected by variations in lighting. Adjusting the color range and/or using additional image processing techniques may improve the performance of the cloak in different lighting conditions.
