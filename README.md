# chat-example for OpenShift v3

This is the source code forked from Socket.IO's [simple chat example](https://github.com/rauchg/chat-example) in the [Getting Started](http://socket.io/get-started/chat/) guide.
It is a little bit modifed for running OpenShift v3.

Usage
----

##### Run on OpenShift v3

```
$ oc new-app https://github.com/nak3/chat-example.git
```

That's all!


##### Run and test on your local

```
$ git clone https://github.com/nak3/chat-example.git

$ npm install --save express@4.10.2

$ npm install --save socket.io

$ npm start -d
```
