## The Javascript Toolkit

This is an attempt to organize the recent explosion of Javascript based technologies and frameworks into a coherent toolkit to be used by a web application developer.

After some time discussing and studying some of the technologies we'd like to include in this toolkit, we realized that more important that the tool itself, **is the motivation that is behind that tool**.


| Need | Motivation | Tools | Related Tools |
|------|------------|-------|---------------|
| Scaffold	 | Several tools. Several ways. Several Practices. Need to organize, and give some good foundation - best practices, good design.	| [yeoman] (http://yeoman.io/) | | 
| Automation | Lots of tasks to execute. Compile. Test. Minify. Concat. Etc. | [grunt] (http://gruntjs.com/) | [gulp] (http://gulpjs.com/), [broccoli](https://www.npmjs.org/package/broccoli) |
| Dependency Management | Applications are getting complex. They rely on several other libraries and frameworks. | [bower] (http://bower.io/) | [component](http://componentjs.com/), [NPM](https://www.npmjs.org/)|
| Dynamic Loading | Big projects are split among several pieces of js for the sake of modularization. No all of them should be loaded at the same time. | [require] (http://requirejs.org/) | [curl.js] (https://github.com/cujojs/curl), [browserify] (http://browserify.org/), [webpack] (http://webpack.github.io/) |
| Testing | Testing is all around. Need to tests on different browsers, need to write the tests, need to run the tests, need to report test results. | [karma] (http://karma-runner.github.io/0.12/index.html) , [jasmine] (http://jasmine.github.io/), [phantom] (http://phantomjs.org/) | [mocha] (http://visionmedia.github.io/mocha/), [qunit] (http://qunitjs.com/), [protractor](https://github.com/angular/protractor), [sinon] (http://sinonjs.org/), [saucelabs] (https://saucelabs.com/), [duck angular] (https://github.com/asengupta/duck-angular)  | |
| Application | Applications on web are getting complex, need for frameworks that support app development. | [angular] (https://angularjs.org/), [backbone] (http://backbonejs.org/), [ember] (http://emberjs.com/), [knockout] (http://knockoutjs.com/)
| DOM Utilities | DOM selection and maniputation, some auxiliary functions, need for utilities that make work simple (and cross-browser) | [jquery] (http://jquery.com/), [zepto] (http://zeptojs.com/) | | 
| Language Utilities | Clean code, functional programming style, reactive programming features, helpers and utilities | [lodash] (http://lodash.com/), [underscore] (http://underscorejs.org/), [promise] (https://www.promisejs.org/), [fn.js] (http://eliperelman.com/fn.js/), [q.js](https://github.com/kriskowal/q) | | 
| CI | Continuous integration, continuous delivery, continuous deployment | [travis ci] (https://travis-ci.org/) | [jenkins] (http://jenkins-ci.org/), [concrete] (https://github.com/ryankee/concrete), [semaphore] (https://semaphoreapp.com/), [go] (http://www.thoughtworks.com/products/go-continuous-delivery), [snap] (https://snap-ci.com/) | |
| Other Languages | Have a syntactic sugar element, or even completelly different syntax (that in the end turn into javascript to run in the browser) | [coffeescript] (http://coffeescript.org/) | [clojurescript] (https://github.com/clojure/clojurescript), [typescript] (http://www.typescriptlang.org/)| |
| Other Javascript | concat, [minify](http://minifiedjs.com/), [uglify](http://marijnhaverbeke.nl/uglifyjs), [lint] (http://www.jslint.com/), [jshint] (http://www.jshint.com/), watch, [page](http://visionmedia.github.io/page.js/), [director] (https://github.com/flatiron/director), [crossroads] (http://millermedeiros.github.io/crossroads.js/), [moment.js] (http://momentjs.com/) | | |

### Style

| Need  | Tools | 
|-------|-------|
| Style - CSS Preprocessors | [sass] (http://sass-lang.com/), [less] (http://lesscss.org/) | 
| Style - Preprocessors Libs| [compass] (http://compass-style.org/), [bourbon](http://bourbon.io/) | 
| Style - CSS Helpers| [susy] (http://susy.oddbird.net/), [zenGrids] (http://zengrids.com/), [neat] (https://github.com/thoughtbot/neat), [normalize] (http://necolas.github.io/normalize.css/), [modernizr] (http://modernizr.com/), [flexbox] (http://css-tricks.com/snippets/css/a-guide-to-flexbox/) | 
| Style - CSS Frameworks| [boostrap] (http://getbootstrap.com/), [foundation] (http://foundation.zurb.com/), [skeleton] (http://www.getskeleton.com/) | 
| Style - Preprocessors | [sass] (http://sass-lang.com/), [less] (http://lesscss.org/), [compass] (http://compass-style.org/), [normalize] (http://necolas.github.io/normalize.css/), [modernizr] (http://modernizr.com/), [boostrap] (http://getbootstrap.com/), [flexbox] (http://css-tricks.com/snippets/css/a-guide-to-flexbox/), [foundation] (http://foundation.zurb.com/), [skeleton] (http://www.getskeleton.com/) | 
| Other General | Google's Pagespeed, Yahoo's YSlow, Chrome Developer Tools, Firebug, FireFinder, Font Icons| 
