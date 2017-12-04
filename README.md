From this blog post about [using Postman to write to your local file system](http://blog.getpostman.com/2017/09/01/write-to-your-local-file-system-using-a-postman-collection/), this is an example of pulling data from this [open source REST API for SpaceX data](https://github.com/r-spacex/SpaceX-API), and writing to a local file.

### Install dependencies

    $ npm install

### Start your local server

    $ node script.js
   
### Run the Postman collection with corresponding environment

Click the Run in Postman button to import the collection and corresponding environment. Check out the [collection documentation](https://documenter.getpostman.com/view/1559645/spacex-launches/6nBvqd3) for step-by-step instructions to get started.

  [![Run in Postman](https://run.pstmn.io/button.svg)](https://app.getpostman.com/run-collection/d4c0cab0bb82ba10cfdf#?env%5BspacexAPI.template%5D=W3siZW5hYmxlZCI6dHJ1ZSwia2V5IjoibGF1bmNoRGF0YSIsInZhbHVlIjoiIiwidHlwZSI6InRleHQifV0=)
 
Run this Postman collection that submits a GET request for launch data and then submits a POST request to your local server.
  [![collection runner](https://s3.amazonaws.com/postman-static-getpostman-com/postman-docs/localServerCollectionRunner.png)](https://s3.amazonaws.com/postman-static-getpostman-com/postman-docs/localServerCollectionRunner.png)
  
### Results of the POST request to http://localhost:3000/launches can be found at ./spaceReport.json   
