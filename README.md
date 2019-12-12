# SeamCarving

## Seam carving algorithm- content-aware image resizing.


### Implementation steps:

* calculate the energy of all pixels using color difference. Draw the energy bitmap.
* Using dynamic programming, calculate row by row the lowest energy value possible considering the "best" vertical seam leading to each  pixel in the image. Draw this energy map.
* Find and draw the seam with the lowest energy on the image itself, on the energy map and on the cumulative energy map.
* Create a smaller image, removing the seam from the original image. Repeat this process until the image is 1/4 in horizontal size. Draw a sample every ~20 pixels.
