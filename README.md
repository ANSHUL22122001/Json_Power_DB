
# JSON_Power_DB
>>> Done by Anshul Sharma 

## A HTML Form Page made with JavaScipt and JsonPowerDB for entrying employee data.
## About JsonPowerDB:

- JsonPowerDB is a Database Server with Developer friendly REST API services. It's a High Performance, Light Weight, Ajax Enabled, Serverless, Simple to Use, Real-time Database.
- Easy and fast to develop database applications without using any server side programming / scripting or without installing any kind of database.
- Whether it's a Dynamic Website or a Mobile App or some Data Analytics Portal, the development is real fun and fast. Nothing better than trying it yourself. What all  you need is a basic understanding of HTML, CSS, Bootstrap, and Javascript.

## Benefits of using JsonPowerDB:

- Easy to use and maintain.
- Schema-free, Simple to use, Nimble and In-Memory database.
- It is built on top of one of the fastest and real-time data indexing engine - PowerIndeX.
- Proprietary algorithm for High Performance CRUD operations..
- Inbuilt support for Querying Multiple Databases.
- It has multiple security layers.
- It reduces reduces development cost.


## Use Cases:

- All Mobile applications that require backend database.
- Existing Database applications to improve their reporting / analytics performance.
- Best suited as backend Database for IoT.
- Live HTML templates / themes.
- Any software application that needs backend database.


## All request uses same coding syntax:
```sh
  // Code snippet for jQuery request and response to JsonPowerDB
  // Creating a request object
  var requestObject = {
      token: [connectionTokenString],
      dbName:[databaseNameString],
      rel: [relationNameString],
      cmd: [commandString],
      jsonStr: [jsonData]
  };

  // request object to json object
  var jsonRequest = JSON.stringify(requestObject);

  // calling api using post method
  $.post([apiURL], jsonRequest,  function (result) {
      var respObject = jQuery.parseJSON(result);
      var status = respObject['status'];
      if (status === 200) {
          // Code for successful response.
      } else {
          // Code for other status
      }
  });  
```

## Table of Content
1. [Screenshots](#screenshots)
2. [Status](#status)
3. [Instructions](#instructions)
   1. [Requirements](#requirements)
   2. [Execution](#execution)


## Screenshots:

![Dashboard](https://user-images.githubusercontent.com/62570770/122332521-27fc9800-cf54-11eb-9d9a-371cdcadfa8a.PNG)

![Front](https://user-images.githubusercontent.com/62570770/122332579-4367a300-cf54-11eb-8c0c-19c0a76899a1.PNG)

![Gui](https://user-images.githubusercontent.com/62570770/122332619-55494600-cf54-11eb-8eec-5d360c401016.png)


## Status:
![success](https://user-images.githubusercontent.com/62570770/122332655-67c37f80-cf54-11eb-9937-0ea58eab2b88.PNG)


## Instructions:
#### Requirements
  * Web Browser
  * Database Connection Token
#### Execution
* open `index.html`



### Scope of functionalities
- It is a very basic project for demonstration of JsonPowerDb with help of a web application.
- Can be further improved by addidng additional fields and can be made into a working DB manager.


### Sources:
- [Documentation Link](http://login2explore.com/jpdb/docs.html)
- [InbuiltFunctions_CDN](https://login2explore.com/jpdb/resources/js/0.0.3/jpdb-commons.js)
