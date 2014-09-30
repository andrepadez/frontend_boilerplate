# Frontend Boilerplate

## Full solution for frontend project startup
* Grunt for automation
* browserify for nodejs style require and module.exports
* sass compiling
* BrowserSync and grunt-watch for serving and live-reload (with re-compilation)
* testem framework with Mocha and Chai  
* tests works with require due to some magic

## Usage
    
    //install dependencies
    npm install
    //run the tests
    npm install -g testem
    testem
    //or
    grunt test
    //run in dev mode
    grunt dev
