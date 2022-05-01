# Swagger Viewer
 This project provides an quick and clean online viewer for api swagger documentations.

 


# Why
 * Its not a good practice to host your API docs in the same instance you host the API itself;
 * Sometime you do not want to deploy an API or make it public but need to share the docs;
 * You have a study project and want to share its Swagger docs.

 # How 
 Just host your swagger.json file anywhere, go to 
 https://kortkamp.github.io/swagger-viewer/ 
and put your swagger file url in the input form,


 or just use the GET param 'host' and go directly to you rendered file,

 ```
 https://kortkamp.github.io/swagger-viewer/?host=my-swagger-file-url
 ```
Example:

 https://kortkamp.github.io/swagger-viewer/?host=https://raw.githubusercontent.com/kortkamp/template-node-api/main/src/docs/swagger.json


## :book: MIT License


<br>

If this project was useful to you, don't forget to give it a star.

Made with love by [Kortkamp](https://github.com/kortkamp)