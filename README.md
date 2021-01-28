# Image-Reconstruction-using-Deep-Encoder-Decoder-Network
 a deep encoder-decoder network architecture on the CelebA dataset


Implemented a deep encoder-decoder network architecture on the
CelebA dataset. Used the aligned and cropped version of the dataset. That version has images of
size 218x178 each.
While reading the batches of images, first resize images to 128x128. We
want to learn to reconstruct a 128x128 original image from its cropped 128x64 version. Your network
will take vertically half of an image as input and output the full image. That is, the input image will have
a size of 128x64 and the output image will have a size of 128x128
