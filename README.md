This is and attempt to organize the recent explosion of Javascript based technologies and frameworks into a coherent toolkit to be used by a web application developer.

After some time discussing and studying some of the technologies we'd like to include in this toolkit, we realized that more important that the tool itself, **is the motivation that is behind that tool**. The need it tries to satisfy.

| Need | Motivation | Tools | Related Tools |
|------|------------|-------|---------------|
| Scaffold | Several tools. Several ways. Several Practices. Need to organize, and give some good foundation - best practices, good design.	| yeoman | | 
| Automation | Lots of tasks to execute. Compile. Test. Minify. Concat. Etc. | grunt | gulp |
| Dependency Management | Applications are getting complex. | They rely on several other libraries and frameworks. | bower | |
| Dynamic Loading | Big projects are split among several pieces of js for the sake of modularization. No all of them should be loaded at the same time.		| require | curl.js, browserify, webpack |
| Testing | Testing is all around. Need to tests on different browsers, need to write the tests, need to run the tests, need to report test results.		| karma, jasmine, phantom | mocha, qunit, protractor, sinon, saucelabs, duck angular | |
| Application | Applications on web are getting complex, need for frameworks that support app development. | angular, backbone, ember, knockout	
| Utilities	Several operations with dom, some data manipulation, need for utilities that make work simple (and cross-browser) | jquery	lodash, underscore, zepto, promise | | 
| CI | Continuous integration, continuous delivery, continuous deployment | travis ci | jenkins, concrete, semaphore, go, snap | |
| Other Languages | Have a syntactic sugar element, or even completelly different syntax (that in the end turn into javascript to run in the browser)	coffeescript | clojurescript | |
| Other Style | sass, less, compass, normalize, modernizr, boostrap, flexbox, foundation, skeleton | | | 
| Other Javascript | concat, minify, lint, watch | | |

