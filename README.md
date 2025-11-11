# eClinibase — Site GitHub Pages (optimisé Copilote)

## Structure
- `/index.md` — Sommaire
- `/attentes.md` — Attentes (Identification, Détail, Prérequis, Non-disponibilité, Communication, Mécanisme d’accès, Réouverture)
- `/rendezvous.md` — Rendez-vous (recherche de dispo, fixation/transfert, présence/confirmation/annulation, Page intervenant, Agenda, eRendez-vous/horaires)
- `/normes-saisie.md` — Normes de saisie (incluant priorités médicales)
- `/procedures.md` — Procédures générales + **Texte intégral (verbatim)** à la fin

## Publication
1) Copiez **tous les fichiers** à la racine de votre repo GitHub Pages.
2) GitHub → Settings → Pages → Source = `main` (ou `docs/`) ; Build & deploy = `Pages`.
3) Vos 4 URLs à déclarer dans Copilote :
   - `/attentes/`
   - `/rendezvous/`
   - `/normes-saisie/`
   - `/procedures/`

## Notes
- **Aucune donnée supprimée** : tout le contenu source est routé par thème et reproduit **intégralement** en fin de `/procedures/`.
- Titres conservés ; pas d’accordéons JS ; texte clair pour l’indexation LLM.
