# GeoPharma
Géolocalisation de Pharmacie
Nom du projet: GeoPharma
Auteur: GOKAR Nadine Manuela
Copyright: Avril 2019
État du projet: Pas complet
Rapide description: Conception une application web de géolocalisation de pharmacie
Détails: L'application devra permettre à son utilisateur de géolocaliser toutes les pharmacies sur une carte, par rapport à sa position géographique. 
Aussi, dans la journée, il pourra voir toutes les pharmacies et la nuit, il ne verra que les pharmacies de garde.
On lui permettra également d'acheter un produit dans la pharmacie choisie.
Mise en place, utilisation rapide: Installation de Netbeans 8.2(derniere version)
Installation de wampp server qui permettra d'avoir Mysql qui est notre serveur de bases de bases de données.
Serveur d'application: GlassFish server (intégré avec Netbeans)
|
|Une fois le serveur de bases de données MySql et le serveur d'application GlassFish démarrés,
| Creez le lien de connexion entre le serveur de bases de bases de données et L'application
| Creez le lien de connexion entre le serveur d'application et L'application en créant le pool et le JNDI dans la console Glassfish
|                                   entrez l'adresse----> http://127.0.0.1:4848/
|nom du pool:pnew
|nom du JNDI:jndinouveau
|
|-------------------------------Après déploiement-------------------------------------------------------------------
|
|Lien vers l'application: http://localhost:8080/GeoPharmacie/
|Login: admin
|Mot de passe: admin
Licence(s): Pas de licence
Méthode de rapport de bug: En cas de bug, lire dans la sortie de messagerie GlassFish pour répérer la source du problème.
Documentation courte: Code plus ou moins commenté.
