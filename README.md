#  EXP 2 Histogram-Equilazation

Histogram Equalization is a technique in image processing used to improve the contrast of an image by adjusting the intensity distribution of pixels. It enhances the image's details in areas that are either too dark or too bright, making the image appear more balanced and visually clearer.

The process involves redistributing the pixel intensity values (brightness levels) to use the full range of intensities available. Typically, an image’s pixel intensity ranges from 0 (black) to 255 (white) in an 8-bit grayscale image. In many cases, images may have pixel intensities concentrated in a limited range, resulting in poor contrast. Histogram equalization helps to spread out the pixel values across the entire range, increasing the contrast.

Here’s how the method works:

Histogram Calculation: First, the histogram of the image (a graph showing the frequency of each pixel intensity) is computed.
Cumulative Distribution Function (CDF): The cumulative distribution function is calculated from the histogram. This function accumulates the probability distribution of pixel intensities.
Mapping Intensities: The pixel intensities are then mapped to new values using the CDF, ensuring that the entire intensity range is used.
Output Image: The result is an image with improved contrast, where the intensity values are spread more uniformly.
Histogram equalization is widely used in applications such as medical imaging, satellite imagery, and computer vision for improving image visibility and detail.
