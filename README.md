# Projet-Dev-2
Developpment d'une application en C# Dans le cadre d'un projet de groupe

> **Projet DEV.2**

**[Objectif]{.underline}**

> • Développement d'une application en C#\
> • Connexion, création, manipulation des données dans une base de
> données • Réalisation des tests unitaire

**[Description du projet]{.underline}**

Le but de l\'application est de permettre aux utilisateurs de suivre
leurs dépenses quotidiennes en enregistrant les montants et les
catégories de dépenses dans une base de données.

L\'application doit permettre alors de saisir ses dépenses quotidiennes,
de les afficher, ajouter, modifier, supprimer, rechercher par catégorie,
et la génération d'un rapport/ graphique de dépenses.

> \- L\'utilisateur doit pouvoir se connecter avec un nom d\'utilisateur
> et un mot de passe sur un formulaire de connexion.
>
> \- Une fois connecté, l\'utilisateur doit être redirigé vers une
> fenêtre qui affiche la liste des dépenses quotidiennes.
>
> \- L\'utilisateur doit pouvoir ajouter, modifier et supprimer des
> dépenses.
>
> \- Les dépenses doivent être stockées dans une base de données.
>
> **Ajout de dépenses** :
>
> L\'utilisateur doit pouvoir ajouter une nouvelle dépense avec les
> champs suivants : date, catégorie, montant et commentaire.
>
> La catégorie doit être choisie parmi une liste prédéfinie de
> catégories (par exemple : alimentation, transport, loisirs, etc.).
>
> **Modification de dépenses :**
>
> L\'utilisateur doit pouvoir modifier une dépense existante en cliquant
> sur un bouton de modification.
>
> Tous les champs de la dépense doivent être modifiables.
>
> **Suppression de dépenses** :\
> L\'utilisateur doit pouvoir supprimer une dépense existante en
> cliquant sur un bouton de suppression.
>
> **Recherche de dépenses** :\
> L\'utilisateur doit pouvoir rechercher les dépenses par catégorie ou
> par date.
>
> **Graphiques** :\
> L\'utilisateur doit pouvoir visualiser les dépenses sous forme de
> graphiques (par exemple : un graphique circulaire montrant la
> répartition des dépenses par catégorie).
>
> **Sauvegarde et récupération des données** :\
> L\'application doit être capable de sauvegarder les données dans une
> base de données et de les récupérer lors du prochain lancement de
> l\'application.

**1.Analyse des besoins**\
Donner le diagramme de cas d'utilisation, un exemple d'un scénario
textuel et un diagramme de séquence\
***Conception de l'interface graphique***\
Donner un exemple d'une conception d'une interface graphique déduite à
partir d'un scénario **2.Base de données :**\
La base de données stocke les informations relatives aux dépenses, y
compris le montant, la catégorie, la date, une description et un
identifiant unique. Il y aurait une table pour chaque catégorie de
dépenses, avec une relation de clé étrangère pour associer chaque
dépense à sa catégorie.

**3.Tests unitaires**\
Des tests unitaires seraient écrits pour chaque fonctionnalité de
l\'application afin de s\'assurer que le code est fonctionnel et qu\'il
répond aux besoins des utilisateurs.

Par exemple, un test unitaire pour l\'ajout d\'une dépense vérifierait
que la dépense est correctement enregistrée dans la base de données et
que les informations de la dépense sont correctes.

Les tests unitaires seraient écrits à l\'aide d\'un Framework de tests
unitaires.

**Contraintes techniques :**\
- L\'application doit être développée en C# avec Visual Studio.

> \- L\'interface utilisateur doit être réalisée en Windows Forms.
>
> \- La base de données doit être réalisée avec Microsoft SQL Server.

**Critères d\'évaluation :**\
Respect des contraintes techniques

**Fonctionnalité :** L\'application doit remplir toutes les
fonctionnalités demandées.

**Base de données :** La base de données doit être correctement conçue
et utilisée pour stocker les informations.

**Tests unitaires :** Les tests unitaires doivent couvrir toutes les
fonctionnalités de l\'application et être écrits de manière
professionnelle.

**Code :** Le code doit être bien structuré, facile à comprendre en
suivant les bonnes pratiques de codage (lisibilité, maintenabilité,
modularité)

**Livrables**\
Les diagrammes UML.

Le code source de l\'application.

Le script SQL pour créer la base de données.

Les fichiers de configuration nécessaires pour exécuter les tests
unitaires.

Un rapport décrivant l\'architecture de l\'application et les choix

**Liens utiles**

