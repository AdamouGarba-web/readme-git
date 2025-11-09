# Project Git/GitHub
## Objectif Général

Cette série d’exercices m’a permis de comprendre et de pratiquer le contrôle de version avec Git et GitHub, de la création d’un dépôt jusqu’à la gestion de conflits.
À travers 3 exercices, j’ai appris à :  

* Créer et gérer un dépôt local et distant.

* Effectuer des commits et suivre l’historique.

* Travailler avec des branches et des pull requests.

* Résoudre des conflits de fusion. 
 
## Éléments Clés de l’Apprentissage

__1. Commandes Git de Base__
| Commande                  | Rôle                                                    |
| ------------------------- | ------------------------------------------------------- |
| `git init`                | Initialise un nouveau dépôt Git local                   |
| `git clone <url>`         | Clone un dépôt distant vers le local                    |
| `git add <fichier>`       | Ajoute les fichiers à la zone de transit (staging area) |
| `git commit -m "message"` | Enregistre les changements dans l’historique            |
| `git push`                | Envoie les commits locaux vers le dépôt distant         |
| `git log`                 | Affiche l’historique des commits                        |

- Objectif : Comprendre comment suivre les modifications et garder un historique clair de son travail.
__2. Collaboration et Branching__

| Concept               | Description                                                                                               |
| --------------------- | --------------------------------------------------------------------------------------------------------- |
| **Branche (branch)**  | Une copie parallèle du projet pour développer une nouvelle fonctionnalité sans impacter le code principal |
| **Pull Request (PR)** | Une demande de fusion de code entre deux branches (souvent de *feature branch* → *main*)                  |
| **Merge**             | L’action de combiner les changements de deux branches                                                     |

- Objectif : Travailler en équipe efficacement et isoler le développement de nouvelles fonctionnalités.
__3. Gestion des Conflits et Maintenance__
| Situation                                          | Solution                                                                                                                |
| -------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------- |
| Deux branches modifient la même ligne d’un fichier | Git ne sait pas laquelle garder → **conflit**                                                                           |
| **Résolution**                                     | Modifier manuellement le fichier pour conserver la bonne version (ou les deux), puis faire un `git add` et `git commit` |

- Objectif : Comprendre et résoudre les merge conflicts — une compétence indispensable dans les projets collaboratifs.

### Exercice N°1: First Repo & Simple Commit

![](./cature%20d'ecran%20du%20premier%20exo/Capture%20d’écran%202025-11-08%20à%2003.04.00.png)
![](./cature%20d'ecran%20du%20premier%20exo/Capture%20d’écran%202025-11-08%20à%2003.04.16.png) 

__Objectif__ : Apprendre à créer un dépôt GitHub, suivre les changements et consulter l’historique.
__Etapes realisées__

    1. Création d’un repo nommé git-learning-1 sur GitHub.
    2. Clonage local : git clone <url_du_repo>.
    3. Création du fichier README.md avec le texte “Mon premier projet Git”.
    4. Ajout d’une nouvelle ligne avec mon nom et le numéro de mon Mac.
    5. Commit (git commit -m "Ajout d'informations personnelles") puis push (git push).
    6. Vérification de l’historique des commits sur GitHub.
*__Compétences acquises__* :

* Cycle complet : création → modification → commit → push.
* Compréhension du staging area et de l’historique Git.
### Exercice N°2: Branching & Merging

![](./cature%20d'ecran%20du%20premier%20exo/Capture%20d’écran%202025-11-08%20à%2023.23.39.png)
![](./cature%20d'ecran%20du%20premier%20exo/Capture%20d’écran%202025-11-08%20à%2023.22.44.png)

__Objectif__: Créer une branche, y apporter des changements et la fusionner avec main.

__Étapes réalisées__

    1. Création d’un repo git-learning-2.
    2. Création d’une nouvelle branche : git checkout -b myself.
    3. Création du fichier about.txt avec mes informations personnelles.
    4. Commit et push de la branche myself.
    5. Création d’un Pull Request (PR) depuis myself vers main
    6. Fusion (merge) de la PR sur GitHub.

*__Compétences acquises__* :

* Création et gestion de branches.
* Utilisation des pull requests pour intégrer du code proprement.
* Compréhension du flux de travail collaboratif GitHub.
### Exercice N°3 — Gestion des Conflits durant le Merging

![](./cature%20d'ecran%20du%20premier%20exo/Capture%20d’écran%202025-11-09%20à%2008.24.47.png)
![](./cature%20d'ecran%20du%20premier%20exo/Capture%20d’écran%202025-11-09%20à%2008.26.50.png)
![](./cature%20d'ecran%20du%20premier%20exo/Capture%20d’écran%202025-11-09%20à%2008.27.04.png)

__Objectif__ : Comprendre comment apparaissent les conflits et savoir les résoudre.

__Étapes réalisées__

    1. Création du repo git-learning-3.
    2. Sur main, ajout de notes.txt avec le texte “Ligne écrite depuis la branche main”.
    3. Création de la branche conflict-test et modification du même fichier.
    4. Commit et push sur les deux branches.
    5. Tentative de merge → conflit détecté.
    6. Ouverture du fichier notes.txt, résolution manuelle en gardant les deux lignes.
    7. Commit final après résolution.
*__Compétences acquises__* :

* Détection et compréhension des conflits de fusion.
* Résolution manuelle dans un éditeur de code.
* Validation de la version finale synchronisée avec GitHub.
## Conclusion

Grâce à ces trois exercices, j’ai acquis une vision complète du cycle Git/GitHub, depuis la  
création d’un projet jusqu’à la résolution de conflits en équipe.
Je me sens désormais capable de :

* Gérer efficacement mes versions de code.
* Collaborer sur des projets via GitHub.
* Résoudre des conflits de fusion de manière autonome.

__NOM: ADAMOU GARBA RIDIWANE__  
__FORMATION: APPRENANT CODELOCCOL__
