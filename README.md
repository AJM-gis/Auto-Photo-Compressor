# Auto-Photo-Compressor

1. Script Overview

- This script allows you to compress images ready for use on a website, or within a web-gis application.
- It has two separate methods for compression depending on image type. 
- It can distinguish between a typical 2D "flat" image as well as "photo-sphere" or "360" images and deal with them accordingly.
- It is also capable of dynamically generating the html, and js files required to host the individual "photo-sphere" images that it finds.
- Outputs include a CSV file holding the data for the images (directory of original image, image name, directory of compressed image file). and a corresponding SHP file containing the same data.
