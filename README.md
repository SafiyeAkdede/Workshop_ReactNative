## Workshop sur React Native

Introduction à React Native en réalisant une application.

---

## Table de matières

- [Technologies requises](#technologies-requises)
- [Installer et débuter avec Expo](#installer-et-débuter-avec-expo)
- [Commencer à coder](#commencer-à-coder)

---

# Technologies requises

***Voici les technos à avoir pour développer***

1. [React](https://reactjs.org/) : Une bibliothèque JavaScript pour créer des interfaces utilisateurs.
2. [React Native](https://reactnative.dev/) : Un framework pour créer des applications native en React.
3. [Expo](https://expo.io/) : Une plateforme d’émulation qui permet d’avoir une version directement fonctionnelle d'une application native.

---

# Installer et débuter avec Expo

Tout d'abord entrer cette ligne de commande dans le terminal pour installer Expo cli globalement :

>npm install -g expo-cli

Lancer ensuite la commande expo init suivi du nom du projet :

>expo init NoteApp

Lors de la création de l'application il faudra choisir entre 4 template proposés par expo :

![Les 4 template proposés](/images/ss_1.png)

Il faudra choisir "blank" à l'aide des flèches. Il va ensuite automatiquement installer les dépendances nécessaires. Le projet est maintenant prêt.

![Propositions pour lancer l'app](images/ss_2.png)

Pour lancer l'application il faut tout d'abord se déplacer dans le dossier :

>cd NoteApp

Il y a plusieurs façon de faire tourner l'application, les méthodes les plus simples sont sur les points 3 et 4 :

**1. Installer un émulateur Android et/ou IOS :**

  Voir les instructions [ici](https://reactnative.dev/docs/environment-setup) sur "React Native CLI Quickstart" et en choisissant l'OS du pc et l'OS du smartphone. Ensuite lancer avec :
  
  >npm run android

  ou

  >npm run ios

**2. Tester en ligne sur Snack Expo :**

  Aller [ici](https://snack.expo.io/), ajouter tous les dossiers et fichiers nécessaires. Le résultat s'affiche à droite de la page.

**3. Télécharger l'application mobile Expo :**

  Sur [Android](https://play.google.com/store/apps/details?id=host.exp.exponent&gl=BE) ou [IOS](https://apps.apple.com/be/app/expo-client/id982107779?l=fr) télécharger l'application Expo et l'ouvrir. Il faudra alors soit créer un compte Expo et stocker notre application NoteApp dessus ou juste scanner le code QR. Pour trouver le code QR il suffit de lancer sur le terminal :

  >npm run web

  ou

  >npm start

  Le code QR sera alors généré sur le terminal et sur le localhost:19002.

**4. Lancer sur le web :**

  Sur le terminal :

  >npm run web

  Deux pages vont alors s'ouvrir :
  
- Sur le localhost:19002 va s'afficher le log, les appareils connectés, la possibilité de lancer l'app de différentes manières et le code QR.

- Sur le localhost:19006 va s'afficher le résultat de notre app.

---

# Commencer à coder
