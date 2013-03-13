# ep_example_plugin
##An Etherpad Lite Example Plugin

### By Rich Jones
### (but really by John McLear)

This project shows three important things one may wish to do while creating a plugin: 

* Editing the "chrome", rendered on the server side. This makes the buttons bigger for no reason.
* Using client-side hooks to change client-side code execution. This causes an alert box when the DOM is initialized, again, for no reason. 
* Manipulating the actual contents of a pad based on the line content. This adds add basic images support, pinched from ep_previewimages.

## Installation

Copy to highest level node_modules directory (same folder as ep_etherpad-lite)

## TODO

* Make everything work as advertised
* Tutorial
* Publishing guide?

## External Resources

* https://github.com/ether/etherpad-lite/wiki/Creating-a-plugin
