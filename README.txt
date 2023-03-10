# The Shuffle Editor (https://shuffle.dev)

*** NOTE: npm commands overwrite the ./public directory. ***

1. Getting Started

Project's source files are placed in ./src/ directory. 
    * ./src/assets - default static files (eg. image placeholders). You should replace them with your own files.
    * ./src/tailwind/ - Tailwind config file used to build the theme. Variables used in Theme Customizer are located in tailwind.config.js file.

All your pages (templates) are stored in separated .pug or .html files (depends on your export preferences)
    * ./src/pug/*.pug 
    * ./src/html/*.html 

2. Installation

# Install dependencies
npm install 

# Run dev server with live preview (Browsersync)
npm run watch

# Or make a production build
npm run build

!!! If you want PurgeCSS to delete unnecessary CSS classes (and create a smaller CSS file as a result) set NODE_ENV to production, e.g:

# Make a production build and automatically use PurgeCSS to remove CSS classes that aren't used.
NODE_ENV=production npm run build

3. Contact

If you have found any bugs in the Shuffle Editor, have any questions, 
comments or ideas for new features, feel free to contact us:

support@shuffle.dev

