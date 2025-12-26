import cv2
import matplotlib.pyplot as plt
import numpy as np

img = cv2.imread("lab5.png", 0)
kernel = np.ones((5,5), np.uint8)
erode = cv2.erode(img, kernel, iterations=1)

plt.imshow(erode, cmap='gray')
plt.axis('off')
plt.show()
