# Connect-NodeMCU-to-WiFi-Router

This is example code to connect the NodeMCU ESP8266 Board to any WiFi Network

Below are some commands and there explanation in order to understand the code.

------------------------------------------------------------------------------
#include <ESP8266WiFi.h>      //add library into program

------------------------------------------------------------------------------
WiFi.begin("WiFiName", "WiFiPassword");     //Command to connect to a WiFi Network

------------------------------------------------------------------------------

WiFi.status();      //To check if it is connected to a Network or not.

WiFi.status() values can be: 

1) WL_CONNECTED	

2) WL_IDLE_STATUS

3) WL_CONNECT_FAILED		
-----------------------------------------------------------------------------
