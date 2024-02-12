Lire attentivement les fichiers docker-compose.yml, docker-compose-simple.yml, docker-stack-simple.yml et docker-stack.yml. Ce sont tous des fichiers Docker Compose classiques avec différentes options liées à un déploiement via Swarm.
Quelles options semblent spécifiques à Docker Swarm ? Ces options permettent de configurer des fonctionnalités d’orchestration.

L'option deploy avec replicas et healthcheck.


Dessiner rapidement le schéma d’architecture associé au fichier docker-compose-simple.yml, puis celui associé à docker-stack.yml en indiquant bien à quel réseau quel service appartient.

Service docker-compose :
![schema_compose.png](schema_compose.png)

Service docker-stack: 
![schema_docker_stack.png](schema_docker_stack.png)

