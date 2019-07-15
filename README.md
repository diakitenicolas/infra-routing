# infra-routing

Usage : Development env

## Requirement

* Create `traefik` network before
```
docker network create traefik
```


* Create User for Traefik Dashboard
```
htpasswd -nb admin changeme
``   