# Proyecto Contenedores

Este proyecto utiliza Docker y Docker Compose para configurar y ejecutar contenedores para PostgreSQL y Jupyter Notebook. A continuación se detallan los pasos necesarios para ejecutar y gestionar el proyecto en tu máquina local.

## Requisitos previos

- [Docker](https://www.docker.com/products/docker-desktop) instalado.
- [Docker Compose](https://docs.docker.com/compose/) instalado.

## Pasos para ejecutar el proyecto

### 1. Clonar el repositorio

Clona este repositorio en tu máquina local y navega al directorio del proyecto:

```bash
git clone https://github.com/KaisGitHub02/DockerExample/
cd tu_repositorio

docker-compose up --build -d
```
![Imagen de WhatsApp 2025-02-06 a las 14 15 05_91acb6c4](https://github.com/user-attachments/assets/aeb246be-2a9b-40ae-aa0e-e6d4c285e820)

```bash
docker ps
```
![Imagen de WhatsApp 2025-02-06 a las 14 15 06_f2033821](https://github.com/user-attachments/assets/ce126471-a68b-4641-9ee3-0c1e157999c0)



4. Acceder a los contenedores

Acceder al contenedor de PostgreSQL
Para conectarte al contenedor de PostgreSQL y acceder a la base de datos, ejecuta:

```bash
docker exec -it pgdb_container psql -U admin -d mi_basedatos
```
![Imagen de WhatsApp 2025-02-06 a las 14 15 06_d6c1b1aa](https://github.com/user-attachments/assets/6cf1ced9-5016-46ac-bc83-ca3d7a5cecdf)

```bash
docker exec -it jupyterugr_container bash
```
![Imagen de WhatsApp 2025-02-06 a las 14 15 06_202ebb00](https://github.com/user-attachments/assets/baec714a-7cbd-4f6d-86d4-0f19da926e75)
![Imagen de WhatsApp 2025-02-06 a las 14 15 06_46b34402](https://github.com/user-attachments/assets/16ef9dca-3d21-48e2-8507-b5ffb2b31b13)

```

