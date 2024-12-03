# jkbms
JK BMS.json:
    it is the NodeRed subflow to retrieve B2A8S20P JK BMS values
    This is a NodeRed subflow that I have succesfully used with the B2A8S20P JK BMS for my personal use.
    It retrieves the relevant BMS values and publishes them on MQTT.

JK Fet Toggles.json:
    it is the NodeRed subflow to switch On/Off the BMS charge & discharge FETs.

For both subflows, into the parent flow must be declared an environment variable called "serport"
where it is defined wich serial port to use to communicate with the BMS.

This flows are freely distributable, but I bear no responsibility whatsoever for their use.
The subflows work for me but could not work for others, no warranty is implied for their use.
