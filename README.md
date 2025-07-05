# License Plate Detection Using Image Segmentation

This Python program implements a license plate detection system using classical image processing techniques. This program is developed as a final assignment for the Digital Image Processing course. It is based on the paper titled "Deteksi Plat Nomor Kendaraan Bermotor dengan Segmentasi Gambar" by Yasinta Oktaviana Legu Rema.

The implementation follows the methodology described in the referenced journal with slight improvements. This program has several features:

- Grayscale conversion using luminosity method
- Visualization of RGB components and histograms
- Otsu thresholding for binary conversion before edge detection
- Prewitt and Sobel edge detection
- Implementation of morphology using closing method (Dilation -> Erosion)
- Blob analysis using connected components
- ROI-based Otsu thresholding for refining license plate segmentation
- Contour detection and bounding box visualization for detected plates
- Side-by-side visual comparison across all stages of processing

Notes:
- This program only processes images named "2.jpg" by default. You can modify the filename directly in the code to accept custom filenames
- Some license plates may not be detected due to variations in image clarity, lighting, or angle. The method is still under improvement.

Sample vehicle images in the Notebook are taken from the Kaggle dataset: https://www.kaggle.com/datasets/caasperart/haarcascadeplatenumber