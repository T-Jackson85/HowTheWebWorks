1. What is HHTP? hyperText Transfer Protocol.(Standard web) how browers communicate with servers

2. What is a URL? Universal Resource Locator.

3. What is DNS? Domain Name sysytem. Takes a hostname such as facebook.com and translates it into a IP address.

4. What is a Query String? This provides "extra information" search terms, info from forms, etc.

5. What are two HTTP verbs and how are they different? GET- request without side effects. gets information.
POST- request with side effects. Typically arguments sent as body of the request.

6. What is HTTP request? request from a client to a server the follows HTTP protocol

7. What is a HTTPS response? Resonse to a client from the server using HTTP protocol

8. What is a HTTP header? Headers provide additional information about the request or response.
examples: Request- host, user-agent, cookies. Response- content-type, last-modified 

9. What is the process when you type in "http://somesite.com/some/page.html" in a browser?
"translates" the name into a IP address using DNS.
Makes request to that IP address.
The server sends a response.
Browser makes a DOM for that HTML, and also finds any other resources need.
The browser then makes seperate HHTP request for those resources and recieves a response from the server for each.
