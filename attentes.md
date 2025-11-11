---
title: "Attentes — eClinibase (min)"
permalink: /attentes/
layout: default
description: "Version minimale : Attente (Identification, Détail, Prérequis, Non-disponibilité, Communication, Mécanisme d’accès, Réouverture)."
---


# Attentes — contenu minimal

> **Périmètre** : Cette page reflète strictement la marche à suivre eClinibase du CISSS des Laurentides.
> Ne pas extrapoler : si une info manque, se référer à **/procedures/** (verbatim) ou aux **pilotes eClinibase**.


### Détail — Champs et règles

| Champ              | Statut          | Règle courte / Note |
|--------------------|-----------------|---------------------|
| Date/heure début   | **Obligatoire** | Date de début d’attente (voir règles *nouveau cas* vs *relance*). |
| Raison de consultation | **Obligatoire** | Sélection via liste. |
| Spécialité         | **Obligatoire** | — |
| Sous-service       | **Obligatoire** | Se remplit selon *Service requis*. |
| Service requis     | **Obligatoire** | **Sélectionner d’abord** (pilote les autres champs). |
| Type de R.V.       | **Obligatoire** | Harmonisé : *Nouveau cas* / *Suivi*. |
| Priorité médicale  | **Obligatoire** | Délais auto selon priorité (voir Annexe 4). |
| Ressource          | Au besoin       | Laisser vide si inconnu. |
| Mode d’intervention| Au besoin       | En personne / tél. / téléconsultation… |

> **Communication — Obligation** : si **le résultat ≠ rendez-vous**, alors **Objet** et **Résultat** sont requis.


> Règle : uniquement listes/tables/libellés exacts. Les explications longues ont été retirées pour réduire les hallucinations.

## Sommaire

- Identification
- Détail (champs obligatoires)
- Prérequis
- Non-disponibilité
- Communication (quand obligatoire)
- Mécanisme d’accès
- Réouverture d’une attente

## Réouverture d’une attente fermée sans que l’usager ait bénéficié du service
- 1- Ouvrez le Power BI <http://cissslaurentides.intranet.reg15.rtss.qc.ca/espace-gestion/tableaux-de-bord/>

- 2- Sélectionnez les données reliées à votre clinique externe.

- 3- Valider pour chaque usager, si vous devez restaurer l'attente de celui-ci.

  - Posez-vous la question suivante : Après l'attribution du rendez-vous, est-ce que l'usager a obtenu un rendez-vous dans le service requis pour lequel il est initialement en attente ?
    - i. Si oui, ne rien modifier. L'attente restera fermée tout simplement.
    - ii. Si non, vous référez au point suivant (étape 4).

- 4- Ouvrez l'application eClinibase.

- 5- Ouvrez le module « Gestion des rendez-vous ».

- 6- Recherchez l'usager ainsi que le rendez-vous concerné via la fenêtre de recherche.

- 7- Assurez-vous que la date de début dans l'onglet « Attente » concorde avec la date dans le fichier Excel.

- 8- Annulez le rendez-vous en appuyant sur le statut « Annulé ».

- 9- Veuillez sélectionner la raison d'annulation suivante : Erreur.

- 10- Sélectionnez l'option « Réactiver l'attente d'origine de l'usager ».

- 11- Sélectionnez « Ok ».
## **Cliniques externes-Attente**




### **1. Champs obligatoires dans l'attente**




### **1.4 Prérequis**


Prérequis (liste déroulante) : Sélectionner un prérequis.

Si le prérequis à entrer n'est pas présent, faire une demande au [eclinibase.cissslau@ssss.gouv.qc.ca.](mailto:eclinibase.cissslau@ssss.gouv.qc.ca)

Statut du prérequis : indique si le prérequis est complété ou non.

- Au DSQ : le prérequis est complété et disponible au DSQ
- À planifier : le prérequis est à faire
- Autre : autre raison, ajouter commentaire, le prérequis n'est pas réalisé.
- Réalisé : le prérequis est complété.

**Assurez-vous d'utiliser la colonne « Statut des prérequis » dans votre liste d'attente.**

**Trois statuts y sont associés :**

- Sans prérequis : aucun prérequis entré
- Non réalisé : prérequis entré et non complété
- Réalisé : prérequis entré et complété

**Vous devez prévoir un mécanisme de vérification des prérequis afin d'éviter des usagers qui seront hors délais à l'octroi du rendez-vous.**

**Une bonne gestion des « Prérequis » permet d'éviter de donner des rendez-vous aux usagers inutilement.**

#### **1.5 Non-disponibilité**


**Champs à compléter au besoin :**

Date de début : Entrer la date de début de la non disponibilité

- Personnelle (cesse le calcul du délai d'attente)
- Médicale (ne cesse pas le calcul du délai d'attente)

Commentaire : tout commentaire pertinent à la non-disponibilité, idéalement une précision sur la raison.

**L'entrée des « Non-disponibilité » permet d'éviter les appels inutiles et diminue les usagers ayant une attente de rendez-vous hors délai.**

#### **1.6 Mécanisme d'accès et Communication**




### **1.6.1 Communication**


**Champs à compléter au besoin :**

- Mode : Méthode de communication

- Détails du résultat : Toutes informations pertinentes

- Commentaire : Toutes informations pertinentes

**Circonstance obligatoire : si le résultat de la communication n'est pas un rendez-vous. :**

- Objet (liste déroulante) : But de la communication

- Résultat (liste déroulante) : Ce qui en a découlé (certains résultats activeront le mécanisme d'accès<sup>1</sup> )

- Interlocuteur : À compléter si on ne parle pas à l'usager directement

- Nom de l'interlocuteur : Nom de la personne si on ne parle pas à l'usager directement

#### **1.6.2 Mécanisme d'accès**


C'est la fenêtre où s'accumule les différents mécanismes, excepté les périodes de non-disponibilité.

- Un indicateur bleu indique une activation des mécanismes d'accès.
- Un indicateur rouge indique un indicateur un maximum atteint et la possibilité de retirer un usager de la liste d'attente.

Case « Ignorer » : au besoin, il est possible d'ignorer des entrées, ajouter une précision.

Deux manières d'effectuer la gestion des mécanismes d'accès

1. Par la liste d'attente en utilisant les colonnes suivantes :
- Max. mécanismes d'accès

- Max. absences atteint

- Max. incapacités atteint

- Max. reports/refus atteint

Les cases cochées indiquent qu'un usager peut être retiré de la liste d'attente.

2. En utilisant la section dédiée dans la barre de recherche.

Nombre maximal atteint :

Incapacités à joindre l'usager

Seules les attentes ayant atteints le maximum permis sortiront sur la liste.

**L'algorithme sur la gestion des mécanismes d'accès est disponible dans l'intranet :**

#### **7.3.5. Attentes (de l'usager)**


Il est possible d'effectuer des recherches plus précises à l'aide des différents champs de la barre de recherche.

### **7.4.1. La gestion des attentes**


Pour consulter les attentes, aller dans l'onglet « Accueil/Prise en charge », choisir « Attente » et sélectionner « Gestion des attentes ».

- 1. Avant d'ouvrir une attente, vérifier si le patient n'en a pas déjà une d'ouverte pour ce service requis. Dans la barre de recherche, entrer le numéro de dossier de l'usager. Si vous ne connaissez pas son numéro de dossier. Appuyer sur les trois petits points ( ... ) et effectuer votre recherche selon le numéro de RAMQ et/ou date de naissance (selon les normes de saisies du CISSS des Laurentides en **annexe 2**).
- 2. Si l'usager n'a pas d'attente ou de dossier, vous pouvez en créer une en appuyant sur le "+" (en haut, à droite)

## **7.4.1.2.1. Information sur l'attente**


- Date/heure inscription : date et heure à laquelle on a appuyé sur Ajouter (ce champ n'est pas modifiable)
- Date/heure réception : date et heure à laquelle on a reçu la requête ou à laquelle on la décision de revoir l'usager a été prise.
- Date/heure début : date et heure à laquelle l'usager commence à être en attente (indépendamment du délai de traitement administratif.)
  - Pour une attente de nouveau cas, la date de réception et la date de début seront la même.
  - **Pour une attente de relance, la date de début s'ajustera automatiquement suite à l'entrée de la priorité médicale de suivi.**

### **7.4.1.2.2. Objet de l'attente**


- Sélectionner le service requis EN PREMIER selon la liste déroulante (le sous-service s'affichera automatiquement). <sup>1</sup>
- Sélectionner le type de rendez-vous selon la liste déroulante.
- Sélectionner la raison de consultation selon la liste déroulante, au besoin.
- La précision de la période permet d'ajouter une précision reliée au rendez-vous, exemple : les cas de CRDS...
- Le mode d'intervention permet d'introduire la manière dont le rendez-vous est effectué : en personne, par téléphone, téléconsultation, etc.
- Ressource : Inscrire une ressource, seulement dans les cas où l'usager est pris en charge par un professionnel en particulier ou qu'il est certain qu'il sera revu par ce même professionnel. Le type de ressource se complètera automatiquement.

<sup>1</sup> *Pour les Relance, inscrire la ressource en premier permet de restreindre les choix de services requis à ceux permis pour la ressource.*

## **7.4.1.3.1. Fermeture de l'attente**


- Inscrire la date de fermeture
- Sélectionner la raison de fermeture selon la liste déroulante. Choisissez la raison la plus précise.
- Au besoin, ajouter une précision sur la raison (texte libre)

## **Non-disponibilité**


- Appuyer sur le "+" pour ajouter une non disponibilité
- Inscrire l'intervalle de date entre laquelle l'usager ne sera pas disponible
- Choisir entre une raison MÉDICALE ou PERSONNELLE
- Inscrire un commentaire qui explique la raison

Une non-disponibilité pour raison personnelle n'est pas une raison pour prioriser l'attribution d'un rendez-vous. En aucun cas.

#### **7.4.2. Mécanismes d'accès et communications**




#### **Mécanisme d'accès**


C'est dans cet onglet que se compilent toutes les communications qui peuvent mener à une radiation de la liste d'attente.

Pour vous aider dans la gestion des mécanismes d'accès, veuillez vous référez à l'annexe 5.

## **Communications**


L'onglet « Communications » sert à compiler et à conserver la trace de toutes les communications faites avec l'usager.

- Appuyer sur le "+" pour ajouter une communication
- Choisir le type de communication
- Sélectionner l'objet selon la liste déroulante
- Sélectionner le résultat selon la liste déroulante
- Inscrire un détail au besoin
- Sélectionner l'interlocuteur selon la liste
- Inscrire le nom de l'interlocuteur, s'il ne s'agit pas de l'usager
- Inscrire un commentaire au besoin

### **8.1. Module « Gestion des attentes »**


- Ouvrez eClinibase.
- Ouvrez le module « Gestion des attentes ».

La barre de recherche se situe à gauche de l'écran et c'est à ce niveau que vous devrez entrer vos critères de recherche.

 Cochez la case « Inclure les attentes fermées » si vous désirez obtenir la liste des attentes ayant été fermées.

Cliquez sur le bouton « Rechercher ».

 Extraire le rapport en Excel en sélectionnant l'option « Afficher le menu d'exportation des grilles ».

Imprimer le rapport en sélectionnant l'icône de l'imprimante si nécessaire

### Voir aussi

- [Recherche de disponibilité]({{ site.baseurl }}/rendezvous/)
- [Normes — Priorité médicale]({{ site.baseurl }}/normes-saisie/)

