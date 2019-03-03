### Laliyeu Aleh
___

[Linked In](https://www.linkedin.com/in/ollie-laliev/)  
[Facebook](https://www.facebook.com/oleg.laliev)

>  I am a  developer who has a wide range of front end skills. The purpose being part of the epam team  I really enjoy go through this challenge RS School. I always look to add my own magical touch to any new code that I write

#### Skills  

+ HTML
+ CSS
+ Javascript
+ Node JS
___

#### Code Example
```
var http = require('http');
var url = require('url');

function start(route, handle) {
  function onRequest(request, response) {
    var pathname = url.parse(request.url).pathname;
    var postData = "";
    console.log("Request for " + pathname + " received.");

    request.setEncoding("utf8");
    request.addListener("data", function(postDataChunk) {
      postData += postDataChunk;
      console.log("Received POST data chunk'" + postDataChunk + "'.");
    });

    request.addListener("end", function() {
      route(handle, pathname, response, postData);
    });
  }

  http.createServer(onRequest).listen(8888);
  console.log("Server started");
}

exports.start = start;
 ```

### Job experience
Period
  ~ From 2016 to 2019

Job Title
 ~ front end developer.

Company:
 ~ I Software  

___

### Education
BNTU:
 ~ 2007-2012
___

### English level
Upper intermediate
