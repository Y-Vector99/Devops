# Devops

Pour fabriquer l'image (dans le repertoire du projet) : docker build -t app .

Pour lancer un conteneur : docker run -d -p 8080:8080 app

CI Lors d'une pull request ou d'un push sur la branche main le code est build et des test sont effectués avec maven.

CD Si les tests passent un tag ainsi qu'une release sont crées à partir de la branche main.
