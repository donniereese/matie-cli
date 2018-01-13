# Matie CLI
**Matie**: _Make a Thing - an Interactive Explanation_

A CLI to be built as an explanation on how to build a CLI in Node.js Not the ultimate way, but one way to 
build a CLI application interface.

The easiest way to learn to build a CLI is to build one. That's what this intentds to provide, a step by 
step, gradual walkthrough on building the **Matie** CLI. By the end you should be able to construct your own 
CLI and apply the tools that you've learned in different projects or extend Matie to your own needs.

## :construction: :construction: This Is Under Construction :construction: :construction:
:warning: This document is actively under construction and is subject to change.

## The Environment
We'll be using Node.js, a JavaScript runtime that supports packages through NPM and has all sorts of 
components that will make it easy to extend and customize **Matie**

* Node.js
* readline module, fs
* editor
* command prompt

## Components to a CLI
* The user input prompt
* A way to parse commands
* Associate methods with commands
* A method to output to the user

## Further Components & Features
* command arguments and rules
* loading plugins
* user settings and customization

## Lesson 0 — Overview
The first Lesson, in programatic fassion, is Lesson 0. It's more of a review of some of the concepts of 
JavaScript that we will be using to build **Matie** and talking about what the _Command Line_ and _Command_
_Line Interface_ is. If you feel comfortable enough with JavaScript and feel as though you can understand 
these concepts well enough then you can skip this or start here; It's code won't carry over to Lesson 1.
[Go to Lesson 0 for a brief overview of the javascript we will be using](./lesson00-Overview/README.md "Lesson 0 - Javascript Overview")

## Lesson 1 — Hello, World
We're going to create a little _Hello, World_ program to interact with, in JavaScript, in our terminals. It's 
not going to be fancy and we aren't going to get into writing our own CLI just yet, but it will illustrate how 
to use the arguments passed to a program and return something to the terminal for the user.
[Go to Lesson 1 to start working on the Hello World terminal program and learn what it all means.](./lesson01-Hello_World/README.md "Lesson 1 - Hello, World in the Terminal")