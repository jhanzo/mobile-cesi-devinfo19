# mobile-cesi-devinfo19

### Livrables attendus

- [ ] Fork du projet https://github.com/jhanzo/mobile-cesi-devinfo19
- [ ] Créer une nouvelle structure d'application mobile React Native
- [ ] Pousser le code sur le fork réalisé

Vous pourrez choisir le projet de votre choix dans la liste donnée dans la partie suivante. Mais si vous avez l'idée d'une application **SIMPLE** à réaliser, n'hésitez pas à développer votre propre idée. Le but est qu'elle soit présentable vendredi (même si incomplète). 

Vous fournirez alors :

Vous rappelerez les informations attendues suivantes dans un fichier README.md.

- [ ] La dernière version de votre projet qui contiendra un historique des commits efficaces
- [ ] Faire apparaitre les commandes principales utilisées (ex: `npx create...`) dans le README.md
- [ ] Un fichier .APK qui contiendra les sources de l'application réalisée et qui pourra être installée et testée sur mon téléphone
- [ ] Vous fournirez une application en ayant changé l'identifiant unique (bundleId) de l'application
- [ ] Vous présenterez en quelques minutes les fonctionnalités réalisées et celles restantes à développer, cette liste sera également présente dans le README.md

### Liste des projets disponibles

Vous essaierez autant que possible d'avoir une ergonomie (couleurs, style, polices, etc).

Votre projet contiendra au moins une notion du cours que vous n'avez pas encore vue : Caméra, Maps, Notifications, Webservice, Firebase Authent, Firebase Admob, SQLite, Realm, React Native naavigation, ...

##### Tout projet de votre choix

##### Application de partage de photos  

- Connexion avec Apple (ou Facebook ou Google ou ...) via [Firebase Authentication](https://rnfirebase.io/auth/usage)  
- Stockage de photos en base de données (Firestore)  
- Système de notations des photos utilisateurs 

##### Application de partage de photos

- Prendre une photo (caméra ou album)
- La partager (email, facebook, etc)
- Stocker un historique local des partages effectués

##### Application de traduction

- Changer la langue du téléphone par action sur un bouton
- Proposer un champ texte qui identifie la langue saisie par l'utilisateur via [Firebase ML](https://rnfirebase.io/ml-natural-language/usage)

##### Application de contenus publicitaires

- Spammer l'utilisateur avec beaucoup de contenus publicitaires via [Firebase Admob](https://rnfirebase.io/admob/usage)
- Ajouter un bouton qui permet à l'utilisateur de désactiver les publicités

##### Application qui affiche le contenu de push notifications

- [Firebase Cloud Messaging](https://rnfirebase.io/messaging/usage)

##### Application de gestion de réveils

- Lecture / Création / modification / Suppression de réveils et stockage dans une base (PAS de AsyncStorage, [Realm](https://realm.io/blog/introducing-realm-react-native/) ? [SQLite](https://github.com/andpor/react-native-sqlite-storage) ?)
- Afficher une alerte interne à l'app
- Afficher une notification alors que l'appli est fermée

##### Application de geofencing

- Détecter la localisation du téléphone et l'afficher sur une carte
- Détecter une action (à définir) qui s'exécute quand le device sort d'un certain périmètre
- Envoyer une notification locale lorsque le téléphone arrive près d'une position GPS
