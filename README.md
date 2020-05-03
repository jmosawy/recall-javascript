# Recall JavaScript

*The place where I look up regulary to refresh my mind about things I learn about JavaScript.*

> This document assumes you are familiar with JavaScript and just need to look up techniques or expections in JavaScript so as to refresh your memory. I write down whatever I find interesting while I'm learning about JavaScript, be it a simple thing or a very complex concept.

These notes are taken from the following learning materials:

- [JavaScript.info](https://javascript.info) by Ilya Kantor

## Table of Contents

1. [JavaScript Introduction](#javascript-introduction)

## JavaScript Introduction

- 1.1 **JavaScript Engines**: there are many different JS engines that implements ECMA standards to run JS codes. Each of them has got their own code name.

  - [**V8**](https://v8.dev/): used in Chrome and in Node.js, built by *Google*.
  - [**SpiderMonkey**](https://developer.mozilla.org/en-US/docs/Mozilla/Projects/SpiderMonkey): used in various Mozilla products, including Firefox, built by *Mozilla*.
  - **Trident & Chakra**: used in Internet Explorer, built by *Microsoft*
  - [**ChakraCore**](https://github.com/Microsoft/ChakraCore): used in Microsoft Edge, built by *Microsoft*
    - **Note**: Edge was later rebuilt as a Chromium-based browser and thus now uses V8.

- 1.2 **How JS engines work**: in a nutshell, the following steps are executed to acheive a running code:

  - Parse the script
  - Compile it to machine language
  - Run machine codes

- 1.3 **Languages over JS**: there are some languages that ultimately are transpiled to JavaScript.

  - [TypeScript](https://typescriptlang.org/) by *Microsoft*
  - [Flow](https://flow.org/) by *Facebook*
  - [Dart](https://dart.dev/) by *Google*

- 1.4 **ECMAScript**: is JavaScript's own specification.

  - [**ECMA-262**](https://www.ecma-international.org/publications/standards/Ecma-262.htm) contains the most in-depth, detailed and formalized information about JavaScript.
  - A new specification version is released every year.
  - Bleeding-edge features are called "stage-3" means they are almost standard and can be found at [https://github.com/tc39/proposals](https://github.com/tc39/proposals).
