# ui-driver-nutanix
Rancher UI driver for Mutanix docker-machine driver


## Using

* Add a Machine Driver in Rancher (Admin tab -> Settings -> Machine Drivers)
  * Name: `Nutanix`.
  * Download URL: The URL for the driver binary (`http://download.nutanix.com/utils/docker-machine-driver-nutanix.linux`)
  * Custom UI URL: The URL you uploaded the `dist` folder to `http://github.com/tuxtof/ui-driver-nutanix/releases/download/0.0.1/component.js`)
* Wait for the driver to become "Active"
* Go to Infrastructure -> Hosts -> Add Host, your driver and custom UI should show up.
