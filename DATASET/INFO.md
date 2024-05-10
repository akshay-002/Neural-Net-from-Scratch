## Digit Recognizer Dataset Description

The digit recognizer dataset contains gray-scale images of hand-drawn digits, ranging from zero through nine. Each image is 28 pixels in height and 28 pixels in width, resulting in a total of 784 pixels. Each pixel has a single pixel-value associated with it, representing the lightness or darkness of that pixel, with higher numbers indicating darker shades. The pixel-values are integers ranging from 0 to 255, inclusive.

The dataset consists of two files: train.csv and test.csv. The "train.csv" file contains labeled data, with each row representing an image of a hand-drawn digit. The first column, labeled "label", indicates the digit drawn by the user, while the remaining 784 columns contain the pixel-values of the associated image.

Each pixel column in the dataset is named as "pixelx", where x is an integer between 0 and 783, representing the position of the pixel in the image. To locate a pixel on the image, the value of x is decomposed into i * 28 + j, where i and j are integers between 0 and 27, inclusive. Thus, "pixelx" is located at row i and column j of a 28 x 28 matrix, indexed starting from zero.

For example, "pixel31" indicates the pixel located in the fourth column from the left and the second row from the top of the image.

## Access the dataset here : 

## https://www.kaggle.com/competitions/digit-recognizer/data



