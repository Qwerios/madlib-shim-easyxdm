# madlib-shim-easyxdm
[![Build Status](https://travis-ci.org/Qwerios/madlib-shim-easyxdm.svg?branch=master)](https://travis-ci.org/Qwerios/madlib-shim-easyxdm) [![NPM version](https://badge.fury.io/js/madlib-shim-easyxdm.png)](http://badge.fury.io/js/madlib-shim-easyxdm)

[![Npm Downloads](https://nodei.co/npm/madlib-shim-easyxdm.png?downloads=true&stars=true)](https://nodei.co/npm/madlib-shim-easyxdm.png?downloads=true&stars=true)

Packaged version of Øyvind Sean Kinsey easyXDM because it isn't available on npmjs. All credit goes to the original author.


## acknowledgments
[EasyXDM](https://github.com/oyvindkinsey/easyXDM) is owned, created and maintained by Øyvind Sean Kinsey. It's released under the MIT license which is included in this package. I am graciously using his library to bridge the Cross Domain barrier for my [madlib-xhr-xdm](https://github.com/Qwerios/madlib-xhr-xdm) module.

The Marviq Application Development library (aka madlib) was developed by me when I was working at Marviq. They were cool enough to let me publish it using my personal github account instead of the company account. We decided to open source it for our mutual benefit and to ensure future updates should I decide to leave the company.


## philosophy
JavaScript is the language of the web. Wouldn't it be nice if we could stop having to rewrite (most) of our code for all those web connected platforms running on JavaScript? That is what madLib hopes to achieve. The focus of madLib is to have the same old boring stuff ready made for multiple platforms. Write your core application logic once using modules and never worry about the basics stuff again. Basics including XHR, XML, JSON, host mappings, settings, storage, etcetera. The idea is to use the tried and proven frameworks where available and use madlib based modules as the missing link.

Currently madLib is focused on supporting the following platforms:

* Web browsers (IE6+, Chrome, Firefox, Opera)
* Appcelerator/Titanium
* PhoneGap
* NodeJS


## installation
```bash
$ npm install madlib-shim-easyxdm --save
```