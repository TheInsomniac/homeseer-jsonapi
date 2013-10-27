homeseer-jsonapi
================

Simple plugin for HomeSeer HS2 that provides a simple API that returns JSON data.

####Usage:  

#####http://username:password@homeseer.ip?[query string]

_All commands are via URL queries. The supported list is as follows_:  

__Get list of all devices located at Room / Interface__:  
  ?action=getroom&id=[interface/room name]  

__Get a list of all devices__:  
  ?action=getdevices  

__Get status of specific device__:  
  ?action=getdevice&id=[device ID]
  
__Turn on specific device__:
  ?action=deviceon&id=[device ID]  

__Turn off specific device__:  
  ?action=devicceoff&id=[device ID]  
  
__Set device value / dim level__:  
  ?action=setdevicevalue&id=[device ID]&value=[device value]  
  
__List all events__:  
  ?action=getevents  
  
__Run specific event__:  
  ?action=runevent&id=[event ID]  
