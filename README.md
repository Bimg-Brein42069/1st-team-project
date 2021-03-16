# 1st-team-project

This is my first team project ever.The project involved converting a specific image format to another.Since this was given to us as a part of my first programming course, we were not expected to deliver a good output image(which we actually do :) ) 
This thing converts 8-bit .bmp to .ico(Yes, that was given to do)
P.S. transparency effect is a bit jank because for 8 bpp, it only specifies one bit for it(0 for opaque,1 for transparent), but since we were told to keep output              similar to input,I did not take this part seriously.
     since there are gimp and image-magick, I am not going to improve my source code but instead happily contribute for them :b
execution: make       //to build obj files and executable
           ./bmptoico //execute the file
           srcname.bmp //name or full-path of image to convert
           //it outputs destination.ico
           make clean //to free the obj files and executable
