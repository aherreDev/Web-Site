Web-Site
========

This is a example of my web site.

Dependencies.
-------------

* npm@6.4.0
  * Node.js package manager.

* jquery@3.3.1
  * Javascript framework.

* browser-sync@2.26.3
  * Website auto-refresher. Every change will be shown in the website immediately.

* bootstrap@4.2.1
  * Popular website development Front-end framework.

* popper.js@1.14.7
  * Dependency of bootstrap. specifically for bootstrap's popping messages

* gulp@3.9.1
  * Build module. Sets up whole project.

Structure.
-------------

**_The bootstrap and jquery .js and .css are accessible from the /js and /css folders. I sat gulp up to do this, so always open the project by building first! Otherwise, bootstrap and jquery may not work! (specially if making changes to bootstrap)_**

#### `index.html`
* Contains the main page of the website!

#### css/index.css
* Contains css stylesheet.

#### js/index.js
* contains the javascript of the website.

**to se more, see the `docs/documentation.txt` file!**

Set up. (On progress)
----------------------

In order for the project to be set up, follow the following:
... need to test this on a different machine before writing this!

##### To start the project open cmd and do the following:

_rem means comment in batch lang! if using linux bash, the command shall be the same, just delete the rems!_

``` batch
rem 'Web-Site' shall be replaced with the path to the project root!
cd Web-Site

rem this installs the npm dependencies! I am still working on issues!
npm install
```

Once the dependencies are all installed, do next:

``` batch
rem ALWAYS RUN GULP INSIDE OF ROOT DIRECTORY!
gulp
```
Once gulp is running, you should not close the command prompt you are using, because the command will update and refresh the website with EVERY CHANGE THAT IS SAVED.

_In order to get out of gulp (like restart it or something), just do ctrl+c_


_README.md written by Jose Aguilar on 2/7/2019. Special thanks to the Francis tuttle 2017/2018 Web-Master team. Also, thank you to my roomate for being there keeping good vibes in the dorm as i wrote and coded this!_
