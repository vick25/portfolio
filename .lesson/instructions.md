# 0. Copier le code du dernier projet
- `index.html`
- `cv.html`
- `contact.html`
- `style.css`

- Ajouter à la balise `head` de toutes les pages ces deux balises : 
  -  `<meta name="viewport"
      content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">`
  - `<meta http-equiv="X-UA-Compatible" content="ie=edge">`
    
Afin optimiser la manière dont une page web est affichée sur les appareils mobiles et s'assurer qu'elle est compatible avec les différentes versions d'Internet Explorer.


# 1. La page d'accueil 

![capture](/images/capture-home-page-mobile.png)
![capture](/images/capture-home-page-tablete.png)
![capture](/images/capture-home-page-desktop.png)



## Le header 

### Dans le fichier style.css 

- Sélectionnez la classe `.gap-m`
  - Donnez la valeur `30px` à la propriété `gap` de la classe `.gap-m`
    
- Sélectionnez la classe `.gap-s`
  - Donnez la valeur `16px` à la propriété `gap` de la classe `.gap-s`

- Sélectionnez la classe `.pl-0`
  - Donnez la valeur `0` à la propriété `padding-left` de la classe `.pl-0`


- Ajouter une règle @media query qui va s'appliquer aux écrans d'une largeur minimal de `520px` (sm).

```css
/* sm */
@media screen and (min-width: 520px) {

}
```

- Sélectionnez la classe `.sm-flex-row` dans la règle @media query que nous venons de créer 
  - Donnez la valeur `row` à la propriété `flex-direction` de la classe `.sm-flex-row`

- Sélectionnez la classe `.sm-flex-justify-space-between` dans la règle @media query que nous venons de créer
  - Donnez la valeur `space-between` à la propriété `justify-content` de la classe `.sm-flex-justify-space-between`


### Dans le fichier index.html

- Ajoutez la classe `.text-center` à la balise `<nav>`
- Ajoutez la classe `.flex-column` à la balise `<nav>`
- Ajoutez la classe `.gap-m` à la balise `<nav>`

- Ajoutez la classe `.sm-flex-row` à la classe `<nav>`
- Ajoutez la classe `.sm-flex-justify-space-between` à la classe `<nav>`

La balise `<nav>` doit avoir les classes suivantes `text-center flex-column gap-m flex flex-justify-space-between flex-wrap padding-y-s sm-flex-row sm-flex-justify-space-between`


- Ajoutez les classes `pl-0  flex-align-center flex-justify-center` à la balise `<ul>` contenu dans la deuxième balise `<div>` dans la balise `<nav>`



## Le Footer 

### Dans le fichier style.css 

- Ajouter une règle @media query qui va s'appliquer aux écrans d'une largeur minimal de `640px` (md).

```css
/* md */
@media screen and (min-width: 640px) {

}
```

- Sélectionnez la classe `.md-flex` dans la règle @media query que nous venons de créer
  - Donnez la valeur `flex` de la classe à la propriété `display` de la classe `.md-flex`

- Sélectionnez la classe `.md-flex-row` dans la règle @media query que nous venons de créer
  - Donnez la valeur `row` de la classe à la propriété `flex-direction`

- Sélectionnez la classe `.md-flex-justify-center` dans la règle @media query que nous venons de créer
  - Donnez la valeur `center` à la propriété `justify-content` de la classe `.md-flex-justify-center`

- Sélectionnez la classe `.md-gap-l` dans la règle @media query que nous venons de créer
  - Donnez la valeur `40px` à la propriété `justify-content` de la classe `.md-gap-l`




- Sélectionnez la classe `.md-text-left` dans la règle @media query que nous venons de créer
  - Donnez la valeur `left` de la classe à la propriété `text-align` de la classe `.md-text-left`

- Sélectionnez la classe `.md-gap-0` dans la règle @media query que nous venons de créer
  - Donnez la valeur `0` de la classe a la propriété `gap` de la classe `md-gap-0`


### Dans le fichier index.html 

- Ajouter les classes `text-center flex-column gap-m md-flex md-flex-row md-text-left md-gap-0` à la balise `<footer>`

