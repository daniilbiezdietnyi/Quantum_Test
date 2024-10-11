The task was to match two different Sentinel-2 images.
The key idea was to use the 11th or 12th bands, as they are more stable with respect to seasonal changes in the images. We then extracted feature maps by processing the band images through a ResNet50 model with a custom output layer, followed by using SIFT to detect matches. At the end we plotted the matches on the original images.

Use requirements.txt for setup.
