#Load balancer

In this project, I continued to build up the configuration of the web server issued in project 0x0B. I was issued 2 additional servers, one to replicate the Nginx configuration of my original server, and another to set up an HAproxy loader balancer on to manage bothe web servers.

## Tasks :page_with_curl:

* **0. Double the number of webservers**
  [0-custom_http_response_header](./0-custom_http_response_header): Bash script that installs and configures Nginx on a server with a customm HTTP response header.
   * The name of the HTTP header is `X-served-By`.
   * The value of the HTTP header is the hostname of the server.
