Project Title

This is my Portfolio page created using HTML, SASS and JavaScript. I developed this portfolio so as to throw myself for any job opportunities. This portfolio puts light on my academic achievement, experience and skills. This portfolio also shows my recent works and contact details too.

Prerequisites

First of all, it is necessary to install package.json file. npm init

SASS is used in this portfolio. Hence, it is very important to install it before getting started. npm install node-sass

After installing node-sass, change the script in package.json as below: "Scripts": { "sass": "node-sass -w scss/ -o dist/css/ --recursive" }

Then, npm run sass

Getting Started

After installing all the prerequisities, in an editor, you can right-click on any '.html' file and open it with live server to view it in the browser. The page reloads if you make edits.

Deployment in Github Pages

First, install github pages npm i gh-pages

After this, add the followings in package.json file "homepage": "https://RabindraManandhar.github.io/Portfolio_Rabindra" Note: This is respective github page link of project.

"scripts": { "deploy":"gh-pages -d dist"

Note: -d dist refer to the directory of project

Then,

npm run deploy

Note: It gives 'Published'

Finally, open the above link in browser.

Acknowledgments

Inspiration from Traversy Media
