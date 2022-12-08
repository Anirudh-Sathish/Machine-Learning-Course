# Tasks of Day 1 include the following :
2. This exercise is designed to make you familiar with multivariate normal distribution generation
and using the generated data.
- a. Generate 300 3-dimensional vectors that come from a normal distribution with
mean vector as [1 2 1]t and 3x3 covariance matrix as [5 0.8 -0.3; 0.8 3 0.6; -0.3 0.6 4]
- b. Make scatter plots of x1 vs x2, x1 vs x3, and x2 vs x3. Explain whatever relationships
you can gather from these plots.
- c. Calculate the mean vector and the covariance matrix using the 300 generated
points.

3. In this exercise, you will read an image of your choice using the PIL library, display it, and then
convert it to a numpy array. You will then work with only red plane of the array to:
- a. Extract a 32x32 patch from anywhere of your choice
- b. Extract the maximum pixel values along each row and column of the patch
- c. Generate a new patch whose pixel values are the cosine of the original patch values and display it.

4. In this exercise, you will create a pandas data frame by reading the data from the link:
https://www.statlearning.com/s/Auto.csv. Using the groupby command, you will calculate the
average mpg for different numbers of cylinders. You will also generate a scatter plot to show the
relationship between the mpg and the displacement.
5. You will generate a 3D plot similar to the one shown at
"https://matplotlib.org/stable/gallery/mplot3d/surface3d.html#sphx-glr-gallery-mplot3d-
surface3d-py" but with a different surface function of your choice. Feel free to play with different functions (Z function in the link)