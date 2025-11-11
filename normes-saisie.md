---
title: "Normes de saisie — eClinibase"
permalink: /normes-saisie/
layout: default
description: "Normes de saisie du CISSS des Laurentides : règles de qualité des données, formats et priorités médicales."
tags: ["eClinibase","Normes de saisie","Qualité des données","Priorité médicale"]
---


> **Périmètre** : Cette page reflète strictement la marche à suivre eClinibase du CISSS des Laurentides.
> Ne pas extrapoler : si une info manque, se référer à **/procedures/** (verbatim) ou aux **pilotes eClinibase**.

# Normes de saisie — CISSS des Laurentides

## Sommaire rapide
- Recherches avant création (NAM / Nom+DDN+Sexe / Mère+DDN+Sexe)
- NAM (validité, **jamais** de NAM temporaire)
- Nouveau-né (nom/prénom, absence de NAM)
- Adresse (formats, abréviations, particularités)
- DDN **inconnue** (valeur de repli)
- Noms/alias (ce qu’on saisit / ne saisit pas)

> **Valeurs de repli clés**
> - **DDN inconnue** : `1899-12-30`  
> - **Nouveau-né** : *Nom de famille de la mère* ; Prénom : *BB de <prénom mère>* (ou **BB1/BB2**… pour multiples)



NORMES DE SAISIE du CISSS des Laurentides - CRÉATION ET MODIFICATION DE DOSSIER

# Avant de créer un dossier, vous devez obligatoirement effectuer MINIMALEMENT 2 RECHERCHES :

Recherche n° 1: NAM

Recherche n° 2: Nom - date de naissance (DDN) - sexe Recherche n° 3: Nom de famille de la mère - DDN - sexe

# Pour les enfants de moins d'un (1) an (qui n'a pas encore de NAM)

Recherche n° 1 : Nom de la mère - BB de (prénom de la mère)

Recherche n° 2: DDN - sexe

#### NAM + DATE D'EXPIRATION

Inscrire la date d'expiration du NAM conformément à la carte d'assurance maladie. Si l'expiration est inconnue, inscrire l'année courante + le mois de naissance de l'usager

Ne pas effacer le NAM déjà inscrit si l'usager ne peut pas présenter sa carte.

Ne jamais inscrire un NAM temporaire. On reconnait un NAM temporaire si celui-ci contient le caractère « M » dans l'avant dernière position.

Ex: BERC980401M2

#### NOUVEAU-NÉ

<u>Ne pas inscrire le NAM de la mère ou du père</u> dans le dossier du nouveau-né. Sélectionner la raison d'absence du NAM : *Usager âgé de moins d'un (1) an*.

Les encadrés à fond vert représentent les données obligatoires à saisir

Document inspiré des Normes de saisie provinciale du CIUSSS du Nord-de-l'île-de-Montréal

# **ATTENTION NE JAMAIS** RÉUTILISER UN NUMÉRO DE DOSSIER

Carte d'assurance maladie du Québec

#### **EXIGEZ-LA!**

L'usager doit présenter sa carte valide à chaque visite!

Si l'usager n'a pas de carte RAMQ, il faut demander une pièce étatique pour confirmer son identité.

Choisir l'exception au numéro d'assurance maladie (NAM) qui correspond à la situation.

Pour MédiPatient, laisser le champ vide.

#### SI LA CARTE RAMQ CONTIENT UNE ERREUR:

→ C'est à l'usager de faire la demande de changement auprès de la RAMQ au 1-800-561-9749.

Dès que la <u>modification</u> à la RAMQ est <u>effectuée</u>, un avis de notification est publié aux établissements par le Registre des Usagers (RU).

#### NOUVEAU-NÉ

Cette norme de saisie s'applique aux nouveau-nés et aux usagers de moins d'un an, nés au Québec, n'ayant pas reçu leur carte RAMQ. Vous devez suivre la norme de saisie ci-dessous même si l'information sur la SP-1 diffère.

Nom du bébé -> Inscrire le nom de famille de la mère.

#### Prénom du bébé

- Naissance unique → Inscrire BB de « prénom de la mère »
   Ex : BB de Hélène
- Naissances multiples → inscrire BB1 de « prénom de la mère », BB2 de « prénom de la mère ». Ex : BB1 de Hélène, BB2 de Hélène, BB3 de Hélène, etc.

IMPORTANT II ne doit pas y avoir d'espace entre BB et le chiffre qui détermine l'ordre de naissance.

#### NUMÉRO D'ASSURANCE SOCIALE

Il est interdit d'entrer le NAS dans un Index

#### DATE DE NAISSANCE (AAAA-MM-JJ)

Écrire la date de naissance conforme à la carte d'assurance maladie.

DDN inconnue: Lorsque la DDN est inconnue, inscrire 1899-12-30

#### NOM / PRÉNOM USAGER

- Inscrire le nom de l'usager conformément à la carte d'assurance maladie ou autre pièce étatique en l'absence de la carte d'assurance maladie.
- Lorsque le nom de l'usager inscrit sur la carte d'assurance maladie est abrégé dû à la longueur du nom, inscrire le nom au complet tel que déclaré par l'usager.
- Si plusieurs noms/prénoms apparaissent sur la carte d'assurance maladie ou autre document officiel/pièce étatique, inscrire tous les noms et prénoms.
- Ne pas inscrire le nom usuel, préféré ou fictif de l'usager.
- Inconnu: Inscrire [Inconnu] lorsque l'usager est incapable ou refuse de s'identifier.
- Lorsque sur la carte de la RAMQ c'est le nom marital qui figure et qui compose le NAM, utiliser ce nom.

#### MÈRE/PÈRE (NOM ET PRÉNOM)

N.B. Inscrire le nom à la naissance de la mère (ne pas utiliser le nom de femme mariée)

Inconnu → Lorsque l'usager est inconscient ou incapable de donner l'information, inscrire « inconnu » dans le [nom/prénom de la mère et/ou du père].

Signifie que l'information doit être revalidée lors de la prochaine visite.

Non déclaré → Lorsque l'usager ne veut pas déclarer le nom/prénom de sa mère et/ou de son père ou s'il ne connaît pas ces noms/prénoms, inscrire [Non déclaré].

Signifie que l'on ne doit pas redemander l'information à l'usager.

{73}------------------------------------------------

# POSER LES QUESTIONS À L'USAGER AU LIEU DE SUGGÉRER LES RÉPONSES!

Dites: « Quelle est votre adresse? » Plutôt que: « Habitez-vous au XYZ? »

<u>Toujours</u> effectuer cette vérification, <u>à chaque visite et à chaque appel</u>, même si l'usager est venu à votre centre récemment.

#### ADRESSE PERMANENTE

#### Deux façons d'inscrire l'adresse :

Si le système d'information (SI) possède un champ «appartement», compléter les champs tel que demandé. Utiliser ce format pour le champ «Adresse» :

#### No Civique + Type + Nom de rue

Ex: 12 rue des Érables Est

Si le SI ne possède pas de champ «appartement», inscrire le numéro

d'appartement à la fin de l'adresse comme suit :

No Civique + Type + Nom de rue + # + App. (Ne pas inscrire d'espace entre le # et le numéro d'appartement)

Ex: 12 rue des Érables Est #3

#### Si le nom de la rue est un chiffre

Inscrire le No civique, faire un espace, inscrire le chiffre suivi de la lettre «e» et du nom «Rue» ou «Avenue».

Ex: 12 2e Avenue

#### Nord, Sud, Est, Ouest

À inscrire après le nom de la rue.

Si une abréviation est requise utiliser N - S - E - O

#### ABRÉVIATIONS

Avenue : AV Boulevard : BOUL

Carré : CARRE Casier postal : CP Chemin : CH

Croissant : CROIS Drive : DR Ième / ière : E

Côte: COTE

Impasse : IMP Montée : MTEE Place : PL

Promenade: PROM Rang: RG

Route: RTE
Route rurale: RR
Square: SQ
Terrasse: TSSE

#### PARTICULARITÉ DE SAISIE POUR L'ADRESSE PERMANENTE

Inscrire dans le champ Adresse permanente pour les usagers suivants :

Étudiant : Adresse du logement occupé actuellement (pour les résidents au Québec seulement).

**Étudiant étranger :** Adresse permanente (hors Québec).

Travailleur saisonnier: Adresse du logement occupé actuellement

Immigrant non résident du Québec : Adresse du logement occupé actuellement Itinérant / sans adresse fixe : Adresse de l'installation qui donne le service

Enfant en garde partagée : Adresse de l'un des parents Usager en centre de détention : Adresse du centre de détention

En logement saisonnier (chalet): Adresse de la résidence permanente Milieu de vie : Adresse du milieu de vie

Plusieurs adresses permanentes : Adresse permanente actuelle

Touriste: Adresse permanente

Adresse de l'usager inconnue : Adresse de l'installation qui donne le service

N.B. L'adresse au Québec des étudiants étrangers et des touristes doit être saisie dans le champ « Adresse temporaire ». Pour les systèmes n'ayant pas de champ « Adresse temporaire », nous vous suggérons d'inscrire l'adresse temporaire au Québec dans le champ « Renseignements supplémentaires » des formulaires (AH-280 et AH-101P) pour tous les non-résidents.

#### **AUTRE NOM DE FAMILLE (ALIAS) AUTRE PRÉNOM (ALIAS)**

- · Inscrire tout autre nom ou prénom usuel, préféré ou fictif.
- Si la carte RAMQ est au nom de femme mariée, inscrire le nom à la naissance dans ce champ.
- · Inscrire le nom de femme mariée si utilisé par l'usager mais non présent sur la carte RAMQ.

### MODIFICATIONS

Pour toutes questions relatives aux modifications d'un dossier existant, ex. : adoption, changement majeur (nom, prénom, parents, date de naissance, sexe),

veuillez communiquer avec le service des archives médicales de votre installation.

#### Décès

Si vous apprenez le décès d'un usager et que cette information n'est pas présente à son dossier, il faut en aviser une archiviste.

Elle aura besoin des informations suivantes :

- Numéro de dossier de l'usager
- Nom et prénom
- Date du décès
- Nom de la personne donnant l'information
  - o Son lien avec l'usager
  - Son numéro de téléphone

Il est important de fermer les attentes et d'annuler les rendez-vous futur avec la raison : Décès
