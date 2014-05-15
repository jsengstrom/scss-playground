SCSS Playground
===============

A very basic project template for developers who are new to CSS preprocessing to learn how it works. Recommended for use with [Codekit 2](https://incident57.com/codekit/).

Built as a learning aid alongside the presentation: [An Introduction to CSS Preprocessing](https://speakerdeck.com/jsengstrom/an-introduction-to-ccs-preprocessing).

## Installation

1. Download this repo to your desktop.
2. Drop the entire folder into Codekit 2.
3. Edit ```scss/_config.scss```, replacing the commented values.

## A Few Tips

Don't worry if you're having trouble getting the project to compile, just head to Codekit's error log and you can see whats causing it to fail. Scss is a lot stricter than regular CSS, and will fail even from a single missing semi-colon.

### Some do's

- Keep code DRY (Don't Repeat Yourself). Poorly structured Scss is even hard to read than poorly structured CSS.
- Use a file structure that makes sense to YOU (this is just a suggestion to get you started)
- Keep your file naming structure semantic

### Some Don'ts

- Don't nest selectors more than three levels deep.
- Don't keep module files than are longer that around 60-80 lines long!
- Don't add or edit any files to the build folder, that is strictly for compiled files (if you do, they will be overwritten next time you save any scss file).


* * *

Tweet me for support [@jsengstrom](https://twitter.com/jsengstrom).