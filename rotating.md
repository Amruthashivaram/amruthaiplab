develop a program to perform linear transformation
import cv2

```


```python
image = cv2.imread('panda.jfif')

```


```python
height, width = image.shape[:2]
center = (width/2, height/2)

```


```python
rotate_matrix = cv2.getRotationMatrix2D(center=center, angle=180, scale=1)


```


```python
rotated_image = cv2.warpAffine(src=image, M=rotate_matrix, dsize=(width, height))

```


```python
cv2.imshow('Original image', image)
cv2.imshow('Rotated image', rotated_image)

```


```python
cv2.waitKey(0)

```


```python
cv2.imwrite('rotated_image.jpg', rotated_image)

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```
![image](https://user-images.githubusercontent.com/95746548/148200481-a72c7dbf-ef0b-4bf8-87be-7ccc3a7aa660.png)
