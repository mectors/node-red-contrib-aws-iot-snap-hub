node-red-node-aws-iot-snap
==========================

A Node-Red node to read and write to AWS IoT via MQTT.

Install
-------

Run the following command in the root directory of your Node-RED install

    npm install node-red-node-aws-iot-snap


Usage
-----

Allows sending and receiving MQTT messages. Be sure to run before using it:
   sudo /snap/bin/nodered.awsinit <key> <secret> <region>

This will create an awscerts directory that can be used by the node to autoconfigure the right options.
