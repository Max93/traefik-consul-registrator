# Boilerplate Traefik with Docker registrator and Consul

This solution use Traefik as load balancer. Services are discovered by Docker registrator and saved on consul catalog.

Ref.

- [Traefik](https://traefik.io)
- [Docker registrator](https://gliderlabs.github.io/registrator/latest/)
- [Consul](https://www.consul.io)


## Test

```bash
$ curl --header 'Host: random_service.docker.localhost' 'http://localhost:80/'
```

## Credits

- [@nicofuccella](https://github.com/nicofuccella)
- [@Max93](https://github.com/Max93)