# Nginx Health Simulator

* Docker repo: https://hub.docker.com/r/neowaylabs/nginx-health-simulator/

Just simple docker image running NginX responding to:
```
/         # 404 Not Found
/healthz  # 200 OK
/readyz   # 200 OK
```
