------------------------------
Integrating Ionic and Loopback
------------------------------

The main idea behind this integration is to avoid the lengthy process of creating a REST API on Node JS.
The purpose of this app will be to add devices parameters(device name, device type, device owner) to a NoSQL database, MongoDB to specific. More such parameters can be added according to user requirements, with different customisations.

The Loopback Framework usage procedure can be found here: https://github.com/strongloop/loopback-example-database

Names used in this particular API, which are of significance and will be used for connecting loopback and ionic app are: deviceName, deviceType, deviceOwner. These names will be used when creating a loopback model, all of them are of type string, and have been set as required.

Change the port used by loopback according to your purpose, as the default port may/may not be occupied by other processes. You can do so by editing the config.json file in server folder under your loopback project folder. These changes should be enough to create a functioning REST API.

The ionic app can be found here: https://github.com/abdeokar23/ionic-root
