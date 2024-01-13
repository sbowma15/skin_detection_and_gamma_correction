# Skin Detection and Gamma Correction

## Overview
This Python script performs skin detection using RGB thresholding and gamma correction with the LUV color space. The program compares an original image with itself and four altered copies to observe the effects of various modifications such as Gaussian noise, uniform noise, salt and pepper noise, and contrast stretching.

## Dependencies
- OpenCV (`cv2`)
- NumPy (`np`)
- Matplotlib (`plt`)
- Math (`math`)
- Random (`random`)
- Google Colab patches (`cv2_imshow`)

## Usage
1. Ensure you have the required dependencies installed.
2. Replace the file paths in the script with the paths to your input images.
3. Run the script to see the results of skin detection and gamma correction.

## File Description
- `skin_detection_and_gamma_correction.py`: The main script containing skin detection and gamma correction methods.

## Method Descriptions
- `luv_space_gamma(src, gamma)`: Applies gamma correction to the LUV color space.
- `skin_rgb_threshold(src)`: Performs skin detection using RGB thresholding.
- `find_local_min(hist)`: Finds local minima in the histogram of luminance values.

## Results
The script displays the original images, images after gamma correction, and the final skin detection results using RGB thresholding.

## Notes
- The script assumes that you have images named "face_good.bmp" and "face_dark.bmp" in the specified file paths.

Feel free to modify the script and adapt it to your specific use case.
