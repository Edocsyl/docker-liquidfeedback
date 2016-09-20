# Docker LiquidFeedback 
LiquidFeedback is an open-source software, powering internet platforms for proposition development and decision making

Website: http://liquidfeedback.org/

##Docker

Docker image to run an instance of the liquidfeedback software

How to build:

	$ make

How to run:

	$ make run

Open the browser:

	http://$(docker-machine ip default):8080

	
	
### Changelog
* Added SQL Query to create an admin user withou a password. ! set a password after setup!
* Updated Source
	* LiquidFeedback Core to v3.2.2
	* WebMCP v2.1.0
	* LiquidFeedback frontend to v3.2.1