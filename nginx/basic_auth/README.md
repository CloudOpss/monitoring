# HTTP basic authentication files directory

This is the directory where must reside the files generated by [htpasswd](https://httpd.apache.org/docs/2.4/programs/htpasswd.html). NGINX will use these files to restric the access to the metrics exposed by cAdvisor, node-exporter or [any other Prometheus exporter](https://prometheus.io/docs/instrumenting/exporters).