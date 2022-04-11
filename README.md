Introduction to Web Development



HTTP - Hypertext Transfer Protocol
HTTPS - Hypertext Transfer Protocol + Encryption

HTTP Requests list:
GET -> the method request a representation of the specific resource. Request using "GET" should only retrieve data.
HEAD -> the method asks for a respose identical to a "GET" request, but without response body.
POST -> the method submits an entity to the specified resource often causing a change in state or side effects on the server.
PUT -> the replaces all current representation of the target resource with request payload
DELETE -> the method deletes the specified resource
CONNECT -> the method establishes a tunnel to the server identified by the target resource
OPTIONS -> the method describes the communication optinos for the target resource
TRACE -> the method performs a message loop-back test along the path to target resource
PATCH -> the method applies partial modification to a resource

Error Codes: 
1xx informational respose -> the request was received, continuing proccess. 
2XX sucessfull -> the request was succesfully received, understood, and accept.
3XX redirection -> further action needs to be taken in order to complete the request.
4XX client error -> the request contains bad syntax or cannot be fulfilled 
5XX server error -> the server failed to fullfill an apparently valid request

