# hello-blockstack
A blockstack hello-world application

> Requirements:
- `Yeoman`
- `NPM`
- `Blockstack.js`

-----------------------------------------------------------

> installation
- installing yo Generator
	```bash
	npm install -g yo generator-blockstack
	```
- Change root directory
	```bash
	mkdir hello-blockstack && cd hello-blockstack
	```
- generating blockstack app from yo generator
	```bash
	yo blockstack
	```
	
> Serving the app
- Download Npm dev dependencies
	```bash
	npm install -dev
	```bash
- Run browserify
	```bash
	npm run browserify
	```
- Start server
	```bash
	node server.js
	```
-----------------------------------------------------------
The server must render the index.html file at localhost:5000
-----------------------------------------------------------
[Original tutorial](https://blockstack.org/tutorials/hello-blockstack)
