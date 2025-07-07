# 🩷 MLO - Le Langage de Programmation Web Interactif ♥️

---

## 🚀 Bienvenue dans MLO !

MLO (prononcé "M.L.O.") est un langage de programmation **intuitif et accessible**, conçu spécifiquement pour la **création rapide de contenu interactif directement sur le web**. Oubliez les installations complexes : MLO fonctionne sur son site dédié, vous permettant d'écrire votre code, de cliquer sur "Exécuter" et de voir vos créations prendre vie instantanément.

Idéal pour les débutants, les éducateurs, les conteurs numériques et quiconque souhaite créer des expériences web dynamiques sans plonger dans la complexité du JavaScript ou d'autres frameworks web.

---

## ✨ Caractéristiques Clés

MLO est bâti avec la simplicité et l'interactivité en tête :

* **Exécution Instantanée :** Écrivez votre code sur le site MLO, cliquez sur "Run", et voyez le résultat apparaître en temps réel.
* **Contenu Visuel Riche :** Intégrez facilement du texte coloré, des effets arc-en-ciel et des images pour rendre vos projets plus attrayants.
* **Interactivité Simplifiée :** Créez des histoires à choix multiples, des quiz et des formulaires d'entrée utilisateur sans effort.
* **Logique de Base :** Manipulez des variables (texte, nombre, booléen), effectuez des calculs mathématiques et contrôlez le flux de votre programme avec des conditions.
* **Génération Aléatoire :** Ajoutez des éléments imprévisibles à vos jeux ou simulations avec des fonctions de texte et de nombre aléatoires.

---

## 📖 Démarrage Rapide

Pour commencer avec MLO, rendez-vous sur le [site officiel de MLO](https://mlo-code-m5z1rb0m.adaptive.ai/?_ogb=true&_evid=M2BzLrfqm86MpGC3).

1.  **Accédez à l'éditeur :** Sur la page principale, vous trouverez une zone de texte où vous pouvez écrire votre code MLO.
2.  **Écrivez votre premier programme :**
   
 ```
    MLO imprime "Bonjour le Monde MLO !"
    MLO délai 1000
    MLO text couleur vert "Ceci est mon premier pas avec MLO."
    MLO délai 1500
 MLO VarText nom = "Votre nom"
    MLO imprime "Salut,  Amuse-toi bien. Ton nom est"
MLO imprime nom
MLO ciel "MLO est génial !"
```

3.  **Exécutez le code :** Cliquez sur le bouton "Run" (ou "Exécuter") pour voir votre programme prendre vie dans la zone de sortie.

--
# 🩵 Documentation de MLO 🩵

### Commandes de Base

* `MLO imprime "texte"` : Affiche le `texte` à l'écran.
* `MLO simple_variable nom = valeur` : Crée une variable numérique ou booléenne.
    * Ex: `MLO simple_variable age = 30`
* `MLO VarText nom = "texte"` : Crée une variable de type texte.
    * Ex: `MLO VarText message = "Bienvenue"`
* `MLO booléenne nom = true` / `false` : Crée une variable booléenne 
* `MLO input "question"` : Demande une saisie à l'utilisateur. 
* `MLO interactive "question|choix1|choix2|..."` : Présente des choix multiples à l'utilisateur (écrivez si possible le contexte dans chaque choix, mais n'oubliez pas d'être créatif!)

### Affichage et Effets Visuels

* `MLO image "url_de_l_image"` : Affiche une image depuis l'URL de lien hébergé fournie.
* `MLO text couleur [nom_couleur] "texte"` : Affiche le `texte` dans la `couleur` spécifiée (ex: `rouge`, `bleu`, `vert`).
* `MLO ciel "texte"` : Affiche le `texte` avec un effet arc-en-ciel.
* `MLO délai millisecondes` : Met le programme en pause pour le nombre de `millisecondes` spécifié.

### Mathématiques et Logique

* `MLO calcul nom_variable = expression_mathématique` : Effectue un calcul et assigne le résultat à une `nom_variable`.
    * Ex: `MLO calcul resultat = 5 + 3 
* `MLO math racine nombre` : Calcule la racine carrée du `nombre`.
* `MLO math puissance base exposant` : Calcule la puissance (`base` élevé à l'`exposant`).
* `MLO math abs nombre` : Retourne la valeur absolue du `nombre`.
* `MLO math min nombre1 nombre2 ...` : Retourne la valeur minimale parmi les nombres fournis.
* `MLO math max nombre1 nombre2 ...` : Retourne la valeur maximale parmi les nombres fournis.
* `MLO if condition alors "message_vrai" sinon "message_faux"` : Exécute une branche de code basée sur une `condition`. (Note: Si votre `if` peut exécuter plusieurs lignes, remplacez les messages par des blocs de code comme dans l'exemple de l'histoire interactive que nous avons fait).
    * Ex: `MLO if age >= 18 alors "Adulte" sinon "Mineur"`
* `MLO random text "opt1|opt2|opt3"` : Sélectionne et affiche aléatoirement une option parmi celles fournies.
* `MLO random nombre min max` : Génère un nombre entier aléatoire entre `min` et `max` (inclus).

---

## 💡 Idées de Projets avec MLO

Avec MLO, vous pouvez créer :

* **Histoires Interactives :** Des aventures textuelles à choix multiples.
* **Quiz et Sondages :** Des questionnaires amusants avec feedback immédiat.
* **Jeux Simples :** Comme "Devine le nombre", des dés virtuels, ou des mini-simulations.
* **Outils Utilitaires :** Petits calculateurs ou générateurs aléatoires.
* **Cartes de Vœux Animées :** Des messages personnalisés avec des images et des effets.

Laissez libre cours à votre imagination !

---

## 🤝 Contribuer

MLO est un projet passionnant et nous sommes ouverts aux suggestions et aux contributions. Si vous avez des idées de nouvelles fonctionnalités, des améliorations ou si vous trouvez un bug, n'hésitez pas à :

** Ouvrir une **Issue** sur ce dépôt GitHub.**

---

## Avez-vous une question ou un projet MLO à partager ?

N'hésitez pas à ouvrir une discussion sur le dépôt ou à nous contacter !
