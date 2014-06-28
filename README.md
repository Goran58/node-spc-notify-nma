# Siemens SPC Notify NMA
Send events from Siemens SPC intrusion alarm to Android clients by Notify My Android service.

To be able to use this module you need to have:
- An account and an api key from [Notify My Android](http://notifymyandroid.com)
- SPC Web Gateway from [Lundix IT](http://www.lundix.se/smarta-losningar). SPC Web Gateway is providing a generic open REST and Websocket interface to Siemens SPC intrusion system.

## Installation
      
	git clone https://github.com/Goran58/node-spc-notify-nma
	cd node-spc-notify-nma
	npm install
	
## Configuration

- Modify the settings in config.json according to your environment and NMA api key
- Adapt the function manageSiaEvent() to the SIA-events you would like to be managed. Look in the SPC documentation for definitions of the SIA event types.

## Start
	./node-spc-notify-nma.js
