# Fullpage-Boilerplate

A full-screen scrolling website boilerplate built using [fullPage.js](http://alvarotrigo.com/fullPage/) and [Velocity.js](http://julian.com/research/velocity/).

It comes with useful gulp tasks that automatically compile sass, bundle javascript modules, compress images, reload browsers and so on.
With the help of this boilerplate, you can build a wonderful full-screen scrolling website in a very short time.

![Screenshot](https://raw.githubusercontent.com/panteng/fullpage-boilerplate/master/screenshot.jpg)

## Live Preview

[Click Here](http://panteng.me/demos/fullpage-boilerplate)

## Dependencies

1. [Font Awesome](https://fortawesome.github.io/Font-Awesome/)     --> Icon font set.
2. [fullPage.js](http://alvarotrigo.com/fullPage/)      --> The full-screen scrolling engine.
3. [jQuery](https://jquery.com/)           --> Used for manipulating DOM, also as the dependency of fullPage.js.
4. [Normalize.css](https://necolas.github.io/normalize.css/)    --> Used for CSS resets.
5. [Velocity.js](http://julian.com/research/velocity/)      --> The animation engine.

## Directory Layout

    /bundles
        bundle.css                  --> Generated by gulp task 'dev'. Contains all styles the project needs.
        bundle.js                   --> Generated by gulp task 'dev'. Contains all scripts the project needs.
    /fonts                          --> Contains all fonts the project needs. Some of the fonts may be grabbed from node_modules. Such as font awesome.
    /images                         --> Contains all images the project needs.
    /javascripts
        /animations                 --> Contains all scripts that control animations.
            section-1.js            --> Controls the animations of section 1.
            section-2.js            --> Controls the animations of section 2.
            section-3.js            --> Controls the animations of section 3.
        main.js                     --> The entry point javascript file. Contains global settings and project bootstrapping.
    /node_modules                   --> Contains 3rd party dependencies.
    /scss                           --> Contains all scss files the project needs.
    .gitignore
    gulpfile.js                     --> Gulp tasks.
    index.html                      --> The html structure of this project.
    package.json
        

## Getting Started

1. Install dependencies:

        npm install

2. Start gulp task:

        gulp dev   
       
        
## Getting Ready For Production

1. Minimize files using gulp task:

        gulp prod

2. Upload files to your server and run:

        npm install --production
        
   Add `--production` tag to only install dependencies that are needed for production environment.


## License

MIT
