

## REST

Representational state transfer It is architactural style as well as an apprroch of comminication purpose thats is often used by web service development .

REST (REpresentational “State” Transfer) architecture style/pattern - the server does not store any state about the client session on the server side.This restriction is called Statelessness.

## RESTful web service/api

Application that implements REST.

## Why REST is called stateless?

Statelessness means that every HTTP request happens in complete isolation. When the client makes an HTTP request, it includes all information necessary for the server to fulfill that request. The server never relies on information from previous requests. If that information was important, the client would have sent it again in this request.

## REpresentational State Transfer
REST stands for REpresentational State Transfer. It means when a RESTful API is called, the server will transfer to the client a representation of the state of the requested resource. 

## Example

when a developer calls Instagram API to fetch a specific user (the resource), the API will return the state of that user, including their name, the number of posts that user posted on Instagram so far, how many followers they have, and more. The representation of the state can be in a JSON format, and probably for most APIs this is indeed the case. It can also be in XML or HTML format.


## Advantages of Statelessness
There are some very noticeable advantages for having REST APIs stateless.

1) Statelessness helps in scaling the APIs to millions of concurrent users by deploying it to multiple servers. Any server can handle any request because there is no session related dependency.

2) Being stateless makes REST APIs less complex – by removing all server-side state synchronization logic.

3) A stateless API is also easy to cache as well. A specific software can decide whether or not to cache the result of an HTTP request just by looking at that one request. There’s no nagging uncertainty that state from a previous request might affect the cacheability of this one. It improves the performance of applications.

4) The server never loses track of “where” each client is in the application because the client sends all necessary information with each request.
