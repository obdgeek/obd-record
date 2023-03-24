## 0.50.3
The first public release so take it slow.  Just interested in the onboarding process and a short trip/charge and confirm they show up in OBD Play (don't forget to add your MME as the active vehicle and use your new data source).

While this build appears robust I need your feedback as only those with a Mach-E and an OBDLink MX+ can use this.  There is one known issue that you should be aware of (and perhaps more that I am unaware of):
- Doesn't correctly detect a disconnection when you walk away so it stays in the Connected view but appears to be connected to the MX+.  I recommend you swipe up and remove and relauch OBD Record if it fails to detect the vehicle being plugged in or the ignition turned On.  You maight also have to go to the Bluetooth settings and manually disconnect the OBDLink MX+ (t should reconnect after a few seconds).

### Change History
- cleaned up EVSE naming
- fixed onboarding problem with Fishinshed step showing up blank when a data source was added during onboarding
