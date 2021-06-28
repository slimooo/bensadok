---
layout: post
title: Existe-t-il des alternatives à Google Analytics conformes au RGPD ?
date: '2021-03-25 10:57:09'
tags:
- rgpd
---

Les éditeurs de site utilisent souvent des solutions de mesure d’audience pour comprendre comment leur site est consulté, connaitre sa fréquentation et étudier ses performances. C’est pour répondre à ces besoins que Google a lancé Analytics, son outil de mesure d’audience cloud et gratuit.

## Pourquoi Google Analytics n’est pas conforme au RGPD ?  

Pour proposer son service, Google dépose sur le terminal du visiteur un traceur appelé cookie qui lui permettra d’identifier chaque utilisateur de manière individuelle. Avec cette technologie, Google collecte des données personnelles sur les visiteurs, dont notamment l’adresse IP et l’identifiant du navigateur (l’user-agent). Dans la plupart des cas, et par défaut, les données collectées ne sont pas anonymisées. Analytics opère donc un traitement de données personnelles et se voit ainsi soumis à l’application de la réglementation sur la protection des données personnelles (RGPD et ePrivacy).

[Google Analytics]( __GHOST_URL__ /blog/comment-rendre-google-analytics-conforme-au-rgpd/) règne en maitre sur le marché de la mesure d’audience. Plus de 8 sites sur 10 utilisent ce service. Il permet à Google de suivre précisément la navigation d’un internaute sur la majorité des sites qu’il consulte. En opérant de la sorte, Google peut proposer à ses clients des profils très détaillés et optimiser leurs annonces publicitaires.

Google Analytics n’est pas simplement un outil de mesure d’audience, c’est surtout un outil marketing en puissance. Contrairement à certains [outils analytics]( __GHOST_URL__ /analytics/), la solution de Google nécessite de collecter le consentement explicite du visiteur pour pouvoir être utilisé conformément au RGPD et aux recommandations de la CNIL.

Si on n’informe pas le visiteur de manière précise sur ce qui est fait de ses données personnelles et si celui-ci ne clique pas sur le bouton “Oui j’accepte”, aucun dépôt ne devrait être réalisé via Google Analytics. Ces mesures peuvent donc donner lieu pour les éditeurs à la perte d’une grande partie des données sur les visites.

En outre, par défaut les cookies déposés par Google Analytics sont conservés pendant deux ans. Cela est en totale contradiction avec le principe de limitation de la durée de conservation des données personnelles. Un cookie de mesure d’audience devrait être conservé pour une durée maximale de treize mois.

## Matomo est-elle une solution alternative et conforme au RGPD ?

Matomo propose une solution open source de mesure d’audience alternative à Google Analytics. Là où Google Analytics ne propose son service que sur le Cloud, Matomo offre la possibilité d’utiliser sa solution sur le cloud ou alors de l’installer sur son serveur (on-premise).

En utilisant Matomo, il n’est pas nécessaire de recueillir le consentement de l’utilisateur avant le dépôt de cookies. Cet outil bénéficie de l’exemption de consentement prévue à l’article 5 des lignes directrices de la CNIL.

Cependant, cette solution n’est pas privacy by design. Tout comme pour Google Analytics, par défaut les données collectées avec Matomo ne sont pas anonymisées. Pour une utilisation conforme au RGPD de l’outil de mesure d'audience, il sera nécessaire d’activer l’anonymisation des données (notamment l’adresse IP), et de définir une durée de conservation de 13 mois.

Toutefois, à la différence de Google Analytics, l’installation et la configuration de Matomo se révèlent plus complexes. Pour pouvoir utiliser Matomo, il est nécessaire de disposer d’un serveur dédié ou d’un VPS.

Matomo est aussi très complexe à utiliser. En effet, si cet outil présente beaucoup de fonctionnalités, cette solution n’est pas accessible à tout le monde. C’est au contraire un produit surdimensionné, qui risque de perdre en route les personnes qui cherchent simplement à connaitre le nombre de visiteurs, les pages consultées ou encore la source du trafic.

## Existe-t-il une solution de mesure d’audience conforme au RGPD ?

L'entreprise Astra Porta a développé une solution de mesure d’audience, simple d’utilisation et respectueuse par défaut de la vie privée des utilisateurs.

[Abla Analytics](https://abla.io/) ne dépose aucun cookie, se lance en un clic et ne nécessite aucune configuration particulière.

Surtout, la solution de mesure d’audience étant exemptée de la collecte du consentement du visiteur, il est possible de collecter des données instantanément.

Pour plus d’informations :

<figure class="kg-card kg-bookmark-card"><a class="kg-bookmark-container" href="https://abla.io/"><div class="kg-bookmark-content">
<div class="kg-bookmark-title">Abla Analytics - Mesure d’audience conforme RGPD CNIL - Alternative à Google Analytics</div>
<div class="kg-bookmark-description"></div>
<div class="kg-bookmark-metadata">
<img class="kg-bookmark-icon" src="https://abla.io/assets/images/icons/fav*32.png"><span class="kg-bookmark-author">ootancy</span>
</div>
</div>
<div class="kg-bookmark-thumbnail"><img src="https://abla.io/images/logo.svg"></div></a></figure>

