**[Edge Detection]{.ul}**

1.  **Author's Name and Email.**

> Sahil Mirchandani
>
> Sahil.mirchandani\@hotmail.com

2.  **Purpose of the project**

> Edge Detection Using Sobel Operator

3.  **Method**

> Used Sobel Operator To perform edge detection on the given Images.
> Used gaussian matrix to compare the pixel values.
>
> Step 1: Convert the image into segments with 100% overlap
>
> Step 2: Automatically Find the threshold of the image. (To know more
> about threshold, refer to the Image Segmentation)
>
> Step 3: Find gaussian matrix in the x and y direction.
>
> Step 4: Apply the gaussian matrix (x & y) to the segments.
>
> Step 5: calculate the cumulative gradient i.e root of (gradient_x)^2^
> + (gradient_y)^2^.
>
> Step 6: if the cumulative gradient is greater than gradient then
> consider that an edge and color the edge white.
>
> I have used 3x3 matrix as default to detect the edges.

4.  **Results**

> For Video Frame 1:

  **Original image**                                                                                                                    **Edged image**
  ------------------------------------------------------------------------------------------------------------------------------------- -----------------------------------------------------------------------------------
  ![A person standing in a room Description automatically generated](media/image1.png){width="2.6666666666666665in" height="2.0in"}     ![](media/image2.jpg){width="2.6666666666666665in" height="2.0in"}
  ![A person standing in a room Description automatically generated](media/image3.png){width="2.6666666666666665in" height="2.0in"}     ![](media/image4.jpg){width="2.6666666666666665in" height="2.0in"}
  ![A car parked on a city street Description automatically generated](media/image5.png){width="2.5in" height="1.6666666666666667in"}   ![](media/image6.jpg){width="2.6665616797900262in" height="1.7774114173228346in"}
  ![A car parked on a city street Description automatically generated](media/image7.png){width="2.5in" height="1.6666666666666667in"}   ![](media/image8.jpg){width="2.6734142607174105in" height="1.7822626859142607in"}
