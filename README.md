# Lab1 -Noura Aldossari Group2
1. Why is reshaping important in NumPy?
Reshaping is important because it changes the shape of an array without changing the values.

2. How does slicing help in image processing?
Slicing helps us select a specific part of an image and work on it separately.

3. What would happen if brightness enhancement were applied to the entire image
The whole image would become brighter because all pixel values would increase.

4. Modify the code to decrease brightness of border pixels by 5 units.

img[0, :] -= 5
img[-1, :] -= 5
img[1:-1, 0] -= 5
img[1:-1, -1] -= 5

5. Compute the standard deviation of the final image matrix.

print("Standard Deviation:", img.std())
12.7856


