```python
import numpy as np
import cv2 as cv

```


```python
img = cv.imread('grapes.jpg')
res = cv.resize(img,None,fx=2, fy=2, interpolation = cv.INTER_CUBIC)
```


```python
cv.imshow('img',res)
cv.waitKey(0)
cv.destroyAllWindows()
```


```python

```


```python

```
