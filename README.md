UIImage-Additions
==================

These classes are UIImage categories written taken from Trevor's Bike Shed, then again from jchatard and modified/simplified. The resizing library has been updated to work with the iPhone 4 retina display.

See author post for explanation: http://vocaro.com/trevor/blog/2009/10/12/resize-a-uiimage-the-right-way/

It provides:

UIImage+Resize.h, UIImage+Resize.m
----------------------------------
Extends the UIImage class to support resizing (optionally preserving the original aspect ratio), cropping, and generating thumbnails. (iPhone 4 retina display support added in this branch)

UIImage+RoundedCorner.h, UIImage+RoundedCorner.m
----------------------------------
Extends the UIImage class to support adding rounded corners to an image.

UIImage+Alpha.h, UIImage+Alpha.m
----------------------------------
Extends the UIImage class with helper methods for working with alpha layers (transparencies).