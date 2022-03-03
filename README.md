# ToCode-4
The objective of this `ToCode4` section is to manipulate two (2) RESTFUL Web services : `RWS1` and `RWS2` : <br>

- `RWS1`: is a RESTFUL Web service you have to implement yourself.
- `RWS2`: is a RESTFUL Web service you have to choose from internet; you can for instance try [Covid19 APIS](https://explore.postman.com/4DTEzqFagDUe7F), test it, then, write one client against `RWS2` : `Client1`.

> Step 1

Implement a RESTFUL web service -- we will call it `RWS1`.<br>

- Write a PHP web service using CURL library. Your web service should implement at least one HTTP method. Test your web service with POSTMAN or SOAPUI and generate a WADL file for it.
- Write a client in PHP to your Web service.

> Step 2

Search for your `RWS2` : it should supports REST-based invocation.<br>

Testing :
- TEST the web service with SOAPUI (choose a method with XML response) and generate WADL file.
- TEST the web service with postman ((choose a method with JSON response) and capture HTTP traffic.
- Write `Client1` for a method with XML response : the one tested with SOAPUI. Use SimpleXML to parse XML.
- Write `Client2` for a method with JSON response : the one tested with POSTMAN.

> Step 3

Call `RWS1` and `RWS2` using a Web interface.

> Step 4 

Implement a RESTFUL web service in Java or .NET and write a client for this web service in PHP.
