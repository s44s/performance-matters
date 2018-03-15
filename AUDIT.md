***
## Custom fonts
Declan told us that they saved ~65% in custom web font file size using font subsetting. So I wanted to do the same for this site to see if I will get the same result. I started with subsetting the custom fonts. Tool: https://www.fontsquirrel.com/tools/webfont-generator

The weird thing I found out is that you can't pick the .woff, .woff2 and .svg font types. So I subset the font files that are able to generate. I downloaded the kit and this was the result:

![alt text](https://github.com/s44s/performance-matters/blob/custom-fonts/src/images/screen3.png "Screen")

I replaced the old .woff and .woff2 files for the subsetting files.


Secondly, I checked if the fonts only uses the font types .woff and .woff2. Other font types (.eot, .ttf, .otf) have been deleted.

The result was:
sourcesanspro-regular.woff2 9.47sec & 75.3kb > 3.11sec & 26.8kb

sourcesanspro-light.woff2 11.70sec & 74.5kb > 6.18sec & 26.3kb

Before:
![alt text](https://github.com/s44s/performance-matters/blob/custom-fonts/src/images/before.png "Screen")

After:
![alt text](https://github.com/s44s/performance-matters/blob/custom-fonts/src/images/after.png "Screen")
