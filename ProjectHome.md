# Welcome to the JavaMagick project #

JavaMagick is a Java interface to [ImageMagick](http://www.imagemagick.org). It implements the most common image manipulation methods in a user friendly manner. It uses a JNI interface between Java and the [MagickWand API](http://www.imagemagick.org/script/magick-wand.php).

### Current Version ###
The project was created using ImageMagick version 6.7.0-10 (16 bit) but it should in theory work with previous and future versions (as long as the MagickWand API methods that it uses don't change).

### History ###
I was looking for a Java interface to ImageMagick and the only one I could find was [JMagick](http://www.jmagick.org). The problem with JMagick is that it crashes my Web server when I use it and also the project seems outdated. So I wrote my own interface and decided to "give back to the public".


### Binary distribution ###
I wrote the JNI dll in C using Visual Studio 10 on a Windows platform. I created a 32 bit and a 64 bit dll. I don't use Linux or Mac but if someone sends me the binaries I'll be happy to add them to the downloads section.