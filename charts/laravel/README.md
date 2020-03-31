# Laravel Helm Chart
This is my personal implementation of a Helm Chart for deploying Laravel in Kubernetes.

The architecture costs of three deployments:
- App Component: a pod containing a reverse proxy made with NGINX proxying the PHP-FPM container containing the actual code.
- Queue Component
- Scheduler Component

