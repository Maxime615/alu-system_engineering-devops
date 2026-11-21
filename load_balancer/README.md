# Load balancer

* `0-custom_http_response_header`: installs Nginx and adds an `X-Served-By` header with the server's hostname.
* `1-install_load_balancer`: installs HAProxy and sends traffic to web-01 and web-02 using roundrobin.
