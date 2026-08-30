# SALSABOR — Programmation annuelle des cours de danse

Application web pour préparer, suivre et imprimer la programmation annuelle
d'un cours de danse : **40 semaines réparties sur 10 mois**, de septembre à juin.

**→ [Ouvrir l'application](https://jmfetienne-coder.github.io/salsabor/)**

## Ce qu'elle fait

| Onglet | À quoi il sert |
|---|---|
| **Tableau de bord** | Avancement de la fiche, progression mois par mois, prochaine séance. |
| **Grille annuelle** | La fiche complète : 10 mois × 4 semaines × 9 champs. Export PDF A3, Excel, CSV. |
| **Séance** | La fiche d'un cours, à imprimer ou exporter en PDF A4 pour l'emporter en salle. |
| **Calendrier** | Date les 40 séances à partir de la rentrée, vacances déduites. Export `.ics`. |
| **Référentiel** | Objectifs, supports chorégraphiques et outils pédagogiques, éditables. |
| **Notice** | Mode d'emploi. |

## Le modèle pédagogique

Neuf champs par semaine :

- **F1 Musicalité, F2 Appuis, F3 Connexion, F4 Respiration** — les quatre
  fondamentaux techniques, objectifs **cachés**, à usage du professeur ;
- **F5 Support chorégraphique** — objectif **affiché** aux élèves ;
- **Outils 1 / 2 / 3** — outils pédagogiques unitaires ;
- **Réalisé + commentaires** — à compléter après le cours.

**S1 à S3** sont des semaines d'acquisition, **S4** une semaine de révision.
Le référentiel livré couvre le Mambo en couple, cycle Débutant ; les autres
disciplines sont utilisables en complétant les tables depuis l'onglet
**Référentiel**.

## Vos données vous appartiennent

Aucun compte, aucun serveur : les fiches sont enregistrées **dans votre
navigateur**, sur votre poste. Elles ne sont envoyées nulle part et ne sont
visibles de personne d'autre.

Conséquence : changer de navigateur ou de poste ne transporte pas vos fiches,
et vider les données de navigation les efface. Utilisez le bouton
**Sauvegarder** pour écrire un fichier `.json`, et **Restaurer** pour le
relire ailleurs.

## Sur téléphone

La même adresse fonctionne sur téléphone : la page s'adapte à l'écran, il n'y a
rien d'autre à installer.

La **grille annuelle** s'y consulte **un mois à la fois** en portrait, **deux ou
trois** en paysage, choisis dans un sélecteur en haut de l'écran — dix mois côte
à côte seraient illisibles. Les exports, eux, restent complets : le PDF sort
bien l'année entière.

En paysage, les actions moins courantes se replient derrière le bouton **⋯**
pour laisser la place au contenu ; rien n'est perdu.

Pour l'avoir sous la main comme une application, dans Safari :
**Partager → Sur l'écran d'accueil**. Elle s'ouvre alors en plein écran, avec
son icône, et retrouve vos fiches.

## Hors ligne

L'application tient dans une seule page. Enregistrez-la
(**Fichier → Enregistrer sous…**) et elle fonctionnera par double-clic, sans
connexion.

## Impression et PDF

Deux boutons **Exporter en PDF** :

| Onglet | Bouton | Résultat |
|---|---|---|
| **Grille annuelle** | Exporter en PDF (A3) | la fiche de programmation annuelle, A3 paysage |
| **Séance** | Exporter en PDF | la fiche d'un cours, A4 portrait, une page |

Tous deux ouvrent la fenêtre d'impression, où il faut choisir
**« Enregistrer au format PDF »** — menu *Destination* dans Chrome, menu *PDF*
en bas à gauche dans Safari. Le PDF obtenu est vectoriel : son texte reste
sélectionnable et recherchable.

Pour la grille, un sélecteur voisin propose trois mises en page :

- **2 pages, coupure au changement de niveau** *(défaut)* — Sept.–Déc. puis
  Janv.–Juin, de façon qu'un sous-niveau ne soit jamais coupé en deux ;
- **2 pages, 5 mois par page** — Sept.–Janv. puis Févr.–Juin ;
- **1 page** — les dix mois, texte plus petit.

### Trois réglages qui changent tout

- **Papier A3 paysage** pour la grille. La page le demande d'elle-même, mais un
  réglage manuel resté sur A4 prendrait le dessus.
- **Marges par défaut.** Des marges élargies font déborder la grille sur une
  page de plus.
- **Impression des arrière-plans**, si votre navigateur ne les affiche pas dans
  l'aperçu : « Graphiques d'arrière-plan » dans Chrome, « Imprimer les
  arrière-plans » dans Safari. Sans quoi le code couleur disparaît.

---

*Conception et contenu pédagogique : Jean-Michel Etienne. Toutes les vues
portent la mention « version JM ETIENNE ».*
