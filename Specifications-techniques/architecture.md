# 👷‍♀ Architecture du projet

Pour assurer la scalabilité, la maintenabilité et l'évolutivité de notre application, nous avons choisi d'adopter une architecture N-tier. Cette approche consiste à séparer l'application en plusieurs couches de responsabilité logiques, chacune étant responsable d'une tâche spécifique et pouvant être développée et mise à jour indépendamment des autres couches.

Notre application sera découpée en trois couches distinctes:

- Couche de base de données
La première couche sera la couche de base de données, qui stockera toutes les informations nécessaires au fonctionnement de l'application. 

- Couche API
La deuxième couche sera la couche API, qui servira d'interface entre la base de données et la couche client. 

- Couche client
Enfin, la troisième couche sera la couche client, qui sera elle-même divisée en deux parties : le front-end et la partie mobile.
Le front-end sera l'interface utilisateur de l'application, accessible depuis un navigateur web. Il permettra aux utilisateurs de réserver des terrains, de rechercher des partenaires de jeu et de consulter les informations relatives à leur compte. La partie mobile, quant à elle, sera une application native disponible sur les plateformes iOS et Android. Elle offrira les mêmes fonctionnalités que le front-end, mais avec une expérience utilisateur optimisée pour les appareils mobiles.

Grâce à cette architecture N-tier, nous espérons rendre notre application plus facile à maintenir et à faire évoluer, tout en séparant clairement les responsabilités de chaque couche. Cela nous permettra également de développer et de mettre à jour chaque couche de manière indépendante, ce qui accélérera le processus de développement.