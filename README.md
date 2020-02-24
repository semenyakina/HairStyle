# HairStyle
![](https://sun9-9.userapi.com/jYEYAMVxOGb1Gw7jqNoxT7OvHkC1vdxC_TRHmA/QqXYSWbhmww.jpg)
## Purpos 
HairStyle is a project designed on ReactJS to demonstrate diffrent hairstyles on images. It implemented 10 basic hairstyles and 10 colors. 
 
### How to use the web application? 
1. In order to run the web application you must open a file named "index.html". 
You will see a window in the browser.  
2. You can choose one of two languages that the application supports: Russian and English. The choice of language must be made at the beginning of the work with the application.
3. You can use already prepared image, as well as open an image from a local disk. 
4. Choose hairstyle and color from suggested by HairStyle.
5. After processing the image, you can save it to your device. 
6. The application runs on a mobile device and on most desktop browsers (ex. Google Chrome, Mozilla Firefox). 

## Limitations 

- Unable to upload a photo larger than 1080 x 1080 px 
- Currently only one hairstyle is supported in one filter 
- Only png format for image as input is supported 

## Prerequisites 
Download [NodeJS](https://nodejs.org/en/download/) 
Version not below than v.6.10.3 is required. 
After NodeJS installation please check that everything is installed correctly (for example, PATH ), using command: 
``` 
node —version 
``` 
Stdout should be v6.10.3 (or higher). 

### Install bower 
``` 
npm i -g bower 
``` 

### Install Gulp 
``` 
npm install -g gulp 
``` 

### Install all node packages 
``` 
npm install 
bower install 
``` 
After this command you will see node_module folder. 

## Command interface 

### Run 
``` 
gulp run start 
``` 
You need to open browser and type in the address bar 
``` 
localhost:3000 
``` 

### Verify coding standard with ESLint 
``` 
gulp run lint 
``` 
After running the command you should see no errors. 

### Running unit tests  
To run the tests run the command: 
``` 
gulp run test 
``` 

### Building autodocumentation 
``` 
gulp run docs 
``` 
After launch, the result will be in the folder docs/auto. 

### Building a project for putting it on the server 
``` 
gulp run build 
``` 
The result will be in the folder dist. 

