MEAN examples

INSTALL

- Requires
	sudo npm -g install bower
	
- Optional
	sudo npm -g install forever
	
- Get source from git
	
	git clone https://github.com/cecile/meanexample.git

- Install node modules

	npm install
	
- Install scripts

	bower install
	
LAUNCH

- via npm

	npm start

- via node
		
	node server.js
	
- via forever

    forever start server.js
    
- stop via forever

	forever stopall
	
FILES

- Server Side
	MongoDB configuration
	./config/db.js

	Node Server
	./server.js

	Express Application
	./app/routes.js
	./app/api.js
	./app/models/item.js

	Node Modules
	./package.json
	./node_modules

- Client Side

	Bower
	./bower.json
	./.bowerrc
	./public/libs
	
	Simple Page HTML
	./public/index.html
	
	AngularJS code
	./public/js/app.js
	./public/js/appRoutes.js
	./public/js/services/ListService.js
	./public/js/controllers/ListCtrl.js
	./public/js/controllers/MainCtrl.js
	
	AngularJS views
	./public/views/home.html
	./public/views/list.html

