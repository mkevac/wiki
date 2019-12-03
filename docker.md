# Docker

### Using container names as DNS names

[https://stackoverflow.com/questions/37242217/access-docker-container-from-host-using-containers-name/45071126\#45071126](https://stackoverflow.com/questions/37242217/access-docker-container-from-host-using-containers-name/45071126#45071126)

```text
$ docker run --hostname dns.mageddo --restart=unless-stopped -p 5380:5380 \
-v /var/run/docker.sock:/var/run/docker.sock \
-v /etc/resolv.conf:/etc/resolv.conf \
defreitas/dns-proxy-server
```

