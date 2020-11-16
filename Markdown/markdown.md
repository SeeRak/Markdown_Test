# Tuto Markdown

Le Markdown est un langage de balisage (comme le html). Sa structure est très légère

## Les titres

Avec un # vous pouvez indiquer des titres de différentes niveaux (comme h1, h2..)
# Titre de niveaux 1 
## Titre de niveau 2

## Les listes

On peut faire des listes de plusieurs niveaux :

### Liste de course:
- tomates
    3-normales
    une barquette de tomates cerise
- mozzarella
- parmesan
- huile d'olive

    - tomates
        3-normales
        une barquette de tomates cerise
    - mozzarella
    - parmesan
    - huile d'olive 

## Les liens

Pour créer un lien on utilise les crochets [] pour y mettre notre texte
et les parenthèses pour indiquer le lien vers lequel il redirige :

[lien vers github](https://github.com)
    [lien vers github](https://github.com)

## Les images

On peut rajouter des images!
![alt-texte](lien)

## Les tableaux

|En-tête de colonne 1| En-tête de colonne 2|
|--------------------|---------------------|
|element colonne 1 ligne 1 | element colonne 2 ligne 1|
|element colonne 1 ligne 2 | element colonne 2 ligne 2|
|element colonne 1 ligne 3 | element colonne 2 ligne 3|

    |En-tête de colonne 1| En-tête de colonne 2|
    |--------------------|---------------------|
    |element colonne 1 ligne 1 | element colonne 2 ligne 1|
    |element colonne 1 ligne 2 | element colonne 2 ligne 2|
    |element colonne 1 ligne 3 | element colonne 2 ligne 3|

## Les éléments de texte

On peut mettre des éléments de texte en *italique*

    On peut mettre des éléments en *italique*

Ou en gras **gras**

    Ou en gras **gras**

Il est possible d'insérer des lignes de code entre 3 backticks (``) ou avec des tabulations

```html
    code html..
```

Le mardown n'interprète pas le retour à la ligne comme les autres langages:
On peut faire 
des 
retour
à la ligne
avec 
2 espaces