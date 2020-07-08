# pass-culture-beneficiary-android-app

C'est la version TWA (Trusted Web Activities) de l'application frontend du pass Culture pour les jeunes.

Cette application n'est qu'une simple enveloppe autour de la page web du pass Culture.
Elle permet de retrouver l'application dans les stores, de la mettre sur sa page d'accueil et de l'ouvrir en plein écran.
Par contre elle n'a aucun comportement spécifique.

## *Build Variants*

Nous utilisons les *Build Variants* pour construire trois applications différentes :
- `debug` : permet de construire une application pointant sur notre environnement de `testing`
- `staging` : permet de construire une application pointant sur notre environnement de `staging`
- `release` : permet de construire une application pointant sur notre environnement de `production`
