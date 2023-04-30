# Release Notes

## 0.50.20
- removed .chargerPowerLimit from AC charge processing
- added many data logging events
- rewrite of connect/disconnect code

### Known Problems
- reset sequence on connect hangs if the scan tool doesn't respond

## 0.50.15
- minimums to save a trip are a distance of 0.1 km and a duration of at least 15 seconds

## 0.50.14
- export activity indicator
- log level display
- export options include log level filtering

## 0.50.13
- added alert to export debugging logs action
- show loading entry for debug logs

## 0.50.12
- OBD Record will now discard any trip less than 0.1 km as being uninteresting.
- initial logging support added to Settings.About where you can see the most recent entries and copy the logs to the clipboard for sharing.
