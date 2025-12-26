import cv2
import matplotlib.pyplot as plt

img = cv2.imread("lab2.png")
blur = cv2.GaussianBlur(img, (9,9), 0)

plt.imshow(cv2.cvtColor(blur, cv2.COLOR_BGR2RGB))
plt.axis('off')
plt.show()
