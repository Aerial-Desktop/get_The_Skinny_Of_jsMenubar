## Welcome to get_The_Skinny_Of_jsMenubar
I made this repository under the assumption that the screensavers I added and later deleted bloated the project because git had to retain those files in the circumstance that someone checked out to a past commit sha.

Assumtion verified, here is the proof:

![proof](https://user-images.githubusercontent.com/11463275/43267443-f6642b16-90bb-11e8-9119-f83608fcfb03.png)
<hr/>

## js_menubar_Dynamic_Wallpaper
This project can be found at: https://github.com/js-talk-menubar-application/js_menubar_Dynamic_Wallpaper

![menubar_interface](https://user-images.githubusercontent.com/11463275/29501256-41e46114-85f5-11e7-9876-108172bef118.png)

#### Note To Self: early development. This repository is being developed with forks as a bridge node. <br>Click through to the specific organization and make changes on that branch.
### Electron, a node package that turns your javascript into desktop applications.
For our purposes, "MenuBar" Desktop Application.

Inital files that need manipulation

Here is a nice example for beginners: 
<br/>https://steemit.com/education/@ryanbaer/getting-started-with-electron-a-basic-menubar-app-part-1
<pre>
vi index.js
atom index.js
atom index.html
atom main.js
atom package.json

npm install -g opener
npm install
  if "Cannot find module 'electron' from '/Users/michaeldimmitt/js_menubar_attempt'"
    npm install --save-dev electron

    electron-packager .
    <br>
    <b>In one command, rebuild:</b>
    electron-packager . --overwrite; open dyna-dynamic-walpaper-darwin-x64/dyna-dynamic-walpaper.app/ 
</pre>

Copyright (c) 2017, Michael Dimmitt
<br>Access granted upon approved request. 

