{metric}
========

Not yet functional - [Progress through Tumblr screenshots](http://liamz.tumblr.com/tagged/metric)

![Screenshot as of 12/04/2015](http://40.media.tumblr.com/2da3fff026cd7b570e1c3f463390a932/tumblr_nmp1s2upRV1trskuwo1_1280.png)

**What is **{metric}**:
 - An app I'm using to keep track of different metrics for self-improvement in a relational manner (Health tracking is dependent on metrics relating to my Diabetes, exercise, eating habits, Happiness is related to my self-actualization, social belonging, etc.)
 - A modern take on what spreadsheets are supposed to do - take data and compute things. We use Web tech, JavaScript and libraries instead of MACROS and plugins. We use objects categorised and stored in databases rather than tables (2D arrays) to represent data.
 - An experiment, and my new life work.

Key points:
 - unlike Excel, we don't do tables
 - we do metrics and records
 - metrics are dynamically computed functions written in JavaScript, a record is just a JSON object
 - it's all built with web tech, it's real-time using Meteor and React
 - as a result of its client-server architecture, it can be hosted and accessed from multiple clients, and the metric computation thread is separated from the UI

## Install
 1. Install [Meteor](https://www.meteor.com/)
 2. Clone the project
 3. Run `meteor` and open [localhost:8000](http://localhost:8000)

Later when functional I'll bundle it up as an single-file app.

## License
Copyright Liam Edwards-Playne 2015. Licensed under [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-nc-sa/4.0/), which means you **can't use it for commercial purposes** without my written permission.

## Development practices
I admit this project does not adhere to several development practices -- the reason for this is that I am trying to develop it as quickly as possible and don't have time for dealing with the inadequacies of the Meteor packaging system, among other things.

## Thanks
This uses these projects:
 - Meteor
 - React.js
 - classNames
 - [javascript-editor](https://github.com/maxogden/javascript-editor), and subsequently Esprima and CodeMirror