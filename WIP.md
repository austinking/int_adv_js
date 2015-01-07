Week 1
Why JavaScript (Chapter 1)
Tools - NodeJS, Debugger and debugger statement, JSDoc (http://usejsdoc.org/)
Resources - w3schools should die, MDN, http://www.html5rocks.com/en/

Week 2
Language Nazi - types (Chapter 2, 3, 6)
- Syntax
- Objects (use for (var x in bar) { ...
- Arrays (use for (var i=0; ...
- Associative Arrays (aka Map or HashMap) should be implemented with Objects not Arrays
- Array and Object literals make JavaScript easy to read and a pleasure to write
- use primitive types and literals instead of Java style Object wrappers
- reserved words will blow up (in IE 8)
- use Array.prototype.slice.call(arguments); to copy arrays or convert objects to arrays
- Strings - use single quotes, use Array#join for building up strings
- foo || {}, foo= bar ? "baz" : "buz";

Week 3
Functions (Chapter 4)
- Scope
- bind, call, apply
- nested functions are cool
- implicit variables in scope (arguments, ?)
bind FTW
el.click(function(e) {  
    this.clickCount++;
}.bind(this));

DO NOT
- declare a function in a conditional block



Week 4
Functional Programming (Chapter 5 page 52)

Week 5
Inheritance (Chapter 5, Chapter 8)

Week ?
AMD and JS to Avoid
RequireJS
eval
with
multiline string support

Week 6
The Future of JS
ES6 http://kangax.github.io/compat-table/es6/
Modules
Proxies
Sweet.js
ES7

-----------------------------------------------------------------------
Cutting room floor?
Regular Expressions (Chapter 7)

Error handling
- new Error("foo").stack
- - try / catch
- NodeJS calling patterns
- try / catch / finally doesn't allow for selective catching of errors
- name anonymous functions to improve stack traces


Memory Leaks
Closures can capture references to objects, which will cause them to never be garbage collected.
http://google-styleguide.googlecode.com/svn/trunk/javascriptguide.xml?showone=Closures#Closures

Monkey Patching
APE SHALL NOT KILL APE - APE SHALL NOT MODIFY PROTOTYPES OF BUILT IN OBJECTS
-----------------------------------------------------------------------

Structure Resources
* http://eloquentjavascript.net/Eloquent_JavaScript.pdf
* JavaScript: The Good Parts
* https://developer.mozilla.org/en-US/learn/javascript

Tools
* JSHint / JSLint
* Chrome debugger
* Mocha
* Esprima, Sweet.js

APIS:
* XHR
* SSE
* IndexedDB
* Web Workers
* Service Workers

var foo = function foo (a, b) ... (debugging, scope)



semi-colons are optional... but use them, they are part of the language

multiline strings are a thing...

Homework - watch WUT video

checking for nulls, truthiness
!! foo

var value = foo || "default";
var value = req.headers.referer || "direct_traffic";

User script - scripts to change web pages - automate stuff
Web Components
jshint
"use strict"; - catches undeclared variables instead of creating an implicit global, catches Constructors initiated without new
ES 6
Sweet.js

Offline First http://jakearchibald.com/2014/offline-cookbook/

http://jstherightway.org/ - Concepts, ideas

Games: http://codecombat.com/play/spectate/gold-rush

---------------------------------

High Order Functions as a means of reorganizing programs

----------------------------

Going to the highest level of abstraction isn't always appropriate!
Sometimes concrete is better!
EmberJS or Ruby on Rails are too abstract and require a massive learning curve.
Once one masters these abstractions, one welds great power... but at great cost.

Style Guides:
Google http://google-styleguide.googlecode.com/svn/trunk/javascriptguide.xml?showone=Closures#Closures