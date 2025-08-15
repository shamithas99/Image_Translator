Image translation refers to a technology where we can translate the text on images (posters, banners, menu list, sign board, document, screenshot etc.).
This is done by  pre-processing of the image followed by  segmentation to extract the text contained in the image and then translating the text into a language of choice.

To read text written in English from an Image and translating it into Kannada language.

Pre-processing:
The aim of pre-processing is an improvement of the image data that suppresses all the unwanted distortions and enhances some image features important for further processing.

Segmentation is an important process in image recognition, its referred to the isolation of the position of the words within the image, and then the extraction of each letter individually.

1: Horizontal segmentation
2:  Vertical segmentation

Correlation
The segmented image is resized to the size of the template provided and correlated with the template image using matlab function corr2. This is stored in an array. After this we find the index value and if the index value matches to the condition a new text file is created and the letters are written in the file.
