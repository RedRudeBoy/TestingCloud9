howmanyc9
=========

How Many rewrite from scratch using cloud9 IDE

## Goals ##
1.	Complete testing suite
2.	Optimize separately for browsers, iphone and other mobile devices
3.	Serve pages optimized for the client using the user agent string
4.	Serve assets compressed in production but uncompressed during development

## Todo ##
1.	Import weart/node-backbone interesting parts
	1.	Twig templates (from jquerymobile folder)
	2.	Connect & Assetmanager (& handlers)			- /lib/asset.js
	3.	Persistent Database
		1.	CouchDB (below)
		2.	MongoDB (mongodb)
			1.	Mongoose
			2.	express-mongoose-resource
			3.	mongoose-auth - everyauth https://github.com/bnoguchi/mongoose-auth
	5.	Redis (connect-redis)
	6.	Testing Suite

## New Boilerplate? ##
[express-boilerplate](https://github.com/gaarf/express-boilerplate)

## New Framework? ##
http://stackoverflow.com/questions/3809539/choosing-a-web-application-framework-using-node-js  
http://ccnmtl.columbia.edu/compiled/reviewed/nodejs_frameworks_review.html  
http://brunch.io/#compare  

[chaplin](https://github.com/chaplinjs/chaplin)  
	[Boilerplate](https://github.com/chaplinjs/chaplin-boilerplate-plain/tree/master/js/vendor)  
	https://github.com/paulmillr/brunch-with-chaplin  
[spinejs](http://spinejs.com/docs/started)  

## Backbone plugins? ##
https://github.com/theironcook/Backbone.ModelBinder  
http://tbranyen.github.com/backbone.layoutmanager/


## CouchDB?? ##
[Local Instance:](http://127.0.0.1:5984/_utils)  
[Cloudant:](http://redrudeboy.cloudant.com/crud https://cloudant.com/for-developers/crud/)

#### Documentation: ####
[couchdb-guide:](https://github.com/oreilly/couchdb-guide)  
1.	http://guide.couchdb.org/editions/1/en/index.html
2.	http://guide.couchdb.org/draft/index.html
3.	http://guide.couchdb.org/editions/1/en/design.html
3.	http://guide.couchdb.org/draft/security.html Login & Users
4.	http://guide.couchdb.org/draft/transforming.html Views1
5.	http://guide.couchdb.org/editions/1/en/lists.html Views2

#### Utils & Projects: ####
[Backbone-couchdb:](http://github.com/janmonschke/backbone-couchdb)    
	http://janmonschke.com/projects/backbone-couchdb.html  
	https://github.com/janmonschke/backbone-couchdb/tree/master/chat_example  


[pouchdb:](https://github.com/iriscouch/pouchdb)  
[browsercouch:](https://github.com/mikeal/browsercouch)  
[flatiron:](http://flatironjs.org/)  
	[resourceful:](https://github.com/flatiron/resourceful)  
		https://github.com/flatiron/resourceful/wiki/Engine-Constructor  
	[restful:](https://github.com/flatiron/restful)  
		https://github.com/flatiron/restful/blob/master/test/fixtures/index.js



[couchdb-login-jquery:](https://github.com/couchapp/couchdb-login-jquery)  
	http://stackoverflow.com/questions/8342140/couchapp-user-registration


#### Examples: ####
http://backbone.iriscouch.com/backbone-couchapp/_design/backbone_example/index.html  
http://backbone.iriscouch.com/backbone-couchapp/_design/backbone_couchapp_comments/index.html  
http://emanuelpeg.blogspot.com.es/2012/06/pouchdb-un-base-de-datos-web-inspirada.html  


## Others: ##
[Markdown-Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
