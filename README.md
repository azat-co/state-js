footer: © NodeProgram.com, Node.University and Azat Mardan 2017
theme: Simple, 1
build-lists: true

[.slidenumbers: false] 
[.hide-footer]

# State of Javascript: Overview of recent ECMAScript standard and libraries (end of 2017, early 2018)

![inline 100%](images/azat.jpeg)
Azat Mardan @azat_co

![inline right](images/nu.png)

---

# Meet Your Presenter: Azat Mardan

* Author of 14 books and over 20 online courses, taught over 500 engineers in-person and over 25,000 online (Udemy and Node University)
* Likes FinTech, blockchain and his coffee :coffee: with coconut oil
* Works as Capital One (in top 10 US banks) in Technology Fellows Program

---

![fit](images/azats-books-covers.png)

---

## In the beginning...

---

# DHTML

```js
document.getElementById('main').style.borderLeft = '2px dashed red';
document.getElementById('main').style.color = '#ff0000';
document.getElementById('nav').style.left = 300;
```

---

## Dreamweaver and other WYSIWYGs

![inline](images/phpdreamcs4.gif)


---


![inline](images/err1.gif)

---

![inline](images/error-objectexpected.gif)

---

![inline](images/error-displaying-previous-error-funny-error-messages.jpg)


---

# Now things are better...


---

[.autoscale:true]

## Or not?

* import vs. require
* Webpack vs. Gulp
* React vs. Angular
* Vue vs. pReact
* TypeScript vs. Flow
* npm vs. yarn
* Semicolons vs. no semicolons

---

# How it feels to learn JavaScript now


![inline](images/1-raWO3dhM4jMjf9VY-kZzNg.png)

^Source: <https://hackernoon.com/how-it-feels-to-learn-javascript-in-2016-d3a717dd577f>


---

# Min max

## I'm here to help! Let me give you the absolute minimum you need to know in 30 min or less

---

# Stack Overflow survey 2017

* Over 64,000 developers 
* 72% Web developers
* 63% Full stack web developers

![right width:60%](images/world-js.png)

^ [Stack Overflow Developer Survey Results 2017](https://insights.stackoverflow.com/survey/2017#technology) 

---

# ES2015 (a.k.a. ES6) - only important

* Fat arrow functions
* Promises
* Object literals
* Classes
* Modules (import)

---

# ES2016 and ES2017 (ES7 and ES8) - only important

* Async await functions
* Trailing commas in functions

---

# Learn ECMAScript more in depth

Blog posts:

* <https://webapplog.com/es6/>
* <https://node.university/blog/498412/es7-es8>

Courses

* <https://node.university/p/es6>
* <https://node.university/p/es7-es8>

---

# Presets? Compatibility?

<https://kangax.github.io/compat-table/es6/>

Include specific features ✅ by targets with `@babel/preset-env`:

```bash
npm install @babel/preset-env --save-exact
```

```json
{
  "presets": ["env"]
}
```

---

## JS Flavors

* CoffeScript v2
* TypeScript
* Elm
* ClojureScript

---

## State Management

* Redux
* Mobx
* Relay

---

## CSS

* SASS/SCSS
* LESS
* CSS Modules
* Aphrodite

^TL;DR Love inline approach for React. SASS/SCSS is the dominant framework.CSS Modules are probably worth looking into as well.

---

## Frameworks

* React (or preact or inferno)
* Angular 4
* Vue
* Ember
* Backbone

---

## API

* REST API
* GraphQL (Apollo or Relay)
* Firebase
* Falcor
* Meteor


---

## Testing

* Mocha
* Jasmine
* Enzyme
* Jest
* Cucumber
* Ava

---

# Webpack and Hot Module Reloading

^not live reloading

---

# Enterprise app + Strong Typing = ♥️

Benefits: 

* Static analysis, a.k.a. type checking (IDEs and build tools)
* Better, safer code reuse

---

# Which to use

## Flow has less intrusive syntax and easier to integrate while TypeScript is more mature and robust

Get started:

* For Angular, use [TypeScript](https://www.typescriptlang.org)
* For React, use [Flow](https://flow.org)

---

# Stop using Notepad ++

Seriously! 😏

---

## Get VS Code

<https://code.visualstudio.com>

* Smart autocomplete
* Debugger
* Git
* Terminal
* Quick, extendable and customizable

---

## Node

* `util.promisify`
* Chakra instead of Chrome V8
* http2
* v8 + npm v5
*  Large mainstream and enterprise adoption

---

[.autoscale:true]

## How Organizations use Node

* Back-end 73%
* Full stack 61%
* Front-end 51%
* DevOps 22%
* Desktop apps 20%
* Mobile 18%
* Security 8%

^ [2017 USER SURVEY EXECUTIVE SUMMARY](https://nodejs.org/static/documents/casestudies/Nodejs_2017_User_Survey_Exec_Summary.pdf)

---

![inline](images/langs.png)

---

## Future: ES2018

The following feature is currently at stage 4:

* Template Literal Revision (Tim Disney)

<https://github.com/tc39/proposals>

---

[.autoscale:true]

## Future: ES2018 Candidate features (stage 3)  

The following features are currently at stage 3:

* Function.prototype.toString revision (Michael Ficarra)
* **`global` (Jordan Harband)**
* Rest/Spread Properties (Sebastian Markbåge)
* Asynchronous Iteration (Domenic Denicola)
* **`import()` (Domenic Denicola)**
* RegExp Lookbehind Assertions (Daniel Ehrenberg)
* RegExp Unicode Property Escapes (Brian Terlson, Daniel Ehrenberg, Mathias Bynens)
* RegExp named capture groups (Daniel Ehrenberg, Brian Terlson)
* s (dotAll) flag for regular expressions (Mathias Bynens, Brian Terlson)
* Promise.prototype.finally() (Jordan Harband)
* BigInt – arbitrary precision integers (Daniel Ehrenberg)
* **Class fields (Daniel Ehrenberg, Jeff Morrison)**
* Optional catch binding (Michael Ficarra)

^Talk about class fields, import(), global, finally

---

![inline](images/world-on-node.png)

---

# Summary

* Learn ECMAScript
* Use Webpack and Hot Module Reloading
* Add Flow, Redux, React Router to React if needed
* Consider Vue instead of Angular
* Use Node 8, it's faster
* Switch to VS Code
* Adopt async functions or just use callbacks

---

# Wrap up

* JavaScript was a toy language 
* It spread to other platforms 
* It conquered web, i.e., all software
* It's used by startups and enterprises
* It's becoming feature-rich

---

## The future is bright

If can be written in JavaScript, it will be written in JavaScript. If you can pick only one language, with JS you can do so much more:

* Mixed Reality (VR and AR)
* Blockchain and dapps
* Mobile
* IoT 
* Cloud and databases

---

# THE END

## Links

* <https://github.com/azat-co/state-js>
* <http://azat.co>
* <https://webapplog.com> 
* <https://node.university>


