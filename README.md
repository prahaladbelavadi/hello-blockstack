# hello-blockstack
# hello-blockstack
A blockstack hello-world application

> Requirements:
- Yeoman
- NPM
- Blockstack.js

-----------------------------------------------------------

> installation
- installing yo Generator
	```
	npm install -g yo generator-blockstack
	```
- Change root directory
	```
	mkdir hello-blockstack && cd hello-blockstack
	```
- generating blockstack app from yo generator
	```
	yo blockstack
	```
	
> Serving the app
- Download Npm dev dependencies
	```
	npm install -dev
	```
- Run browserify
	```
	npm run browserify
	```
- Start server
	```
	node server.js
	```
-----------------------------------------------------------
The server must render the index.html file at localhost:5000
-----------------------------------------------------------
[Original tutorial](https://blockstack.org/tutorials/hello-blockstack)
