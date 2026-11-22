PlantEvo Viewer

Site web statique (HTML + CSS) qui raconte l'évolution des végétaux, des milieux aquatiques jusqu'aux forêts : **« Du milieu aquatique aux Forêts : La Grande Conquête Végétale »**.

Projet réalisé dans le cadre du **Brief 1** de la Digital Farming School (DFS).

 Objectif

Permettre au visiteur de découvrir les grands groupes de végétaux, dans l'ordre de leur apparition, et de passer facilement d'une page à l'autre.

 Pages du site

| Page | Rôle |
|---|---|
| Accueil | Présente le site et son thème |
| Menu | Affiche les groupes de plantes ; chaque image est cliquable vers sa page |
| Algues | Page du groupe des algues |
| Mousses | Page du groupe des mousses |
| Fougères | Page du groupe des fougères |
| Conifères | Page du groupe des conifères |
| Dicotylédones | Page du groupe des dicotylédones |
| Graminées | Page du groupe des graminées |
| Recherche | Champ de saisie pour chercher un groupe, relié aux autres pages |

 Structure du projet

```
PlantEvo-Viewer/
├── README.md
├── style.css          (un seul fichier de style pour toutes les pages)
├── html/
│   ├── Accueil.html
│   ├── Menu.html
│   ├── Algues.html
│   ├── Mousses.html
│   ├── Fougères.html
│   ├── Conifères.html
│   ├── Dicotylédones.html
│   ├── Graminées.html
│   └── Recherche.html
└── images/
    └── Logo.webp
```

> Adapte les noms de fichiers si les tiens sont différents.

Technologies utilisées

- HTML : la structure des pages
- CSS : le style (couleurs, mise en page), dans `style.css`

Aucun framework, aucun JavaScript : le site s'ouvre directement dans le navigateur.

Lancer le site

1. Télécharge ou clone le projet.
2. Ouvre le fichier `html/Accueil.html` dans ton navigateur (double-clic).
3. Navigue grâce au menu et aux liens.

Ajouter tes images

Les balises `<img>` sont déjà dans le code. Il te suffit de :

1. mettre ton image dans le dossier `images/` ;
2. mettre à jour l'attribut `src` avec son nom ;
3. écrire un texte `alt` qui décrit l'image ;


Exemple :

```html
<img class="image-gauche" src="../images/algues.jpg" alt=" Algue verte filamenteuse">
```

Auteur

 BENE AXEL JUNIOR, étudiant à la Digital Farming School.