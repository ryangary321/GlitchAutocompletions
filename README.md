# Glitch Autocompletions
A buggy chrome extension for glitch.com autocompletions

## How to use
1. Download this project into a directory (not .zip)
2. Open chrome://extensions
3. Turn on developer mode (Upper right corner)
4. Click "Load Unpacked"
5. Select the folder that contains all the files

## Things it does do
- Adds autocompletions
- You CAN select other autocompletions!
- Use `tab` to autofill the top one
- New variables are included
- Other files are included

## Things it does NOT do
- It DOESN'T care about the HTML file includes
- It will NOT auto-update the extension when new changes come out on GitHub

## FAQ
### Why does it have so many errors?
This project is still in development, so there are many bugs.

### Why is the glitch.com editor crashing?
The code is somewhat funky with including files, so when you open a large file, it may crash the extension.

### What all does it work on?
This extension is made for chrome. It will probably only work on chrome.

### What is the Input autocompletion?
- Input is [Engine.js](https://engine-js.glitch.me/). I use it with most of my projects, so it is included.

### How did I do it?
First off, look at the code.

Secondly:
- I did a lot of using the dev console while on the glitch editor.
- `application.editor()` is your friend.
- Lots of hours staring at minified code.