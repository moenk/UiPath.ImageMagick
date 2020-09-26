# UiPath.ImageMagick
Wrapper to call ImageMagick binaries from UiPath for image operations

= Purpose =
This library enables UiPath to make use of ImageMagick binaries. ImageMagick is a free and open-source cross-platform software suite for displaying, creating, converting, modifying, and editing raster images. Created in 1987 by John Cristy, it can read and write over 200 image file formats. It and its components are widely used in open-source applications. Read more in the documentation on https://imagemagick.org/

= Installation =
Compile library and publish to Orchstrator. The Install activity is called on the first run to download and unzip ImageMagick to the target system.

= Usage =
Use the Magick activity to do image operations. You need to know the commands for ImageMagick! See Demo folder for examples for some operation you can do with ImageMagick.
