# sorties-calendrier

Fichiers iCalendar (`.ics`) pour ajouter des sorties à Québec (spectacles, visites, marchés, expos) à un calendrier en un clic. Un fichier par événement, publié avec GitHub Pages : https://lucrousseau.github.io/sorties-calendrier/

## Structure

```
ics/<année>/<id>.ics
```

Chaque fichier décrit un seul événement : titre, date et heure (America/Toronto), lieu et adresse, lien vers la page officielle, courte description et prix. Les fichiers déjà publiés ne sont pas supprimés, pour que les liens existants restent valides.

## Génération

Les fichiers sont produits automatiquement par un script qui valide les liens et refuse tout contenu personnel (adresses courriel, noms). Ils ne contiennent que de l'information publique sur des activités.

## Licence

Les descriptions proviennent des pages publiques des organisateurs, dont les droits leur appartiennent.
