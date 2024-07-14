
```markdown
# Projet Profondeur de Neige

Ce projet est une application full stack construite avec React pour le frontend et Express pour le backend. Il vise à fournir des informations sur la profondeur de la neige en utilisant divers services.



```
###Structure des dossiers
```
-Frontend :client/neige
-Backend :server
```


## Prérequis

- Node.js
- Docker (pour le backend)
- npm ou yarn

## Démarrage

### Cloner le Répertoire

```bash
git clone https://github.com/votre-nom-utilisateur/profondeur_neige.git
cd profondeur_neige
```

### Installer les Dépendances

#### Client

```bash
cd client/neige
npm install
# ou
yarn install
```

#### Serveur

```bash
cd server
npm install
# ou
yarn install
```

### Lancer l'Application

#### Client

Pour démarrer l'application React :

```bash
cd client/neige
npm start
# ou
yarn start
```

#### Serveur

Pour démarrer le serveur Express :

```bash
cd server
node server.js
```

Pour démarrer le serveur avec Docker :

```bash
cd server
docker-compose up
```

## Construire pour la Production

#### Client

```bash
cd client/neige
npm run build
# ou
yarn build
```

#### Serveur

Le serveur peut être construit en utilisant Docker :

```bash
cd server
docker-compose build
```

## Fonctionnalités du Projet

- **React** pour le frontend
- **Express** pour le backend
- **Docker** pour la conteneurisation
- **Tileserver-GL** pour le service de tuiles de cartes

## Structure des Dossiers

### Client

- **neige/** : Contient l'application principale React.
- **node_modules/** : Contient les dépendances installées.
- **package.json** : Contient les dépendances et les scripts du projet.
- **package-lock.json** : Verrouille les dépendances du projet.

### Serveur

- **tileserver-gl/** : Contient les fichiers relatifs à Tileserver-GL.
- **node_modules/** : Contient les dépendances installées.
- **docker-compose.yml** : Fichier de configuration Docker Compose.
- **server.js** : Fichier principal du serveur.
- **package.json** : Contient les dépendances et les scripts du projet.
- **package-lock.json** : Verrouille les dépendances du projet.

## Contribution

Les contributions sont les bienvenues ! Veuillez ouvrir un ticket ou soumettre une pull request pour toute amélioration ou ajout.


## Contact

Pour toute question ou problème, veuillez contacter [wassimajbari123@gmail.com](mailto:votre-email@example.com).
```

