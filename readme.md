Instructions:

1: Start with a local webserver with npm packet serve. 
    -> npx serve -p 5006
2: we write npm project in packet json. Run this in new terminal
    -> npm init -y
3: inititalize git repository
    git init
4: create a gitignore file
    add files that we want to ignore.
5: create index.html
6: create manifest file (manifest.webmanifest). 
7: create a folder for javascript and its files
8: create style.js
9: start with index.html. Write code. Add stylesheet, script and manifrst
10: write in the manifest, select colors
11: write in style, implement colors
12: make icons: width 512 * 512
13: after adding icons check in lighthouse. check boxes for progressive webapps and desktop
14: add a service worker in script folder. 
15: register service worker in script.js
    if service worker in navigator (promise) then console.log
16: add media devices in script.js
17: add video section in html
18: check mediastream webApi mdn for media methods
19: comment "async function allowCamera()" method
20: In case or error Uncaught (in promise) DOMException: could not start video source.....when clicked "show camera video" we use try catch on start button method
21: Add surge in terminal. npx surge
after surge is installed, press enter
22: copy the url and add https://thick-worm.surge.sh and run in browser
23: npm i --save-dev surge
24: add deploy in package json. Deploy scriot is required when one publish on the internet
25: write this in termninal to deploy "npm run deploy"
26: Add recording buttons in html and hidden download button
