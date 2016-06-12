# Website Performance Optimization portfolio project

## Description
This is a project for the Frontend Web Development Nanodegree from Udacity. The assignment was to optimize a given website using various techniques described below.

## Optimizations Made
Here is a list of some of the optimizations that were made to the site to improve its performance and load-time.

- Compressed all images using [compressor.io](https://compressor.io/compress).
- Added media query to only load print css when the user needs to print
- Made analytics load asynchronously
- Minified CSS, HTML and JS
- Removed font because the download was unnecessary
-

### JS Optimizations
- Reduced number of pizzas loaded on page to 50 (200 was way more than we needed)
- Moved Pagescroll calculation to a variable outside of the for loop because it was constant.
