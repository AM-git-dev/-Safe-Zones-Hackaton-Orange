# Safe Zones

Bienvenue dans ce projet ! Cette application a été conçue sur base d'API's fournies par Orange, malheureusement celles-ci étaient en phase de béta et donc surement plus disponible a ce jour, 

## Fonctionnalités

-Creéation de zone "GéoFencing" permettant de délimiter un périmètre autour d'une addresse, permettant de notifier toute entrée ou sortie de ce périmètre d'un numéro de téléphone mobile renseigné.
-Cette application a pour but de protéger enfants, personnes agées, personnes malades ou bléssées en prévenant une personne de confiance de son entrée sortie de la zone définie (Domicile, Ecole, Hopital, Maison de retraite etc etc) 
-Si la personne est sortie de ce rayon, via une API nommée Device Location Retrieval, on peut retrouver la position de la dite personne, permettant par exemple a la famille d'agir si une personne atteinte d'Alzeihmer venait à s'égarer et oublier ou elle se trouve.


## Prérequis

Avant de commencer, assurez-vous d'avoir :

- [Node.js](https://nodejs.org/) installé (version LTS recommandée).
- npm ou un autre gestionnaire de packages comme Yarn.
- Une clé API obtenable sur l'espace Orange developer ou toute autre variable nécessaire (voir fichier `.env`).

## Installation

1. Clonez ce dépôt sur votre machine locale :

   ```bash
   git clone https://github.com/votre-utilisateur/nom-du-projet.git
   ```

2. Accédez au dossier du projet :

   ```bash
   cd nom-du-projet
   ```

3. Installez les dépendances nécessaires :

   ```bash
   npm install
   ```

4. Configurez vos variables d'environnement :
   - Renommez le fichier `.env.example` en `.env` (s'il existe) ou créez un fichier `.env`.
   - Ajoutez-y les variables nécessaires, par exemple :

     ```env
     PORT=3000
     DATABASE_URL=VotreURLDeBaseDeDonnées
     ```

## Lancement

1. Démarrez l'application en mode développement :

   ```bash
   npm run dev
   ```

2. Ouvrez votre navigateur et accédez à :

   ```
   http://localhost:3000
   ```

## Scripts Disponibles

Les scripts suivants sont définis dans le fichier `package.json` :

- `npm run dev` : Démarre l'application en mode développement.
- `npm start` : Lance l'application en mode production.
- `npm test` : Exécute les tests (si configurés).

## Structure du Projet

- **app.js** : Point d'entrée principal de l'application.
- **routes/** : Définit les routes de l'application.
- **controllers/** : Contient la logique métier.
- **models/** : Définit les schémas de données.
- **views/** : Contient les vues ou templates.
- **public/** : Contient les fichiers statiques (CSS, JS, images).
- **services/** : Regroupe les services auxiliaires (API, utilitaires, etc.).

## Contribuer

Les contributions sont les bienvenues. Voici comment contribuer :

1. Forkez ce dépôt.
2. Créez une branche pour votre fonctionnalité :

   ```bash
   git checkout -b nouvelle-fonctionnalite
   ```

3. Effectuez vos modifications et validez-les :

   ```bash
   git commit -m "Ajout d'une nouvelle fonctionnalité"
   ```

4. Poussez vos modifications :

   ```bash
   git push origin nouvelle-fonctionnalite
   ```

5. Ouvrez une Pull Request.


---

Merci de contribuer à ce projet ! Si vous avez des questions ou des suggestions, n'hésitez pas à les partager.
