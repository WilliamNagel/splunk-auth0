# Setup

1. Set the `SPLUNK_HOME` environment variable to the root directory of your Splunk instance.
* Copy this whole `splunk-auth0` folder to `$SPLUNK_HOME/etc/apps`.
* Open a terminal at `$SPLUNK_HOME/etc/apps/splunk-auth0/bin/app`.
* Run `npm install`.
    
    If this step fails
    1. [Clone the SDK from Github](https://github.com/splunk/splunk-sdk-javascript).
    * Copy the full `splunk-sdk-javascript` folder to `$SPLUNK_HOME/etc/apps/auth0/bin/app/node_modules`.
    * Rename this copied folder as `splunk-sdk`.
    * Run `npm install`.
* Restart Splunk

# Usage
[TODO]