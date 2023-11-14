# RCN-DesignSystem
 
Un jeton de conception (design token en anglais) est une référence unique qui stocke un ou plusieurs attributs visuels liés aux interfaces utilisateurs. Ces jetons sont préférés aux valeurs brutes pour des questions d’évolutivité, de maintenance et de cohérence entre les différents services applicatifs AIFE.

Respecter le RCN implique l’utilisation de ces property tokens.

La fiche design tokens sera complétée prochainement. En cas de difficulté dans l’utilisation de ces tokens veuillez contacter l’Equipe UX et Qualité.


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


## Roadmap

| Lot       | Status  | Versions   | Description                |
| :-------- | :------- | :------------------------- | :------------------------- |
| Lot 1     | [Static Badge](https://img.shields.io/badge/Done-8acdb0.svg) | [Static Badge](https://img.shields.io/badge/v0.1.0+-grey.svg)  | **Composants :** backtotop / breadcrumb / Button / captcha / card / chips / Header / Icon / Link / loader / Modal / notification / tooltip / typography |
| Lot 2     | [Static Badge](https://img.shields.io/badge/Done-8acdb0.svg) | [Static Badge](https://img.shields.io/badge/v0.2.3+-grey.svg)  | **Composants :** Accordions / Footer / Tabs |
| Lot 3     | [Static Badge](https://img.shields.io/badge/Done-8acdb0.svg) | [Static Badge](https://img.shields.io/badge/v0.3.1+-grey.svg)  | **Composants :** FormInputs |
| Lot 4     | [Static Badge](https://img.shields.io/badge/Done-8acdb0.svg) | [Static Badge](https://img.shields.io/badge/v0.4.2+-grey.svg)  | **Composants :** Menu / Pagination / Stepper |
| Lot 5     | [Static Badge](https://img.shields.io/badge/Done-8acdb0.svg) | [Static Badge](https://img.shields.io/badge/v0.5.1+-grey.svg)  | **Composants :** ConnexionModule / FooterLanguageAndVersionBanner / formTemplate |
| Lot 6     | [Static Badge](https://img.shields.io/badge/Pending-abb8df.svg) |   | **Composants :** DataTable |
