# Portfolio de Yann Kounkoud · BTS SIO SISR

Portfolio de Yann Kounkoud, étudiant en 2e année de BTS SIO option SISR à l'ESUP Puteaux (session 2027) : projets de l'épreuve E6, stages, tableau de synthèse de l'épreuve E5, compétences et veille technologique.

## Contenu du dépôt

- `index.html` : le site complet (HTML, CSS et JavaScript dans un seul fichier, sans dépendance). Thème clair ou sombre selon l'appareil, lisible sur mobile.
- `docs/` : documents liés depuis le site.

## Documents liés

Un intitulé de livrable devient un lien seulement si le fichier existe dans `docs/` sous le nom attendu. Sinon il reste en texte simple, sans lien cassé.

| Fichier | Document |
|---|---|
| `tableau-de-synthese.pdf` | Tableau de synthèse des réalisations professionnelles (E5) |
| `cv-yann-kounkoud.pdf` | CV |
| `negotech-contexte.pdf` | Projet NégoTech : contexte de l'organisation cliente |
| `negotech-plan-de-projet.pdf` | Projet NégoTech : plan de projet et checklist de l'annexe II.E |
| `negotech-captures.pdf` | Projet NégoTech : captures Proxmox et pfSense |
| `salle-formation-methodologie.pdf` | Salle de formation virtuelle : méthodologie de conduite de projet |
| `services-schema.pdf` | Infrastructure de services : schéma réseau |
| `techbuild-doc-vmware.pdf` | Stage TechBuild SAS : documentation technique VMware Workstation |
| `techbuild-diaporama-vmware.pdf` | Stage TechBuild SAS : diaporama de la procédure |
| `ad-esn-diaporama.pdf` | Active Directory esn.local : diaporama |
| `ad-evolutions.pdf` | Active Directory : script de conformité et captures FGPP |
| `itw-rapport-de-stage.pdf` | Rapport de stage ITW Automotive |
| `vlan-stratadvise.pkt` | Réseau StratAdvise : fichier Cisco Packet Tracer |
| `vlan-diaporama.pdf` | Réseau StratAdvise : diaporama |
| `attestation-secnumacademie.pdf` | Attestation SecNumacadémie (ANSSI) |

Avant d'ajouter un document, retirer les informations internes aux entreprises (adresses IP, noms de collègues) ainsi que tout identifiant ou mot de passe.

## Publication

Le site est publié avec GitHub Pages depuis la branche `main`, dossier racine (Settings → Pages → Deploy from a branch).

## Mise à jour

- Chaque réalisation est un bloc `<article class="rea">` dans `index.html`. Son attribut `data-cat` (`e6`, `pro` ou `formation`) règle le filtre de la page.
- Le tableau de synthèse du site (section `id="synthese"`) doit rester identique au tableau officiel. Après un ajout, mettre à jour la ligne « Réalisations par compétence » et réexporter `docs/tableau-de-synthese.pdf`.
