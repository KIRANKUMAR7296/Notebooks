# API
Application Programming Interface

[Public API](https://public-apis.xyz/)

Communicate One Application to Another, Allow to Transfer | Share Stored Data or Instructions.

Many API require an Authenticating ID Token to Access.

API Real Life Examples

1.Weather Snippets : Daily Weather (Weather + City Name)

2.Login : Log in Using Google, Facebook, Twitter and GitHub.

3.Online Payment using Paypal

4.Twitter Bots : Accounts that Automatically Tweet, Retweet, Send Direct Message based on Software Instructions.

5.Travel Booking : Flight and Destination Bookings.

Share Data with the World.

If Data is small, you can provide a Data Dump in the form of Downloadable JSON, CSV, XML or SQL Table.

GET : Pull Data from a Server by making Request to Remote Web Server.
      Retrieve Data from a Server at Specified Resources.
      Only Request Data and do not Modify any Resources.
      Valid GET Request returns a 200 Status Code.
      Invalid GET Request returns a 400 Status Code.

HTTP : Hypertext Transfer Protocol      | Mean of Communicating Data on the Web.
URL  : Uniform Resource Locator         | Address | Location of a Specific Resource (Web Page)
JSON : JavaScript Object Notation       | Text based Data Storage | Each Read for Humans and Machines.
REST : REpresentational State Transfer  | Architectural Design Pattern for API

POST : Push Data to a Server.
       Send Data to the API Server.
       Create and Update a Resource (POST Requests Modify Data).
       Data Sent to the Server is Stored in the Request Body of HTTP Request.
       Response Body is in the Form of JSON or XML or Query Parameter (?Parameter=)

Why to Use API?
- The Data is Changing Quickly 
- Regenerating Datasets and Downloading it Again and Again Every Minute (Will Use a Long Bandwidth and System will get Slow)
- We Need only Small Part of Data from the Data Set (No Sense to Download entire Dataset)
- Sometimes there is Repeated Computation Involved

Concept of API works Similar like Every Request and Response to the Web Servers.

Browser make Requests to a Web Server and Web Server Responds with the Content of the Web Page (Response Code + Response Data)
API also works Exactly the Same Way, Request is made to API Server for Data, and it Responds to your Requests.

Status Code are Returned with Every Request that is made to a Web Server.
Status Code :
200 : Everything went OK.
301 : Server is Redirecting you to a Different Endpoint.
400 : Bad Request | Invalid or Incorrect Data.
401 : Not Authenticated | Require Credentials to Access.
403 : No Permission to Access Data.
404 : Not Found on Server.
503 : Not Ready to Handle the Request.

Status Codes which begins with 2 : Successful and which begins with 4 or 5 : Error

# JSON 
- Language for API
- A Way to Encode Data Structure 
- json.dumps() : Converts Python Object to A String.
- json.loads() : Converts JSON String to A Python Object.
