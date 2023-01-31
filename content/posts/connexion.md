---
title: "Les erreurs à éviter sur une page de connexion"
date: 2023-01-30T16:47:12+01:00
description: "La page de connexion est un aspect d'un site web qui peut facilement être négligé. Comme s’il suffit de créer quelques champs de formulaire et voilà, le tour est joué. Cependant, comme le reste d'une interface, la page de connexion est cruciale. Si le système de connexion n'est pas bien conçu, c'est alors un grand nombre de personnes qui n'arrivera pas à se connecter et par conséquent n'utilisera pas votre produit."
image: images/goodconnexion.webp
draft: false
---

# La page de connexion

La page de connexion est un aspect d'un site web qui peut facilement être négligé. Comme s’il suffit de créer quelques champs de formulaire et voilà, le tour est joué. Cependant, comme le reste d'une interface, la page de connexion est cruciale. Si le système de connexion n'est pas bien conçu, c'est alors un grand nombre de personnes qui n'arrivera pas à se connecter et par conséquent n'utilisera pas votre produit.

## La page de connexion et les éléments qui me feront ne jamais vouloir me connecter.

> Autheur Alex Slatkus <br> [Source de l'article et des images](https://blog.prototypr.io/dont-do-these-things-on-your-login-page-78497189aa01)

**_Alex Slatkus_** partage son avis basé sur son expérience des pages de connexion. Selon lui, il existe de bonnes pratiques à réaliser. Également de mauvaise pratique à ne surtout pas réaliser. C'est justement de quoi traite l'article. **_Alex Slatkus_** nous explique selon lui les cinq choses à éviter dans une page de connexion.

L'auteur de l'article insiste sur le fait que la page de connexion est probablement le premier contacte avec le service en ligne. C'est la porte d'entrée du produit. Il fait la comparaison avec une porte d'entrée physique. Lorsque nous arrivons chez quelqu'un et que la poignée est branlante, ou que la sonnerie ne fonctionne pas. Alors nous avons instinctivement moins confiance en vers la propriété. Cependant, si la porte d'entrée s'ouvre automatique et rapidement, alors nous commençons notre visite agréablement.

### 1. Ne pas pouvoir afficher la valeur du mot de passe

<img src="/labeveilletech/images/afficherMotDePasse.webp">

Dans ce point,**_Alex Slatkus_** exprime le fait qu'un champ de formulaire destiné au mot de passe se doit d'avoir la possibilité d'afficher ou de cacher le contenu du champ. C'est une possibilité qui facilite grandement l'expérience de l'utilisateur. Avoir la possibilité de voir où est l'erreur dans le mot de passe pour rapidement corriger cette erreur. Aulieu de devoir tous récrire à chaque fois.

L'auteur insiste sur le fait que c'est un besoin plus que nécessaire sur les interfaces mobile. En effet, l'erreur est plus fréquente sur ces minuscules claviers numériques que sur un clavier physique.

Dans l'illustration au-dessus, l'auteur en profite également pour montrer le mauvais exemple de mettre un lien d'oublie du mot de passe directement sur le champ de mot de passe. Ce qui est une très mauvaise pratique.

### 2. Du contenu marketing distrayant

<img src="/labeveilletech/images/connexionMarketing.webp" width="30%">

L'auteur de l'article explique que les personnes qui travaillent dans le marketing voient la page de connexion comme une aubaine pour du contenu publicitaire. Cependant, c'est apparemment une très mauvaise pratique.

L'utilisateur va être distrait lors de la connexion. De plus, le contenu marketing peut être perçu comme gênant pour l'utilisateur. Jusqu'au point où il peut complètement empêcher l'utilisateur de comprendre où sont les champs de formulaires.

Dans l'exemple au-dessus, la page de connexion souhaite communiquer à propos de cartes de crédit. **_Alex Slatkus_** insiste sur le fait que ces informations ne sont pas au bon endroit et que l'utilisateur peut être intéressé de lire ce contenu plus tard dans le site web.

<img src="/labeveilletech/images/connexionMarketing2.webp">

Dans cet exemple, l'auteur illustre l'apparition multiple de contenu marketing. De plus, ces différents contenus ne s'affichent pas au même moment, ce qui risque de déconcentrer l'utilisateur.

### 3. Confondre "Log in" et "Login"

<img src="/labeveilletech/images/connexionLogin.webp">

Ce problème a lieu lors d'interface dans la langue en anglais. Il faut bien différencier les deux. Ce n'est pas un grand problème qui en est. Mais cela permet de ne pas faire l'erreur et d'avoir une meilleure image auprès des utilisateurs.

1. "Login" est le nom traduit en français par "Connexion"
2. "Log in" est le verbe traduit en français par "Se connecter"

Ainsi, en anglais, la page de connexion prend le terme "Login". Alors que "Log in" étant l'action de se connecter. Ce terme doit donc se retrouver sur le bouton pour se connecter.

L'erreur en français est moins fréquente, car nous disons "la page de connexion" et "où est la page pour se connecter?". Il est toutefois intéressant d'observer cette nuance et de pouvoir apporter le bon terme lors de design multilingues.

### 4. Les champs de formulaires avec de petites largeurs

<img src="/labeveilletech/images/connexionLongueurChamps.webp">

Il est nécessaire de prendre en compte que certaines personnes ont de long nom et prénom. Par conséquent, leur e-mail risque également d'être long. C'est donc très gênant d'avoir un champ de formulaire qui n'affiche pas l'entièreté de l'e-mail. L'utilisateur peut rapidement se perdre.

**_Alex Slatkus_** conseille d'avoir un champ de formulaire qui permet de contenir plus de 35 caractères avant que le champ ne doive défiler.

<img src="/labeveilletech/images/connexionLongueurChamps2.webp">

À l'inverse, faire des champs trop longs va déstabiliser l'utilisateur qui risque de se sentir intimidé.

### 5. Avoir des points de mot de passe trop petits

<img src="/labeveilletech/images/connexionPointPetitPass.webp">

Ce n'est pas le point le plus important pour se connecter. Toutefois, cela peu rendre plus complexe l'expérience de l'utilisateur. En effet, lorsque nous entrons un mauvais mot de passe, un réflexe que nous pouvons tous avoir, c'est de regarder le champ mot de passe. Ce qui permet de nous rendre compte combien de caractères ont été inscrits. Par conséquent, si les points sont trop petits, alors il est difficile de pouvoir compter le nombre de caractères entrés. Ce qui forme l'utilisateur d'entrée à nouveau le mot de passe depuis le début.

### 5. Le formulaire parfait selon Alex Slatkus

<img src="/labeveilletech/images/goodconnexion.webp">

> **_Alex Slatkus_** nous montre le formulaire parfait selon lui. Un formulaire qui respecte chacune des bonnes pratiques démontrées dans cet article.

### Pour la suite

L'article de **_Alex Slatkus_** est un article intéressant qui permet d'apporter une attention à la page de connexion. Ces informations et son expérience sont très intéressantes à prendre en compte pour de prochains projets. À l'avenir, lorsque je vais devoir designer une interface de connexion, je vais alors pouvoir me référer à l'expérience de **_Alex Slatkus_**.

C'est pour ma part une opportunité que d'avoir lu son article. Je n'étais pas aux claires sur l'ensemble de ces points à éviter. Typiquement d'avoir la réflexion de ne pas faire des champs de textes trop courts. Ou alors également de laisser une page de connexion sobre de toute annonce marketing.

> **_Alex Slatkus_** m’a permis de mettre en avant le fait qu'une page de connexion est la porte d'entrée du produit digital. Il est donc nécessaire d'appliquer toutes les bonnes pratiques.

> Autheur Alex Slatkus <br> [Rappel de la source de l'article et des images](https://blog.prototypr.io/dont-do-these-things-on-your-login-page-78497189aa01)
