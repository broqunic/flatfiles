---
layout: cours
nom: Cours 7 Dossier de données, YML et JSON
---

## Data

Il est possible d'importer ses propres données sur un site et les afficher à partir d'un tableau **YML** ou **JSON**.

Ici on s'en sert pour des membres et des clubs de football, l'avantage est de ne pas utiliser de bases de données.

- Création du dossier _data qui contient les fichiers de données
- Création d'une page membre, à travers un tableau Json, lecture des informations du tableau, et affichage selon la norme :
**nomTableau.attribut**
*ex: member.nom*

#### Assignations

- Assignation équipe de football à l'équipe de football d'un membre
```
{% assign footballteam = {{membre.footballteam}} %}
```

- Assignation club et valeur tableau ligue, avec condition WHERE : key, footballteam

### Remarques
Le dièse permet le commentaire en YML.

Attention à modifier les URL entre la version locale et la version en ligne, sinon problèmes pour les liens de pages et d'images notament.
