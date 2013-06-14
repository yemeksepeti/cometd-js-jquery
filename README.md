cometd-js-jquery
========================

An implementation of the Bayeux protocol in JavaScript for jQuery for distribution via Bower.

Purpose
-------
The purpose of this repository / project is to have an "always up-to-date" version of [CometD](http://cometd.org/), that can be acquired through [Bower](http://bower.io).

**Notice:** If a newer version has been released (yes, RC's or Alphas also count), feel free to submit a pull request (just include a message of which version you would like), and I'll make the version available.

Usage
-----
This paragraph implies that you have installed npm (Node Package Manager, which is part of NodeJS) as well as [Bower](http://bower.io). (the command . 

The simple way of using this dependency is to issue:
```bower install cometd-js-jquery```

or by adding it to your project's ```bower.json```- / ```component.json```-file:
```
{
  "name": "my-project-utilizing-bower",
  "version": "1.0.0",
  "dependencies": {
    ...
    "cometd-js-jquery": "~2.6.0",
    ...
  },
  "devDependencies": {
    "somedependency": "someversion",
    ...
  }
}
```
Information about available versions can be obtained by issueing the *info*-command, eg.:
```bower info cometd-js-jquery```

For futher information on using [Bower](http://bower.io)., read the documentation available on their [website](http://bower.io).

Changelog
---------
*   Jun 14th, 2013
    *   Forked repository ([marksherretta/cometd-javascript-jquery](https://github.com/marksherretta/cometd-javascript-jquery))
    *   Renamed repo
    *   Added BowerJS description file (bower.json)
    *   Added CometD version 2.6.0
