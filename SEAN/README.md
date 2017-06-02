# SEAN - Docker para el desarrollo de aplicaciones Sequelize - Express - Angular - Node
## INSTALACIÓN

docker-compose build

## CREACIÓN DE APLICACIÓN

docker-compose run sean yo
docker-compose run sean npm install

// Solo para Windows
docker-compose run sean patch -p0 < gulpfile.patch
docker-compose run sean patch -p0 < express.patch
// Fin de solo para Windows

## EJECUTAR APLICACIÓN

docker-compose up

