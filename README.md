# Gestion des machines 
Cette application web a été développée en utilisant JavaServer Pages (JSP) et est déployée sur le serveur GlassFish.
Son principal objectif est d'optimiser la gestion des machines. À travers cette application, les utilisateurs ont
la possibilité d'effectuer diverses actions telles que la création de nouvelles machines, la consultation de la liste
des machines actuellement en service, la mise à jour des informations liées à ces machines, ainsi que leur suppression
# la page web :
![WhatsApp Image 2023-10-24 at 9 06 30 PM (3)](https://github.com/MeryemRACHYQ/TPjsp/assets/147452254/df525e3a-f95a-4967-b1c2-6ceda33d3651)

# Structure de projet
La structure du projet est divisée en plusieurs répertoires principaux :

src/main/java : Contient les fichiers sources Java et les packages.
src/main/webapp : Inclut les fichiers JSP et les ressources web.
src/main/resources : Contient les fichiers de configuration, y compris le fichier de configuration Hibernate (hibernate.cfg.xml).
# Execution :
Pour déployer et exécuter l'application :

Clonez ce référentiel sur votre ordinateur local.
Configurez votre base de données MySQL avec les paramètres appropriés, en vous assurant que la configuration correspond à celle définie dans le fichier hibernate.cfg.xml situé dans le répertoire src/main/resources.
Déployez le projet sur un serveur compatible avec Java Servlet. Vous pouvez le faire en créant un fichier WAR à partir du projet et en le déployant sur le serveur.
Démarrez votre serveur.
Accédez à l'application depuis votre navigateur web en utilisant l'URL correspondante (par exemple, http://localhost:8080/RoomMachineManagement). N'oubliez pas d'ajuster l'URL en fonction de votre configuration de serveur.
Vous pouvez maintenant utiliser l'interface web pour gérer les salles et les machines.
# Prérequis
Environnement de Développement Java : Assurez-vous d'avoir Java Development Kit (JDK) installé sur votre machine.
NetBeans IDE : Vous pouvez utiliser NetBeans IDE pour ouvrir et travailler sur ce projet.
Serveur d'Application : Cette application est conçue pour fonctionner sur un serveur compatible avec Java Servlet, tel que Apache Tomcat ou GlassFish.
Base de Données MySQL : Configurez une base de données MySQL et assurez-vous d'avoir les paramètres de connexion appropriés.
