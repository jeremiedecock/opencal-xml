# OpenCAL XML schemas

## DTD

Vérifier la syntaxe du fichier XML :

```
xmllint --noout fichier.xml
```

Vérifier la validité selon la DTD :

```
xmllint --noout --valid fichier.xml
```

Remarque: `--noout` permet de n'afficher que les erreurs.

## XML Schema

Vérifier la validité selon le Schema :

```
xmllint --noout --schema fichier.xsd fichier.xml
```

Remarque: `--noout` permet de n'afficher que les erreurs.