- La balise `<footer>` doit avoir les classes suivantes `flex flex-justify-space-between top-bordered padding-y-s text-center flex-column gap-m md-flex md-flex-row md-text-left md-gap-0`



## La balise main 


### Dans le fichier style.css  


- Modifiez le style appliqué à la classe `.button`
  - Changer la largeur (qui était à `100px`) à `80px` en donnant la valeur `80px` à la propriété `width` de la classe `.button`
  - Changer la hauteur minimale  (qui était à `100px`) à `80px` en donnant la valeur `80px` à la propriété `min-height` de la classe `.button`

- Ajouter une règle @media query qui va s'appliquer aux écrans d'une largeur minimale de `950px` (md).

```css
/* lg */
@media screen and (min-width: 950px) {

}
```
- Séctionnez la classe `.button`
  - donnez la valuer `100px` à propriété `width` de la classe `.button`
  - donnez la valuer `100px` à propriété `min-height` de la classe `.button`

- Sélectionnez la classe `.lg-flex-row` dans la règle @media query que nous venons de créer
  - Donnez la valuer `row` de la classe à la propriété `flex-direction` de la classe `.lg-flex-row`
  
- Sélectionnez la classe `.lg-text-left` dans la règle @media query que nous venons de créer
  - Donnez la valuer `left` de la classe à la propriété `text-align` de la classe `.lg-text-left`

- Sélectionnez la classe `.lg-flex-justify-start` dans la règle @media query que nous venons de créer
  - Donnez la valuer `flex-start` de la classe a la proprieté `justify-content` de la classe `.lg-flex-justify-start`



- Ajouter une règle @media query qui va s'appliquer aux écrans d'une largeur minimale de `320px` (md).

```css
/* xs */
@media screen and (min-width: 320px) {

}
```

- Sélectionnez la classe `.xs-flex-row` dans la règle @media query que nous venons de créer
  - Donnez la valeur `row` de la classe à la propriété `flex-direction` de la classe `.xs-flex-row
 


### Dans le fichier index.html 

**La balise `<main>`**

- Retierez la classe `.flex-wrap` de la balise `<main>`
- Ajoutez la classe `.flex-column` à la balise `<main>`
- Ajouter la classe `.text-center` à la balise `<main>`

La balise `<main>` doit avoir les classes suivantes `padding-y-xxl flex flex-column flex-justify-center flex-align-center gap-xl text-center lg-text-left lg-flex-row`

**Premiere balise `<div>` de la deuxieme balise `<div>` de la balise `<main>`**

- Retirer la classe `.flex-wrap` de première balise `<div>` de la deuxième balise `<div>` de la balise `<main>` 
- Retirer la classe `.gap-xl` de première balise `<div>` de la deuxième balise `<div>` de la balise `<main>`


- Ajouter la classe `gap-s` à la première balise `<div>` de la deuxième balise `<div>` de la balise `<main>`
- Ajouter la classe `flex-column` à la première balise `<div>` de la deuxième balise `<div>` de la balise `<main>`
- Ajouter la classe `flex-justify-center` à la première balise `<div>` de la deuxième balise `<div>` de la balise `<main>`

- Ajouter la classe `flex-align-center` à la première balise `<div>` de la deuxième balise `<div>` de la balise `<main>`

- Ajouter la classe `xs-flex-row` à la première balise `<div>` de la deuxième balise `<div>` de la balise `<main>`

- Ajoutez les classes `md-flex-justify-center md-gap-xl  md-gap-l` à la première balise `<div>` de la deuxième balise `<div>` de la balise `<main>`

- Ajoutez les classse `lg-flex-justify-start` a la première balise `<div>` de la deuxième balise `<div>` de la balise `<main>`

La première balise `<div>` de la deuxième balise `<div>` de la balise `<main>` doit avoir les classes suivantes `flex padding-y-s gap-s flex-column flex-justify-center flex-align-center 
xs-flex-row md-flex-justify-center md-gap-xl  md-gap-l lg-flex-justify-start`




# 2. La page CV

- Remplacer la balise `<header>` du fichier `cv.html` par celle du fichier `index.html`
- Remplacer la balise `<footer>` du fichier `cv.html` par celle du fichier `index.html`


# 3. Le page contact 


