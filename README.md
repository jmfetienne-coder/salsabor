# SALSABOR — Programmation annuelle des cours de danse

Application web pour préparer, suivre et imprimer la programmation annuelle
d'un cours de danse : **40 semaines réparties sur 10 mois**, de septembre à juin.

**→ [Ouvrir l'application](https://jmfetienne-coder.github.io/salsabor/)**

## Ce qu'elle fait

| Onglet | À quoi il sert |
|---|---|
| **Tableau de bord** | Avancement de la fiche, progression mois par mois, prochaine séance. |
| **Grille annuelle** | La fiche complète : 10 mois × 4 semaines × 9 champs. |
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

## Hors ligne

L'application tient dans une seule page. Enregistrez-la
(**Fichier → Enregistrer sous…**) et elle fonctionnera par double-clic, sans
connexion.

## Impression et PDF

Grille annuelle en A3 paysage — 2 pages, ou 1 page réduite ; fiche de séance en
A4 portrait.

L'onglet **Séance** porte un bouton **Exporter en PDF** : il ouvre la fenêtre
d'impression, où il faut choisir **« Enregistrer au format PDF »**. Le PDF
obtenu est vectoriel, son texte reste sélectionnable.

---

*Conception et contenu pédagogique : Jean-Michel Etienne. Toutes les vues
portent la mention « version JM ETIENNE ».*
