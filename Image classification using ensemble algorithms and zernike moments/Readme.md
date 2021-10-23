# Image classification using ensemble algorithms and zernike moments 
## Zernike moments
Zernike moments are features extracted by mapping the input image onto a complex set of Zernike polynomials.
Computing Zernike moments from an input image involves three steps. 
1.	The computation of the radial polynomials
2.	The computation of the Zernike basis functions
3.	The computation of the Zernike moments by mapping the image onto the Zernike basis functions [[1]](https://www.kaggle.com/smeschke/four-shapes).

## Dataset
To illustrate the use of zernike moments in shape recognition, we will use the Four Shapes dataset. This dataset contains 14970 samples of four classes: circles, squares, stars, triangles and the rotated version of each.. 
[link to the data](https://github.com/NoreddineDamane/Computer-Vision/blob/master/Feature%20Extraction%20Using%20Zernike%20Moments/images%2Bdoc/1-s2.0-S0031320306001166-main.pdf)

![](https://github.com/NoreddineDamane/Computer-Vision/blob/master/Image%20classification%20using%20ensemble%20algorithms%20and%20zernike%20moments/four%20shapes.PNG)

## Feature extraction
