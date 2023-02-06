# NodeMCU-HTTP-POST-Requiest-code

This is example code for HTTP POST requiest code.

Below are some commands and there explanation in order to understand the code.

------------------------------------------------------------------------------
#include <ESP8266WiFi.h>      //add library into program
#include <WiFi.h>				//add library for wifi network connection
#include <HTTPClient.h>		//add library for http client

------------------------------------------------------------------------------
WiFi.begin(ssid, password);     //Command to connect to a WiFi Network

------------------------------------------------------------------------------
http.begin("http://jsonplaceholder.typicode.com/comments?id=10")		// Specify the URL which server you have to connect

http.addHeader("Content-Type", "text/plain");             //Specify content-type header

httpResponseCode = http.POST("Hello, My name is Vikas");   //Send the actual POST request

response = http.getString();                       //Get the response to the request
		
-----------------------------------------------------------------------------