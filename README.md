# Docker

Docker es una **plataforma de virtualización ligera** que permite **crear, empaquetar y ejecutar aplicaciones** dentro de **contenedores**.  
Estos contenedores incluyen todo lo necesario para que la aplicación funcione: código, librerías, dependencias y configuraciones, asegurando que se ejecute igual en cualquier entorno.

## Características principales
- **Portabilidad**: Los contenedores se pueden ejecutar en cualquier sistema con Docker.
- **Aislamiento**: Cada contenedor es independiente, evitando conflictos entre aplicaciones.
- **Eficiencia**: Usa menos recursos que las máquinas virtuales.
- **Escalabilidad**: Ideal para entornos de microservicios y despliegues en la nube.

## Ejemplos de comandos básicos
```bash
# Verificar la versión instalada
docker --version

# Descargar una imagen desde Docker Hub
docker pull nginx

# Listar contenedores en ejecución
docker ps

# Ejecutar un contenedor
docker run -d -p 8080:80 nginx

# Detener un contenedor
docker stop <container_id>
