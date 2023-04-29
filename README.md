# Docker multi-stage

1. Créer un nouveau projet git.
2. Initialiser une application React avec la commande "npx create-react-app docker-multi-stage".

3. Démarrer le serveur local avec la commande "npm start" et accéder à l'application à l'URL "localhost".
4. Créer un Dockerfile pour l'application (voir Dockerfile).

5. Construire une image Docker en utilisant la commande "docker build -t docker-multi-stage .".

6. Lancer un conteneur Docker à partir de l'image avec la commande "docker run -p 80:80 -d docker-multi-stage".

7. Accéder à l'application à l'URL "localhost" pour vérifier que l'application fonctionne correctement à partir du conteneur Docker.