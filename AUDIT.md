# Audit Bootstrap Documentation site

Test details:
* Network throttle: Slow 3G
* Cache: disabled

***
## CSS
First of all, I checked in Chrome Dev tools how many request are recorded. I found out that the CSS files (especially the bootstrap.css) are taking too long, with a time of 7.40s.

![alt text](https://github.com/s44s/performance-matters/src/images/screen1.png "Screen")

So, I decided to minify the three CSS files. Tool: https://cssminifier.com/ And this was the result:

![alt text](https://github.com/s44s/performance-matters/src/images/screen2.png "Screen")

So, minifying the CSS files saved 1.25sec.
