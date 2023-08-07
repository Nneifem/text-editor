# text-editor

## Description

This project was built to create a text editor, using progressive web applications (pwa) that will able to run the same online and offline. Doing so this solves the issue of if the user is somewhere where there is no access to wifi or bad connection, the website will still be able work properly. When working on this, I got to learn how pwa works and that you can have different package.json that each have something different installed rather than having just one with everyone you need for the code in one place. 

## Installation

To get this running properly you will need to install the following in the general code: 
- npm init -y
- npm i
- npm i express
- npm i if-env

Then in the terminal type 'cd server' to enter the server folder and install the same as in the instructions above but stop after installing express. Now enter the client folder, type the usual npm init -y and with the rest of the ones you type it will follow as npm install "the package you type" --save-dev:
- @babel/core
- @babel/plugin-proposal-object-rest-spread
- @babel/plugin-transform-runtime
- @babel/preset-env
- @babel/runtime
- babel-loader
- css-loader
- html-webpack-plugin
- http-server
- style-loader
- webpack
- webpack-cli
- webpack-dev-server
- webpack-pwa-manifest
- workbox-webpack-plugin

## Usage

When everything has been properly installed, in the integrated terminal type in 'npm run start:dev' to start the website and you'll be able to type whatever you want inside there, be able to refresh it and still have everything appear and still be able to use it offline as well.
![alt text](/client/image/Screenshot%202023-08-07%20at%206.49.54%20PM.png)

## License

MIT License

Copyright (c) 2023 Nneif

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.


## Links 
Repository Link: https://github.com/Nneifem/text-editor

Website Link: https://nneif-text-editor-2d4fcad3ac4f.herokuapp.com/