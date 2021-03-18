# 360 Degree Product Viewer

#### Description:

This project allows users to hover over an image and rotate its view, which could be used for e-commerce sites where users need to view different angles of a product.

#### Built With:

- HTML5
- CSS3

#### Getting Started:

1. Clone this repo to your computer.
2. Unzip the file into a new folder.
3. To use this project to view a different image, add your own product images to the img folder named numerically starting at 0.
4. Open the index.html file and change the img src names on the odd lines from 19-49 from for the image files you added.
5. This project uses 16 pictures. If you have fewer images in your project, remove sets of span + img code in the index.html file accordingly. Add additional sets of span + img code if you have more than 16 images. For example: remove or comment out lines 48-49 if you only have 15 images, but copy lines 48-49 and add them below if you have 17 images.
6. If you added extra code because you had more images, change the variable number to increase sequentially on even lines from 50 onward from --i:15 to --i:16, etc.
7. If you added more or fewer images, open the style.css file and change the property code on lines 34 and 35 to match the number of images you used. For example: if you used 17 images instead of 16, on line 34 change left: _calc(100% / 16 \* var(--i))_ to left: _calc(100% / 17 \* var(--i))_.

#### Acknowledgements:

The code for this project was inspired by a YouTube tutorial, which was enhanced by changing the product and adding additional images for improved rotation and viewing.
