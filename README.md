
# Text-Editor

## Description

A text editor that allows the user to type in scripts and save them to a browser database. This application allows the user to cache their data and is 
capable of running offline. I enjoy writing scripts but find myself going through dozens of files before I find the code snippets that I am looking for.
This application allows me to quickly find code snippets that I would like to preserve. I learned alot from this project, mainly with caching and webpack.
with caching I learned that if I get my service worker running before the app is complete that it'll cache everything instead and makes it difficult to edit.
With webpack I learn how everything should be linked in order for the webpack config to get everything into the dist directory.


## Installation

When the application runs you will be presented with a black screen that has a header with the name JATE. You will also see a banner saying install, when
when the install button is clicked, the program will install into your computer as a logo that you can place on your desktop. In the text editor you are 
able to type text inside and once you click away from the editor it will save the data in a ibd browser data base. When you hit refresh the text will be 
pulled from the database and present you with your saved code snippets.




<img width="1429" alt="Screen Shot 2022-08-04 at 9 05 24 AM" src="https://user-images.githubusercontent.com/88277371/182867723-ca3f0e9d-fc94-45c2-8e9a-a66d2e74ef3a.png">




## Credits

"code-mirror-themes": "^1.0.0" <br>
 "idb": "^6.1.2"<br>
 "@babel/core": "^7.15.0"<br>
 "@babel/plugin-transform-runtime": "^7.15.0"<br>
 "@babel/preset-env": "^7.15.0"<br>
 "@babel/runtime": "^7.15.3"<br>
  "babel-loader": "^8.2.2"<br>
  "css-loader": "^6.2.0"<br>
  "html-webpack-plugin": "^5.3.2"<br>
  "http-server": "^14.1.1"<br>
  "style-loader": "^3.2.1"<br>
  "webpack": "^5.51.1"<br>
  "webpack-cli": "^4.8.0"<br>
  "webpack-dev-server": "^4.0.0"<br>
  "webpack-pwa-manifest": "^4.0.0"<br>
  "workbox-webpack-plugin": "^6.2.4"<br>
  "express": "^4.17.1"<br>




























