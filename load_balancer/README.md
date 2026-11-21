# load_balancer

| File | What it does |
|------|--------------|
| 0-custom_http_response_header | Installs nginx and adds an X-Served-By header with the hostname |
| 1-install_load_balancer | Installs HAProxy and balances web-01 and web-02 with roundrobin |
