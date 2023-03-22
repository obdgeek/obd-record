# OBD Record

<a id='overview'></a>
## Table of Contents
- [Overview](#overview)
- [What's new](#whats-new)
- [Requirements](#requirements)
- [Installation](#installation)
- [Privacy Notice](#privacy)

## Overview
**OBD Record** is a SwiftUI application for logging Mustang Mach-E trips and charges which can be later viewed with the companion OBD Play application.  In order to make this happen an OBDLink MX+ OBDII adapter is required.

<a id='whats-new'></a>
## What's new
- Everything is new at this point, just explore and let us know of any problems or share your feedback.

<a id='requirements'></a>
## Requirements
- iPhone running iOS 16.2 or later
- OBDLink MX+ OBDII adapter
- InfluxDB data source (a sample data source is proviced for testing or you can create your own at [Influx Cloud](https://cloud2.influxdata.com/signup))

<a id='installation'></a>
## Installation
The beta test releases as being distributed by the Apple TestFlight application.  If you receive an invitation or have accrss to a shared download link you can access OBD Record from the TestFlight app.

<a id='privacy'></a>
## Privacy Notice
OBD Record collects location information that is used to show trips you have taken and where you have charged your vehicle.

OBD Record uses your Vehicle Identification Number (VIN) to uniquely identify your trips and charges in either a private data store or a shared public data store used for testing purposes.  If you create and use your own data store then no sharing of you location data is possible.

However, if you choose to use a public data store for evaluation and testing then your location and other vehicle data could be viewed by anyone that knows your VIN.  Should you wish to remove your trip/charge data from view you can swipe right on each trip/charge or use the Settings.Data Sources option to remove all your data.
