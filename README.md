# docker_transmission_flexget

Repo con instrucciones para configurar un media server con Jellyfin con descargas por parte de Transmission y el stack sonarr + radarr + prowlarr + bazarr para la gestion de la media y los indexadores asi como homarr para crear un dashboard para fácil acceso a todos los servicios.

Tambien dejo una configuración alternativa para el uso de Flexget.

---
### Descripción

El proyecto cuenta con los archivos necesarios para levantar usando docker-compose un servicio [jellyfin](https://jellyfin.org/docs/general/installation/container/) para Media Server self-host.

### Dependencias

* [Docker](https://docs.docker.com/engine/install/ubuntu/)
* [Docker-Compose](https://docs.docker.com/compose/install/standalone/)

### Uso

```
git clone https://github.com/pgraffigna/docker_transmission_flexget.git
cd docker_transmission_flexget
docker-compose up -d
```

### Extras

* docker-compose con configuracion para usar flexget como gestor de peliculas/series a descargar.
* archivo de configuracion de flexget.
* archivo env de ejemplo.
* archivo de configuración para homarr con sitios ya configurados.