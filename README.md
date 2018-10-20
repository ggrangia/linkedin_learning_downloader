# linkedin_learning_downloader
Simple script to download videos, transcripts and exercise files from the courses of your choice!


## How it works

You need a Linkedin Premium Account.
You need to have Node.js installed.
Download the project.
Open the terminal in the project folder and type:
```
npm install
```
to download necessary modules. (N.B. Puppeteer is a biiiig module).
Modifiy the .env file adding your Linkedin username(email) and password.
In order to properly set the LINKEDIN_COURSE, open the course you are interested in, e.g.:
```
https://www.linkedin.com/learning/node-js-deploying-applications
```
The last part of the url is what we are interested in.
```
node-js-deploying-applications
```
Now, execute the .js file to download the course:

```
node ./index.js

```
