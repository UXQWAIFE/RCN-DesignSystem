# RCN-DesignSystem
 
Un jeton de conception (design token en anglais) est une référence unique qui stocke un ou plusieurs attributs visuels liés aux interfaces utilisateurs. Ces jetons sont préférés aux valeurs brutes pour des questions d’évolutivité, de maintenance et de cohérence entre les différents services applicatifs AIFE.

Respecter le RCN implique l’utilisation de ces property tokens.

La fiche design tokens sera complétée prochainement. En cas de difficulté dans l’utilisation de ces tokens veuillez contacter l’Equipe UX et Qualité.

## Roadmap

- Additional browser support ![Static Badge](https://img.shields.io/badge/Done-v0.1.0+-green.svg)
- Add more integrations


## Utilisation 

Pour utiliser ces fichiers, vous n'avez pas besoin d'appeler chaque élément un à un. 

Il faut pour ça savoir sous quelle marque produit vous êtes : Chorus / Chorus Pro / Piste / Qualification

Ensuite il vous suffit de télécharger ce repo et de l'installer directement dans vos fichiers et ensuite d'intégrer dans la balise <head> la bonne ligne suivant votre marque produit : 

#### Chorus

```html
<link rel="stylesheet" href="RCN-DesignSystem/assets/styles-Chorus.css"><!--CSS-->
<!-- OR -->
<link rel="stylesheet" href="RCN-DesignSystem/assets/styles-Chorus.css"><!--SCSS-->
```

#### Chorus Pro

```html
<link rel="stylesheet" href="RCN-DesignSystem/assets/styles-ChorusPro.css"><!--CSS-->
<!-- OR -->
<link rel="stylesheet" href="RCN-DesignSystem/assets/styles-ChorusPro.css"><!--SCSS-->
```

#### Piste

```html
<link rel="stylesheet" href="RCN-DesignSystem/assets/styles-Piste.css"><!--CSS-->
<!-- OR -->
<link rel="stylesheet" href="RCN-DesignSystem/assets/styles-Piste.css"><!--SCSS-->
```

#### Qualification

```html
<link rel="stylesheet" href="RCN-DesignSystem/assets/styles-Qualification.css"><!--CSS-->
<!-- OR -->
<link rel="stylesheet" href="RCN-DesignSystem/assets/styles-Qualification.css"><!--SCSS-->
```