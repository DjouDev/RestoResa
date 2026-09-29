````markdown
# 🍽️ RestoResa

RestoResa est une application web fictive de réservation de restaurants.

Elle permet aux utilisateurs de découvrir, réserver et évaluer des établissements en quelques clics.

Le projet permet d’expérimenter les workflows de contribution, les pull requests, la gestion d’issues et le versionnement collaboratif, comme dans un environnement professionnel réel.

## Pour bien démarrer

Ce projet a été conçu comme support pédagogique pour découvrir les bonnes pratiques de collaboration avec Git et GitHub.

Tu vas notamment apprendre à :

- consulter un dépôt GitHub ;
- forker un projet ;
- cloner un dépôt en local ;
- modifier un fichier ;
- utiliser Git pour suivre tes modifications ;
- créer des commits ;
- traiter une issue ;
- proposer une contribution via une pull request.

Aucune installation de dépendances n’est nécessaire pour réaliser les exercices proposés dans ce dépôt.

## Prérequis

Avant de commencer, assure-toi d’avoir :

- Git installé sur ton ordinateur ;
- un éditeur de code, comme Visual Studio Code ;
- un navigateur web moderne ;
- un compte GitHub personnel.

## Travailler sur le projet en local

### 1. Forke le dépôt

Commence par créer une copie du projet sur ton propre compte GitHub en cliquant sur le bouton `Fork`.

### 2. Clone ton fork sur ton ordinateur

Récupère ensuite l’adresse de ton propre fork, puis utilise la commande :

```bash
git clone https://github.com/TON-UTILISATEUR/RestoResa.git
````

Place-toi ensuite dans le dossier du projet :

```bash
cd RestoResa
```

Tu peux maintenant ouvrir le projet dans Visual Studio Code.

## Comprendre les fichiers du projet

Avant de commencer une contribution, prends le temps de consulter les fichiers suivants :

* `README.md` : présente le projet et son fonctionnement ;
* `Contributing.md` : explique les règles à respecter pour contribuer ;
* `Code_of_conduct.md` : présente les règles de comportement à adopter dans le cadre du projet.

## Contribuer

Les tâches à réaliser sont proposées sous forme d’issues GitHub.

Avant de modifier un fichier :

1. consulte les issues disponibles ;
2. choisis l’issue que tu souhaites traiter ;
3. lis attentivement la demande ;
4. effectue la modification en local.

Après avoir modifié un fichier, vérifie l’état de ton projet :

```bash
git status
```

Ajoute ensuite le fichier modifié :

```bash
git add nom-du-fichier
```

Crée ton commit avec un message clair :

```bash
git commit -m "Description de la modification"
```

Puis envoie tes modifications sur ton fork :

```bash
git push origin main
```

Une fois la modification envoyée sur GitHub, tu peux créer une pull request afin de proposer ta contribution au dépôt principal.

## Pull requests

Une pull request permet de proposer une modification au projet principal.

Lors de sa création :

* indique clairement ce que tu as modifié ;
* précise l’issue concernée ;
* utilise un titre compréhensible ;
* ajoute une courte description de ta contribution.

Dans un véritable projet professionnel, un autre membre de l’équipe pourrait ensuite relire ton travail, demander des modifications ou accepter ta contribution.

## Auteurs

* Berenice-Oravendis – Mainteneur principal
* Contributions bienvenues via les pull requests !

## Licence

Ce projet est sous licence MIT. Consulte le fichier `License` pour plus d’informations.

---

*RestoResa est un projet fictif à but pédagogique, développé dans le cadre de formations au développement web. Il a pour objectif principal de permettre aux apprenants de pratiquer la collaboration avec Git et GitHub.*

```
