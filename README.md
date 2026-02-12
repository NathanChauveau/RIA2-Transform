# RIA2-Transform

## Description

Le but du ce projet est de réaliser la partie "Transform" d'un ETL

Il consiste a récupérer des datas venant d'un bucket*, de les transformer afin qu'ils soient utilisable par le "Load" et de les déposer dans un bucket prévu pour être repris par le "Load".

Il doit aussi pouvoir réaliser le job sans qu'il soit bloqué avec une méthode en execution.


## Fonctionnalités principales du conteneurs

- Télécharger un/plusieurs fichiers contenant des datas d'un bucket*
- Transforme les datas reçu*
- Déposer le/les fichiers final/aux contenant les datas transformé dans un bucket*

Fournisseur :
Amazon Web Services (AWS)

## Pour commencer

### Prérequis

* PHP 8.3.11 
* Visual Studio Code 1.105.1 
* Composer 2.8.12 
* Windows 11 Éducation 24H2
(require a recheck for all tbs)

### Configuration

## Déploiement

### Sur l'environnement dev

Recevez tous les paquets du projet via cette commande là:
```shell
composer install
```
puis réalisé un serve :
```shell
composer serve
```

Pour tester tous les testes, réalisé cette commande là:
```shell
./vendor/bin/phpunit
```
Pour un test uniquement :
```shell
./vend
```

## Structure du répertoire 

```shell

```

## Question 

- Bucket uniquement sur AWS ?
- Nom des buckets déjà su par le conteneur ? (prédéfinis ou non)
- Séparer les différents mannière de transformer en plusieurs méthodes ?
- Est-ce que l'orchestrateur n'execute qu'une seule methéode par passage ou chaque étape du "Transform" ?
- Type de fichier est déjà connu/prédéfini ?

## Collaboration

### Convention
Commit
Ce projet utilise les [Conventional Commits](https://www.conventionalcommits.org/). Les mots principaux étant: "feat, fix, chore, refactor, test, docs" en anglais pour ce projet.

Workflow
Ce projet utilise Git. Les branches utilisés sont les suivantes: main, develop, feature, release, hotfix. Les noms des branches suivent ce pattern: type/shortDescription eg.(feature/awesomeFeature).

* Il faut savoir :
  * Comment proposer une nouvelle feature (issue, pull request)
  * [Comment commit](https://www.conventionalcommits.org/en/v1.0.0/)
  * [Comment utiliser votre flux de travail](https://nvie.com/posts/a-successful-git-branching-model/)

## Contact

| Développeur           | Email                         |
| --------------------- | ----------------------------- |
| Nathan Chauveau       | <nathan.chauveau@eduvaud.ch>  |
