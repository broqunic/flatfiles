## Structure

* flatfiles
  * index.html
  * _config.yml
* _layouts
  * default.html
  
index -> page d'accueil.

config -> variables globales.

_layouts -> dossier des fichiers du template.

dafault.html -> template de base, n'y placer que les éléments de base, communs à toutes les pages.

---

## Élements

Dans index.html, placer "layout: default" dans l'en-tête du fichier, entre les tirets.

Dans le default.html, appeler le contenu par {{content}}.

Création de 3 éléments, head.html / header.html / footer.html.

-> Ces fichiers seront appeler dans le template default.html, il d'ailleurs possible de séparer d'autres éléments dans d'autres fichiers distinces, comme le menu dans un fichier nav.html, que l'on peut appeler ainsi dans le head.html.


#### détails

Il faut recharger le jekyll serve en cas de modification du fichier _config.yml.
