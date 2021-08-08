# History of HTTP

* HTTP (HyperText Transfer Protocol) is the underlying protocol of the World Wide Web.
* Developed by Tim Berners-Lee and his team between 1989-1991, HTTP has gone through many changes in recent years,
but still keeping most of the simplicity and further shaping its flexibility. 
* HTTP has evolved from an early protocol to exchange files, to the modern maze of the Internet, now carrying images, videos in high resolution, etc..

# HTTP/0.9
* The first version of HTTP had no version number, it was later called as 0.9 to distinguish it from the later versions of HTTP.
* HTTP/0.9 is extremely simple, requests consist of a single line and start with the only possible method GET followed by the path to the resource.

# HTTP/1.0
* Version information is now sent within each request (HTTP/1.0 is appended to the GET line)
* A status code line is also sent at the beginning of the response, allowing the browser itself to understand the success or failure of the request and to adapt its behavior in consequence
* The notion of HTTP headers has been introduced, both for the requests and the responses, allowing metadata to be transmitted and making the protocol extremely flexible and extensible.
* With the help of the new HTTP headers, the ability to transmit other documents than plain HTML files has been added (thanks to the Content-Type header).

# HTTP/1.1
* The first standardized version of HTTP, HTTP/1.1 was published in early 1997, only a few months after HTTP/1.0.
* A connection can be reused, saving the time to reopen it numerous times to display the resources embedded into the single original document retrieved.
* Pipelining has been added, allowing to send a second request before the answer for the first one is fully transmitted, lowering the latency of the communication
* Content negotiation, including language, encoding, or type, has been introduced, and allows a client and a server to agree on the most adequate content to exchange

# HTTP/2
* It is a binary protocol rather than text. It can no longer be read and created manually. Despite this hurdle, improved optimization techniques can now be implemented.
* It is a multiplexed protocol. Parallel requests can be handled over the same connection, removing the order and blocking constraints of the HTTP/1.x protocol.
* It compresses headers. As these are often similar among a set of requests, this removes duplication and overhead of data transmitted.
* It allows a server to populate data in a client cache, in advance of it being required, through a mechanism called the server push.

# HTTP/3
* Still at work
