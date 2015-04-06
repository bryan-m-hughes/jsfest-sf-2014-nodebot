JSFest NodeBot
==============

This code was first used at a hack day event for [JSFest](http://jsfest.com/) 2014 in San Francisco, and then again for a kids workshop on robotics.

## Wiring

Here is the wiring diagram for the SumoBot. Make sure that you get everything wired up **exactly** as shown below. If you get any of the red and black wires crossed, you may damage the motors! Also make sure that none of the metal on the red and black wires ever come into contact, this will definitely damage the motors!

![Wiring Diagram](https://theoreticalideations.com/static/jsfest-sf-2014-wiring.png)

## Installation

- Install [Node.js](http://nodejs.org/)
- If you are on Windows, install [Git](http://www.git-scm.com/). Mac OS X and Linux come with Git preinstalled
- Open a terminal, and navigate to the folder you want to install the project at
- Run ```git clone ```
- ```cd``` into the ```jsfest-sf-2014-nodebot``` directory
- Run ```npm install```

## Running

- Plug the USB cable into your computer and the robot
- In the same terminal and directory where we ran ```npm install```, run ```node bot.js```
- Open your browser and navigate to ```http://localhost:8000/```
- Press the arrow keys to move the robot!

License
=======

The MIT License (MIT)

Copyright (c) 2014 Bryan Hughes bryan@theoreticalideations.com

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.