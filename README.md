# sorties-calendrier

Fichiers **.ics** « Ajouter au calendrier » pour des idées de sorties à Québec (spectacles, visites, marchés, expos…).

Chaque suggestion d'un courriel hebdomadaire a son propre fichier : un clic, et l'événement s'ajoute à Calendrier (Apple, Google, Outlook).

Publié avec GitHub Pages : https://lucrousseau.github.io/sorties-calendrier/

## Contenu

```
ics/
└── 2026/
    ├── nuit-des-clochers-quebec-2026.ics
    ├── harry-manx-palais-montcalm-2026-11-13.ics
    └── …
```

- Un fichier par événement : `ics/AAAA/<id>.ics`.
- Un événement : titre (« Catégorie – Nom »), date et heure (fuseau America/Toronto), lieu avec adresse, lien vers la page officielle, courte description et prix.
- Rien d'autre. Pas de code, pas de données, pas d'historique de préférences.

## Ce dépôt est public

Tout ce qui s'y trouve est lisible par n'importe qui, y compris dans l'historique git. On n'y met donc **que des informations publiques sur des activités** :

- aucun nom de personne, aucune adresse courriel, aucun numéro de téléphone personnel ;
- aucune adresse domicile, aucun trajet, aucune habitude ou préférence ;
- aucune note personnelle, aucun lien vers un calendrier, une mémoire ou un compte privé ;
- aucun jeton, mot de passe ni identifiant.

Les fichiers sont générés par un script qui refuse les contenus suspects (adresses courriel, noms de personnes). Un fichier publié par erreur se retire par un nouveau commit, mais il reste dans l'historique : il faut alors le signaler et nettoyer l'historique.

## Mise à jour

Automatique, une fois par semaine : les nouveaux fichiers s'ajoutent, les anciens restent en place pour que les liens des courriels précédents continuent de fonctionner.

## Licence

Les descriptions viennent des pages publiques des organisateurs ; les droits restent aux organisateurs.
