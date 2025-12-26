import cv2
import matplotlib.pyplot as plt

img = cv2.imread("lab3.png", 0)   # read in grayscale
edges = cv2.Canny(img, 100, 200)

plt.imshow(edges, cmap='gray')
plt.axis('off')
plt.show()
