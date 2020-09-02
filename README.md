This project is deprecated.  Please see https://github.com/CiscoDevNet/meraki_cloud_simulator for a replacement tool.

# Meraki Location Scanning Simulator

The receiver is a simple Python Flask web server that receives the HTTP POST data from the Meraki Dashboard and plots that data in Google Maps.

## Requirements

* Python 3.6+
* Docker/docker-compose


In your terminal or command line run the following commands to launch your receiving server and the simulator server (the simulator server will launch no matter what option you've chosen above):

```
$ cd meraki_location_scanning_python
$ docker-compose up
```

Validate that the receiver is running and accessible by navigating in your browser to http://localhost:5001/go.


Validate that the simulator is running at http://localhost:5002/go.

In the URL field enter http://merakireceiver:5001 to have the simulator talk to the receiver.
