***
## Custom fonts
Declan told us that they saved ~65% in custom web font file size using font subsetting. So I wanted to do the same for this site to see if I will get the same result. I started with subsetting the custom fonts. Tool: https://www.fontsquirrel.com/tools/webfont-generator

The weird thing I found out is that you can't pick the .woff, .woff2 and .svg font types. So I subset the font files that are able to generate. I downloaded the kit and this was the result:

![alt text](https://github.com/s44s/performance-matters/blob/minify-css/src/images/screen3.png "Screen")



Secondly, I checked if the fonts only uses the font types .woff and .woff2. Other font types (.eot, .ttf, .otf) have been deleted (not yet)
