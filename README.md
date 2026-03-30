# Projet-Wakdo-Souliman-SAKKARWakdo – Borne de commande & Back-office
Présentation projet
Le projet a été initié dans le cadre de la certification RNCP 37805 – Développeur Web.
Il consiste en la conception d'une solution de digitalisation d'un restaurant de fast-food (Wakdo), inspiré du fonctionnement des bornes de commande modernes.
L’application permetra au client, de manière autonome, passer commande  Par le biais d'un support (une borne) tactile et  récupérer la commande au comptoir par la suite grâce à un numéro.
Le projet comprend également un back-office permettant aux équipes internes de gérer les produits, les menus et les commandes.
Architecture du projet
Le projet est structuré en 3 blocs principales :
Front borne ou Bloc 1 : interface client avec comme outils HTML, CSS, JavaScript
Back-office & API ou Bloc 2 : gestion des données avec comme outils Node.js, Express, MySQL
Application React ou Bloc 3 : recherche de restaurants sur carte avec comme outils React + Vite
Fonctionnalités principales
Borne de commande :
Parcours utilisateur simple et intuitif
Navigation par catégories (menus, burgers, boissons, desserts…)
Composition de menus (burger + accompagnement + boisson + sauce)
Personnalisation des produits
Gestion du panier en temps réel
Validation de la commande avec un numéro
Back-office :
Authentification des utilisateurs
Gestion des rôles (administration, préparation, accueil)
Gestion des produits et menus
Suivi des commandes
Mise à jour des statuts (en préparation, prêt, livré)
 API :
Récupération des produits et menus
Envoi des commandes (POST /api/orders)
Communication entre le front et le back
Application React :
Recherche de ville
Affichage sur carte (react-leaflet)
Sélection d’un restaurant
Interaction utilisateur dynamique
Base de données :
Une base de données MySQL a été mise en place pour gérer :
les utilisateurs
les produits
les menus
les commandes
Initialisation via :
schema.sql
seed.sql
Sécurité
Le projet inclut :
authentification des utilisateurs
gestion des rôles et permissions
validation des données côté serveur
protection des routes API
