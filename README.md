Download Link: https://assignmentchef.com/product/solved-ece532-homework-4-histogram-thresholding
<br>
Write a computer program to threshold a grayscale image to obtain a bi-level image. Write your

own code for the steps of the algorithm; don’t use existing thæsholding-JVlated functions. Use

Kittler and Illingworth’s Kullback information minimization approach. You do not have to apply

the correction terms for tail truncation. Here’s a possible command-line user interface:

USAGE

thresh I-t T] infile outfile

T: user-specified threshold; € T 255;

default: T is automatically computed using Kittler’s method

infile: the input grayscale image

outfile: the output bi-level image

DESCRIPTION

If a fixed threshold is not specified, then it is automatically

computed by minimizing the Kullback information measure .

Specifically, the image is thresholded as follows:

= 255 if X[n] T

= if x [n] &lt; T

Submit the following items:

<ul>

 <li>Your commented source code files.</li>

</ul>

Run your program on the address . png image, and submit the thresholded image.

(You should also try your program on graybook . png, but don’t submit that image.)

<ul>

 <li>Show the threshold value that Kittler’s algorithm found for the address . png image.</li>

</ul>

Reference

<ol>

 <li>Kittler and J. Illingworth, “Minimum Error Thresholding,” Pattern Recognition, vol. 19, no. 1,</li>

 <li>41-47, 1986.</li>

</ol>

Recursive Update Formulas

mul

varl =

mu2

var2 =

( q1p (varlprev+(mulprev – mul) (mulprev-mul) )

(q2prev* (var2prev+(mu2prev -mu2) (mu2prev-mu2) )