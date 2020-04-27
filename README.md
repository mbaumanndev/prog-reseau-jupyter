Programmation réseau
====================

Avant propos
------------

Ce dépôt contient du matériel pédagogique à destinations des étudiants de LP RGI option CISCO de l'IUT d'Amiens.

Ce dépôt contient du matériel pédagogique adapté pour les cours à distance et le travail individuel.

Pré-requis
----------

Pour utiliser le contenu de ce dépôt, vous aurez besoin de :

- La ligne de commande `git` ou d'un outil graphique vous permettant de faire une copie locale de ce dépôt (son contenu sera enrichi de séance en séance)
- De .NET Core en version 3.0 ou plus (3.1 est OK, 3.2 peut-être pas encore stable)
- De Jupyter Notebooks
- De [.NET Interactive](https://github.com/dotnet/interactive#how-to-install-net-interactive)

La documentation de .NET Interactive contient les liens et guide d'installation pour les autres composants nécessaires à l'éxécution de l'ensemble de l'environement.

Une fois tout ceci installé, vous pouvez lancer Jupyter Notebooks (en ligne de commande ou via Anaconda si vous l'avez installé avec ce dernier).

Cours
-----

Voici la liste de cours prévus à ce jour :

- [Cours sur la résilience](./poly-resilience.ipynb)
- [Cours sur AMQP et MQTT](./amqp-mqtt.ipynb)
- Cours sur SignalR et Sockets
- Cours sur OAuth et les services d'identité

Chaque notebook de cours contient le matériel nécessaire au déroulé de la séance.

Attention cependant, Visual Studio Code saura ouvrir les Notebooks mais pas (pour le moment) éxécuter le code C# qu'ils contiennent ! Vous devrez paser par Jupyter pour celà.
