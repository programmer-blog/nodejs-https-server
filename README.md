# nodejs-https-server


## Source code for article: How to create nodejs https server on localhost using openssl

Blog Link: http://programmerblog.net/

Article link: http://programmerblog.net/nodejs-https-server/

Following tasks are performed in this tutorial:

1. Download and install OpenSSL for nodejs https server

2. Generate SSL certificates for nodejs https server

3. OpenSSL commands to generate SSL certificates
 
  ``` 
      openssl genrsa -out privatekey.pem 1024
      
      openssl req -new -key privatekey.pem -out certrequest.csr -config C:\OpenSSL-Win64\bin\openssl.cfg
      
      openssl x509 -req -in certrequest.csr -signkey privatekey.pem -out certificate.pem 
      
  ```
  4. Generate an NodeJS, ExpressJS application
  
  5. Add https protocol to application.
  
  Detailed Tutorial: http://programmerblog.net/nodejs-https-server/
  
  
