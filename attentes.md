---
title: "Attentes — eClinibase"
permalink: /attentes/
layout: default
description: "Gestion des attentes : Identification, Détail, Prérequis, Non-disponibilité, Communication, Mécanisme d’accès, Réouverture."
tags: ["eClinibase","Attente","Cliniques externes","Détail","Communication","Mécanisme d'accès","Prérequis","Non-disponibilité","Réouverture"]
---

# Gestion des attentes — Attente

## Sommaire
- [Identification](#identification)
- [Détail](#detail)
- [Prérequis](#prerequis)
- [Non-disponibilité](#non-disponibilite)
- [Communication](#communication)
- [Mécanisme d’accès](#mecanisme-dacces)
- [Réouverture d’une attente](#reouverture)

## Réouverture d’une attente fermée sans que l’usager ait bénéficié du service

{0}------------------------------------------------

## **Réouverture d'une attente fermée**

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

{2}------------------------------------------------

## Aide-mémoire Cliniques externes attente

{0}------------------------------------------------

## **Cliniques externes-Attente**



### **1. Champs obligatoire dans l'attente**



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

{5}------------------------------------------------

#### **1.5 Non-disponibilité**

**Champs à compléter au besoin :**

Date de début : Entrer la date de début de la non disponibilité

Date de fin : Entrer la date de fin pour mettre fin à la non-disponibilité. Bien que non obligatoire, le risque d'oubli est grand donc, fortement suggéré de l'entrer dès l'ajout de la non-disponibilité.

Raison :

- Personnelle (cesse le calcul du délai d'attente)
- Médicale (ne cesse pas le calcul du délai d'attente)

Commentaire : tout commentaire pertinent à la non-disponibilité, idéalement une précision sur la raison.

**Lorsqu'il y a une « Non-disponibilité » active dans l'attente, il n'y a pas d'indicateur, donc il faut porter attention. En cochant la case** « **Période de non-disponibilité** » **dans la barre de recherche et en développant les éléments, il est possible d'afficher les différentes « Non-disponibilité »** 

**L'entrée des « Non-disponibilité » permet d'éviter les appels inutiles et diminue les usagers ayant une attente de rendez-vous hors délai.**

{6}------------------------------------------------

#### **1.6 Mécanisme d'accès et Communication**



### **1.6.1 Communication**

Circonstance obligatoire : si le résultat de la communication n'est pas un rendez-vous.

**Il est important d'utiliser cet onglet afin d'assurer une saine gestion des listes d'attente. Éviter l'utilisation du commentaire dans la section « Identification ».** 

**La communication permet la gestion des refus des rendez-vous. Les résultats des communications et des annulations alimentent l'onglet « Mécanisme d'accès ».**

**Les reports et les annulations sont gérer par la raison d'annulation ou de transfert des rendez-vous et s'inscrivent automatiquement lorsque l'attente est liée au rendez-vous.**

**Champs à compléter au besoin :**

- Mode : Méthode de communication

- Détails du résultat : Toutes informations pertinentes

- Commentaire : Toutes informations pertinentes

**Circonstance obligatoire : si le résultat de la communication n'est pas un rendez-vous. :**

- Objet (liste déroulante) : But de la communication

- Résultat (liste déroulante) : Ce qui en a découlé (certains résultats activeront le mécanisme d'accès<sup>1</sup> )

- Interlocuteur : À compléter si on ne parle pas à l'usager directement

- Nom de l'interlocuteur : Nom de la personne si on ne parle pas à l'usager directement

<sup>1</sup> Le mécanisme d'accès est la somme des règles émises par le Ministère de la santé et des services sociaux sur la gestion des listes d'attente, indique quand nous avons le droit de retirer des usagers de nos listes d'attente.

{7}------------------------------------------------

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
Tous 
Reports/refus 
Incapacités à joindre l'usager 
Absences

Seules les attentes ayant atteints le maximum permis sortiront sur la liste.

**L'algorithme sur la gestion des mécanismes d'accès est disponible dans l'intranet :**

<http://cissslaurentides.intranet.reg15.rtss.qc.ca/applications/eclinibase/documents-eclinibase/>

{8}------------------------------------------------

#### **7.3.5. Attentes (de l'usager)**

Dans les attentes (de l'usager), nous retrouvons toutes les attentes de l'usager sélectionné (ouvertes ou fermées). La restriction sur votre installation s'applique dans cette section.

Par défaut, vous ne verrez que les attentes qui sont actuellement actives. Pour consulter les attentes qui sont fermées, il vous suffit de descendre la barre de recherche et de cocher « Inclure les attentes fermées ».

Il est possible d'effectuer des recherches plus précises à l'aide des différents champs de la barre de recherche.

{15}------------------------------------------------

### **7.4.1. La gestion des attentes**

L'attente est le terme utilisé pour parler des requêtes des patients en attente de recevoir un service. Que ce soit pour une nouvelle prise en charge ou pour un suivi avec un professionnel. Tous les rendez-vous doivent partir d'une attente pour être fixés.

Pour consulter les attentes, aller dans l'onglet « Accueil/Prise en charge », choisir « Attente » et sélectionner « Gestion des attentes ».

- 1. Avant d'ouvrir une attente, vérifier si le patient n'en a pas déjà une d'ouverte pour ce service requis. Dans la barre de recherche, entrer le numéro de dossier de l'usager. Si vous ne connaissez pas son numéro de dossier. Appuyer sur les trois petits points ( ... ) et effectuer votre recherche selon le numéro de RAMQ et/ou date de naissance (selon les normes de saisies du CISSS des Laurentides en **annexe 2**).
- 2. Si l'usager n'a pas d'attente ou de dossier, vous pouvez en créer une en appuyant sur le "+" (en haut, à droite)

{18}------------------------------------------------

## **7.4.1.2.1. Information sur l'attente**

{19}------------------------------------------------

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

{20}------------------------------------------------

## **7.4.1.3.1. Fermeture de l'attente**

Les attentes sont fermées automatiquement lors de l'attribution du rendez-vous. Par contre, il est possible de fermer manuellement une attente en cas de besoin.

- Inscrire la date de fermeture
- Sélectionner la raison de fermeture selon la liste déroulante. Choisissez la raison la plus précise.
- Au besoin, ajouter une précision sur la raison (texte libre)

{21}------------------------------------------------

## **Non-disponibilité**

La non-disponibilité est une période d'au moins 7 jours où le patient n'est pas disponible pour venir à un rendez-vous, il n'est donc inutile de l'appeler pour lui en proposer un. La nondisponibilité est très importante dans le calcul des délais d'attente.

- Appuyer sur le "+" pour ajouter une non disponibilité
- Inscrire l'intervalle de date entre laquelle l'usager ne sera pas disponible
- Choisir entre une raison MÉDICALE ou PERSONNELLE
- Inscrire un commentaire qui explique la raison

Une non-disponibilité pour raison personnelle n'est pas une raison pour prioriser l'attribution d'un rendez-vous. En aucun cas.

{22}------------------------------------------------

#### **7.4.2. Mécanismes d'accès et communications**



#### **Mécanisme d'accès**

Le mécanisme d'accès est l'application de la circulaire ministérielle **Gestion active des listes d'attente afin d'améliorer l'accès aux médecins de famille ainsi qu'aux services médicaux et diagnostiques spécialisés** (2021-007) qui indique quand retirer un usager d'une liste d'attente (voir annexe 5).

C'est dans cet onglet que se compilent toutes les communications qui peuvent mener à une radiation de la liste d'attente.

Lorsque les communications sont entrées au bon endroit, il suffit de regarder l'onglet du mécanisme d'accès. S'il affiche une icône bleu avec un "i" dedans, c'est que le mécanisme d'accès est en cours, mais qu'il n'a pas atteint la radiation. S'il affiche un symbole similaire mais rouge, c'est qu'un maximum est atteint et que nous pouvons radier ce patient de notre liste d'attente. Nous devons avertir l'usager et le professionnel référent.

Il est possible de sortir la liste des usagers qui peuvent être radiés de la liste d'attente. Dans la barre de recherche, il suffit de cocher le ou les types de mécanisme d'accès selon le type de ménage que nous voulons effectuer.

Cette liste contient tous les usagers qui doivent être radiés de la liste d'attente. Il ne reste plus qu'à faire les vérifications, fermer l'attente et imprimer les lettres.

Il est possible d'ignorer certaines entrées, pour ce faire il faut aller dans l'onglet et cocher «Ignorer». Une précision peut être ajoutée afin d'indiquer pourquoi il ne faut pas considérer cette entrée. Cette option ne devrait être utiliser qu'en cas d'exception.

{23}------------------------------------------------

**Les reports et les annulations de rendez-vous s'ajoutent automatiquement à l'onglet mécanismes d'accès, à la condition que le rendez-vous ait été donné à partir d'une attente.**

Lors de la radiation, il faut imprimer les lettres requises et les envoyer au référent au à l'usager. Ces lettres se retrouveront dans l'onglet Communications.

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

{24}------------------------------------------------

### **8.1. Module « Gestion des attentes »**

- Ouvrez eClinibase.
- Ouvrez le module « Gestion des attentes ».

Prendre note qu'il y a différentes options de recherches afin d'être en mesure d'extraire les données que vous recherchez. Par exemple : intervenant, type d'intervenant, service requis, date de début, etc.

La barre de recherche se situe à gauche de l'écran et c'est à ce niveau que vous devrez entrer vos critères de recherche.

 Cochez la case « Inclure les attentes fermées » si vous désirez obtenir la liste des attentes ayant été fermées.

Cliquez sur le bouton « Rechercher ».

{67}------------------------------------------------

Assurez-vous de toujours rapporter tous les résultats. Pour ce faire, il suffit de cliquer sur le message indiquant qu'il y a d'autres résultats disponibles se trouvant au bas de l'écran.

 Déplacer, retirer ou ajouter des colonnes selon les besoins. Réfèrez-vous au document « trucs et astuces No3 » disponible sur la page intranet pour plus de précisions à cet effet.

[http://cissslaurentides.intranet.reg15.rtss.qc.ca/fileadmin/intranet/cisss\\_laurentides/A](http://cissslaurentides.intranet.reg15.rtss.qc.ca/fileadmin/intranet/cisss_laurentides/Applications/eClinibase/AIM_2022-06-20_T-A3_Liste_de_travail.pdf) [pplications/eClinibase/AIM\\_2022-06-20\\_T-A3\\_Liste\\_de\\_travail.pdf](http://cissslaurentides.intranet.reg15.rtss.qc.ca/fileadmin/intranet/cisss_laurentides/Applications/eClinibase/AIM_2022-06-20_T-A3_Liste_de_travail.pdf)

 Appliquer des filtres au niveau des colonnes en cliquant sur les symboles de flèches et d'entonnoir situées au niveau du titre de la colonne au besoin.

 Extraire le rapport en Excel en sélectionnant l'option « Afficher le menu d'exportation des grilles ».

Imprimer le rapport en sélectionnant l'icône de l'imprimante si nécessaire

{68}------------------------------------------------
