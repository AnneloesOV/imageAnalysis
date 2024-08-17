The image in this repository illustrates the image analysis method, that I coded in MATLAB. The method is based on a short description in a research paper. 

The goal of the method is to find the average size of the ice crystals. For that, the contours of the ice crystals need to be found. 

Description of the image: 

Illustration of IRI image analysis method. 
(A) Schematic illustration of ice grain with inner (pink), outer (green), and intermediate contour (red). 
The intermediate contour is constructed from the inner contour by adding half the rim thickness in the direction from the centroid. 
(B) Flatten operation to correct for inhomogeneous illumination of IRI micrograph. 
(C) Typical IRI micrograph of 30% (w/w) sucrose solution, after flatten operation. Boxes indicate parts shown in E and F. 
(D) The convex hull, the smallest polygon enclosing the component, is calculated for every component. When the area of the convex hull is more than 10% of the area of the original component it is taken out of the selection. 
(E) IRI imaging analysis steps include; 
i. background equalization, 
ii. conversion to binary image, 
iii. selection of ice grain components, which are shown in red, 
iv. selection of inner (pink) and outer contour (green) of ice grains, 
v. construction of histogram of smallest distances between the inner and outer contour, 
vi. construction of the intermediate ice crystal contour. 
(F) After constructing the intermediate contour misidentified small inclusions can often be discriminated from ice grains since they overlap with adjacent ice grains. Note that the small ice crystal grain at the top of the image is not taken out of the selection. 
(G) Final resulting image with centroids of identified ice grains plotted in blue, and intermediate contours plotted in red. 
