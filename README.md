# nginx on Kubernetes

Deploy nginx in this cluster using the configuration in `nginx/default.conf`.

1. Serve the default nginx page on port 80 through a Service.
2. Configure liveness and readiness probes using the health endpoint defined in the config.
3. Show that the page and the health endpoint respond from inside the cluster.

Use the config file as it is. Looking things up is fine.
