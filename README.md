# DFS Landing Pages
Landing pages for the DFS initiative

# Getting Started 
- Install Gulp `npm install gulp -g`

If you are new to Gulp, learn more about the project building tool: http://gulpjs.com/. 

- Install the dependencies `npm install`
- Run gulp to build the project: `gulp compile`
- Or make Gulp watch all of your changes and build everything automatically: `gulp dev:watch`

# File Structure
```
 Root/
  |--bower_components/    //-- The bower served dependencies
  |  |--bootstrap
  |  |--filterizr         //-- A plugin to enable portfolio works filtering
  |  |--jquery
  |  |--slick-carousel    //-- The slider plugin
  |  |--webfontloader     //-- A tool to load fonts asynchronously
  |
  |--src/
  |  |--css/              //-- SCSS styles
  |  |--js/               //-- JS logic
  |  |--templates/        //-- A Jade template for each component 
  |  |--img/              //-- Raw images and icons
  |
  |--build/               //-- The folder with a successfully compilated project
  |  |--css/              //-- Compiled and minified CSS with SVG icons base64-encoded
  |  |--js/               //-- Compiled and minified JS
  |  |--fonts/            //-- Any Local Fonts (not google fonts)
  |  |--img/              //-- Compressed images
  |  |--index.html        //-- Compiled collection of all the components
  |
  |--gulpfile.js          //-- The Gulp configuration file
  |--package.json         //-- Node.js dependencies to process compiling
  ```

