```python
import cv2
import numpy as np
# Load the image
img = cv2.imread('grapes.jpg')
# Check the datatype of the image
print(img.dtype)
# Subtract the img from max value(calculated from dtype)
img_neg = 255 - img
# Show the image
cv2.imshow('negative',img_neg)
cv2.waitKey(0)




```

    uint8
    


```python

```


```python

```
