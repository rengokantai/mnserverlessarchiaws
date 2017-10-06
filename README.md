# mnserverlessarchiaws

## 1. Going Serverless

## 3. Building a serverless applicaiton


### 3.1.4 Naming your lambda
For example, if you decide to name your file Transcoder.js rather than index.js, you'll have to modify the handler to be Transcode.handler in the AWS console.  


### 3.1.5 Testing locally
```
npm install run-local-lambda
```
package.json,add
``` 
"scripts":{
  "test":"run-local-lambda --file index.js --event tests/event.json"
}
```
