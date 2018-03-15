# Performance matters

## Project setup

This project serves an adapted version of the [Bootstrap documentation website](http://getbootstrap.com/). It is based on the [github pages branche of Bootstrap](https://github.com/twbs/bootstrap/tree/gh-pages).

Differences from actual Bootstrap documentation:

- Added custom webfont
- Removed third party scripts
- The src directory is served with [Express](https://expressjs.com/).
- Templating is done with [Nunjucks](https://mozilla.github.io/nunjucks/)

## Getting started

- Install dependencies: `npm install`
- Serve: `npm start`
- Expose localhost: `npm run expose`

## Master branche
In the master branche you can find the optimized site. For each feature I made a new branche and in the end I merged them with the master branche. Check the [AUDIT.md](https://github.com/s44s/performance-matters/blob/master/AUDIT.md) file to find out more about the process.
Branches I created:
* Minify CSS
* Custom fonts
* Minify JS
* Compress images

Branches I still have to create:
* Critical CSS

***

Overall, you can see the before and after results here:

### Before:
* 20 Requests
* 1.2 MB transferred
* Load: 30.75sec

![alt text](https://github.com/s44s/performance-matters/blob/master/src/images/overallbefore.png "Screen")

### After:
* 20 Requests
* 687 KB transferred
* Load: 19.04sec
![alt text](https://github.com/s44s/performance-matters/blob/css-blocking/src/images/overall-after2.png "Screen")
