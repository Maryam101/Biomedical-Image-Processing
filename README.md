# Biomedical-Image-Processing
The python application developed in this task is aimed at performing image analysis operations on medical images in DICOM format.

The application includes the following functionalities:

1. Reading Patient and Image Information: The application reads the DICOM images and extracts patient information and image information. This includes information such as patient name, ID, age, sex, and image modality, as well as image-specific information such as shape, sampling, pixel aspect ratio, and field of view.

2. Image Exploration: The application enables the user to explore the medical image by slicing it to view from different planes. This allows the user to visualize the 3D image in different 2D planes.

3. Image Enhancement: The application enhances the medical image by applying appropriate morphological operations such as erosion, dilation, opening, and closing. The application shows the histogram before and after the operation and writes a conclusion about the effects of these operations on the image.

4. Feature Detection: The application allows the user to apply their own filter and mask for feature detection. This enables the user to detect specific features in the image that are of interest.

5. Object Segmentation: The application extracts and segments the object of interest (e.g., tumor) from the medical image. This is achieved using techniques such as thresholding, region growing, and active contours.

6. Object Measurement: The application measures the size of the object of interest, the distance transformation, and the center of mass of the object. This provides quantitative information about the object of interest that can be used for diagnosis and treatment planning.
