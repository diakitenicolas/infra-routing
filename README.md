# infra-routing

Usage : Development env

## Requirement

* Create `traefik` network before
```
docker network create traefik
```


* Create User for Traefik Dashboard
```
htpasswd -nb routing changeme

```

Add an entry in your env vas like
 `TRAEFIK_DASHBOARD_CREDENTIALS=routing:$apr1$EgYHSkTP$0XK41V37qyhri0ABAFGoq/` where `routing:$apr1$EgYHSkTP$0XK41V37qyhri0ABAFGoq/` is the result of your htpasswd.


