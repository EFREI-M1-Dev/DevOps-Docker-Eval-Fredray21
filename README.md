# dabadie_frederic_docker

Ce référentiel contient les fichiers nécessaires pour exécuter l'application de Dabadie Frédéric à l'aide de Docker.

## Instructions d'exécution

1. **Décompression du fichier dabadie_frederic_docker.zip**

   Assurez-vous de dézipper le fichier `dabadie_frederic_docker.zip` avant de procéder.

2. **Accès au répertoire .docker**

   Naviguez vers le répertoire `.docker` à l'intérieur du répertoire principal après avoir décompressé le fichier.

   ```bash
   cd dabadie_frederic_docker/.docker
   ```

3. **Exécution avec Docker Compose**

   Pour lancer l'application, utilisez la commande docker-compose up dans le répertoire .docker.

   ```bash
   docker-compose up
   ```

   Cette commande va construire les images nécessaires et démarrer les conteneurs pour le front-end, le back-end et la base de données.

   Assurez-vous que Docker Compose est installé sur votre machine avant d'exécuter cette commande.


# 4. Accès aux services
- Front-end : http://localhost:80
- Back-end : http://localhost:3200
- Base de données : http://localhost:3306
### Assurez-vous que les ports nécessaires sont disponibles sur votre machine et ne sont pas utilisés par d'autres applications.

# Configuration des ports
- Front-end : Port 80
- Back-end : Port 3200
- Base de données : Port 3306

### Avec ces étapes, vous devriez pouvoir exécuter l'application de Dabadie Frédéric en utilisant Docker. 
### Si vous rencontrez des problèmes ou avez des questions, n'hésitez pas à contacter l'auteur du projet.
