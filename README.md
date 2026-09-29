# nginx on Kubernetes

Start from `deploy.yaml`.

1. Run nginx with the configuration in `nginx/default.conf`.
2. Serve the default nginx page on port 80 through a Service.
3. Configure liveness and readiness probes.
4. Show that the page and the health endpoint respond from inside the cluster.

Use the config file as it is. Looking things up is fine.
