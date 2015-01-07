# Week 1

## Goal of this Class

Int -> Advanced JS

## Basic Project

[web](week1/web) - setup

    $ cd week1/web
    $ ../../server.sh

Use `Cnt-C` to quit the web server.

[NodeJS](week1/nodejs)  - setup

    $ node
    > 

## What is JavaScript

ECMAScript (ECMA-262 revision 5.1)

* [Self](https://en.wikipedia.org/wiki/Self_%28programming_language%29) - Prototype based inheritance
* [Scheme](https://en.wikipedia.org/wiki/Scheme_%28programming_language%29) - Lexicaly scoped funcational language
* Dynamically typed (like Self, Scheme)
* Forgiving syntax (like Perl)
* Amazing performance due to vendor competition (V8, SpiderMonkey, Squirrelfish, TraceMonkey, JägerMonkey, IonMonkey)
  * JS Perf battle - 2008 - now
  * JIT Compilers, Type Inference engines, ASM.js
* One of the most widely deployed high level programming languages
  * web browsers, browser addons, web servers, microcontrollers, desktop widgets, TVs, gaming consoles, PDF, Application Scripting


## History

* 1995 Created in 10 days for Netscape 2.0
* Name and Syntax a result of business deals with Sun
* 1996 Quickly standardized as ECMAScript 262
* Slightly useful, Flash plugin for heavy lifting/ads/games on the web
* 2004 - Ajax pattern - JS becomes more powerful
* 2008 / 2010 - Canvas and Amazing Perf - JS instead of Flash
* 2009 - CommonJS / NodeJS modules
* 2014 - Unreal Engine - webgl + JS

## Tools
### JSLint / JSHint

    npm install jshint

### Mocha (or some other testing framework)

### node-inspector
    npm install node-inspector
    export PATH=$PATH:~/src/int_adv_js/node_modules/.bin
    # Terminal A
    node-inspector
    # Terminal B
    node --debug --debug-brk week1/main.js
    # Open http://127.0.0.1:8080/debug?port=5858 in Chrome or Opera

### [JSDoc](http://usejsdoc.org/)

## Deep Understanding

This class won't cover everything related to JavaScript... it's too huge a topic.

The core secret to becoming an Advanced JS programmer, is to keep digging until you truley understand a technology or topic.

Being able to add jQuery to a project and use it to get a couple things done isn't enough!

Read jQuery's source code. Understand what problems it solves for you. Know how to solve them directly in JavaScript.
Evaluate multiple factors (library code size, added complexity, browser matrix support, amount of unused features, etc)

## References

### Web
#### Books
* JavaScript: The Good Parts (main reference for this class)
* Eloquent JavaScript
* Secrets of the JavaScript Ninja
* MDN
* HTML5 Rocks
* [ECMAScript 5.1](http://www.ecma-international.org/publications/files/ECMA-ST/Ecma-262.pdf)

### NodeJS
* http://nodejs.org/api/