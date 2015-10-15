#Behat demo

My little demo application to play around with Behat.
I am not involved or connected to anybody at Behat. I am just a user :)

## Usage

1. Change into the directory of this app.

2. Get [Composer](http://getcomposer.org) and run `composer install`


3. Start Selenium server with the correct version number:

	```
    java -jar selenium/selenium-server-standalone-2.48.2.jar
	```
	or have it running in the background

	```	
	nohup bash -c "java -jar selenium/selenium-server-standalone-2.48.2.jar &"
	```
	

4. Open a new console window and run this command:

	```
    bin/behat
	```
	
## Links
* <http://behat.org>
* [Selenium Standalone Server Download](http://code.google.com/p/selenium/downloads/list)