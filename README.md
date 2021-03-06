# My personal page
This personal page shows my
- contacts
- basic personal info
- some coding for fun in github
- blog

This page is forked from startbootstrap (https://startbootstrap.com/template-overviews/resume/). 

## What the page has
- Google Analytics
- Blog API to blogspot.com

## Usage (Referenced from the author)
### Basic Usage

After downloading, simply edit the HTML and CSS files included with the template in your favorite text editor to make changes. These are the only files you need to worry about, you can ignore everything else! To preview the changes you make to the code, you can open the `index.html` file in your web browser.

### Advanced Usage

After installation, run `npm install` and then run `gulp dev` which will open up a preview of the template in your default browser, watch for changes to core template files, and live reload the browser when changes are saved. You can view the `gulpfile.js` to see which tasks are included with the dev environment.

#### Gulp Tasks
For newer npm, please run the following command first. (Related issue: https://github.com/gulpjs/gulp/issues/2246)
```
npm install natives@1.1.6
```

Gulp Tasks
```
- `gulp` the default task that builds everything
- `gulp dev` browserSync opens the project in your default browser and live reloads when changes are made
- `gulp css` compiles SCSS files into CSS and minifies the compiled CSS
- `gulp js` minifies the themes JS file
- `gulp vendor` copies dependencies from node_modules to the vendor directory
```

#### Build the minimal package
```
. build_patch.sh
```

## Reference
1. (https://startbootstrap.com/template-overviews/resume/). 