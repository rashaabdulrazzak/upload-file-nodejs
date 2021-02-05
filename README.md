# upload-file-nodejs

There is a very good module for working with file uploads, called "Formidable".

The Formidable module can be downloaded and installed using NPM

```
npm install formidable

```

After downloaded the Formidable module, can be included the module in any application:

```
var formidable = require('formidable');

```

### Steps for uplaoding and saving files:

- Create a form to ulaod the file
- Parse the uploaded file using Formidable
- Save the file to the computer : when the file is successfully uploaded and parsed it is save to a temporary folder we use fs module to move the file to afolder on our comupter

### How to use :

- clone the repository
- run node demo-upload-save-file.js

### Useful links :

[Formidable](https://www.npmjs.com/package/formidable)  
[Nodejs](https://nodejs.org/en/)
