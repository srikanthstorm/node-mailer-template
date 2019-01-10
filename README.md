# Installation

## Install the package with NPM:

```bash
npm i node-mailer-template
```

## Usage

 
```bash
 var mailer = require('node-mailer-template')
mailer.sendEmailtoUsers("RecipientEmail","Title","Description","senderEmail",'senderPassword');
```

### Example

```bash
 
mailer.sendEmailtoUsers("toEmail@gmail.com","Title","Description","fromEmail%40gmail.com",'password');
```


 ```bash
 Note: @ in the from sender email should be mentioned as %40 or else your from email will fail to work, It can be normal for to recipient email
 ```
 if any requirements or updates mail us at srikanthnaidu512@gmail.com
