# Mirage
Mirage: A simple image viewer that can use arbitrary object storages as backed.  

## Equipments
- Docker
- Docker Compose

## Usage
Clone into your directory.  
``` sh
$ git clone https://github.com/lycoris0731/mirage
```

Run with `docker-compose`.  
``` sh
$ docker-compose up -d
```

## Use object storages other than AWS (S3 + CloudFront)
Please implement the interface `service/provider.go` in [github.com/lycoris0731/mirage-server](https://github.com/lycoris0731/mirage-server/blob/master/service/provider.go#L13).  

## Also
- [Server](https://github.com/lycoris0731/mirage-server)  
- [Web Frontend](https://github.com/lycoris0731/mirage-web)  

## License
Please see [LICENSE](./LICENSE).
