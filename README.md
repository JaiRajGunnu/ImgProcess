In this project we’ll be trying to separate the blue nuclei from an image of tissue stained with
hematoxylin and eosin (H&E). We’ll be classifying the RGB colors by K-means clustering and
then classify them in a*b* color space. We then create image which is segmented into colors
finally giving out the resulted blue nuclei. In this project we apply K-means clustering and
segment the given image in RGB format and then convert it into a*b* segmentation then
classify the image and produce the required image as output, in this case we apply k-means
clustering to separate blue nuclei from an image of tissue stained with hematoxylin and eosin
(H&E).

Clustering is a way to separate groups of objects. K-means clustering treats each object as
having a location in space. It finds partitions such that objects within each cluster are as close
to each other as possible, and as far from objects in other clusters as possible. You can use
the imsegkmeans function to separate image pixels by value into clusters within a colour space.
This example performs k-means clustering of an image in the RGB and L*a*b* colour spaces
to show how using different colour spaces can improve segmentation results. 
