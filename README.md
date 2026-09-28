# License-Plate-Recognition
License Plate Recognition is a computer vision technology that detects, reads, and extracts vehicle registration plates from video feeds or digital photographs, converting them into structured text in real time.
This project utilizes CRAFT (Character Region Awareness for Text Detection) to detect the regioncs containing the individual characters.Once text regions are cropped by CRAFT, they are passed to EasyOCR’s default recognition network.The Convolutional Neural Network (CNN) acts as the feature extractor. Its job is to translate the raw visual image of cropped text into a mathematical representation that downstream models can understand.
This project utilizes 435 car images with randomized license plate to test the accuracy of the model.
