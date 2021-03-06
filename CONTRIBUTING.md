Contributing to CSS FilterLab
=====

To contribute pull requests back to Adobe, please fill out and submit the [Contributor License Agreement](http://html.adobe.com/webplatform/graphics/customfilters/cssfilterlab/dev/cssfilterlab-cla.html).

## CSS Styles
The project uses [SASS](http://sass-lang.com/) to streamline working with CSS files. 

You may edit the CSS files directly. However, if you want to contribute your changes back you'll need to make the edits in the corresponding SCSS files and use SASS to regenerate the CSS files.

Working with SASS:    

- [Install SASS](http://sass-lang.com/download.html) (requires Ruby)

- Tell SASS to watch the `style` folder and regenerate CSS files when you make changes to SCSS files  
    - `$ sass --watch --style expanded style/app.scss:style/css/app.css`

See the [SASS tutorial](http://sass-lang.com/tutorial.html) for more details on generating CSS files with SASS. 

Have fun!
