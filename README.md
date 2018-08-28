# This is Design Distribution Version of [NETDEVV.COM](https://www.netdevv.com)

* CURRENT VERSION : 1.0.0
* DEV VERSION: 2.0.0

## DEMO::
* 

## Features::
* Smoot Workflow.
* Fully Customizable.
* GULP task manager
* Browser Sync Support.
* SASS compiler.
* JS and SASS minifier.
* WATCH mode inbuild.
* Bootstrap, Foundation, Jquery, Splitting JS and many more libraries built in.

### Installation Process::
* Install node js on your computer globally
*     npm install --global gulp-cli
*     git clone https://github.com/smitpatelx/netdevv-dist.git project01
*     cd project01
*     npm install
*     gulp build
*     gulp serve
* Open any browser and go to [localhost port 5050](http://localhost:5050)


### File Structure::
		(master)
		├───dist
		├───package.json
		├───package-lock.json
		├───gulpfile.js
		├───README.md
		├───LICENCE
		│   ├───fonts
		│   ├───images
		│   │   └───svg
		│   ├───scripts
		│   ├───styles
		│   ├───video
		│   └───index.html
		└───src
		    ├───scripts
		    │   └───vendors
		    │       ├───bootstrap
		    │       ├───foundation
		    │       ├───materialize
		    │       ├───jquery
		    │       └───splitting
		    ├───styles
		    │   ├───00-plugins
		    │   │   ├───bootstrap
		    │   │   ├───foundation
		    │   │   ├───materialize
		    │   │   └───splitting
		    │   ├───01-helpers
		    │   ├───02-base
		    │   ├───03-layout
		    │   ├───04-modules
		    │   ├───05-templates
		    │   └───06-global-components
		    └───views
		        └───index.html
