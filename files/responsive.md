# Responsive

## Activer le responsive

Par défaut, les navigateurs mobiles va partir du principe que votre site internet n'est pas adapté aux téléphones portables. Ainsi, ils vont afficher les sites web avec une largeur de `1024px` (par exemple), alors même que votre téléphone ne fait que `360px`. Pour un exemple concret, vous pouvez visiter [le site de majorette](https://www.majorette.com/fr/accueil/) avec votre téléphone ou avec le [mode mobile de Chrome](https://developers.google.com/web/tools/chrome-devtools/device-mode/#viewport).

Vous pouvez indiquer que votre site internet est responsive à l'aide d'une balise `<meta>` placé dans la partie `<head>` de votre document HTML :

```html
<meta name="viewport" content="width=device-width,initial-scale=1">
```

## Les requêtes média

Les requêtes média (_media queries_) permettent de modifier l'apparence d'un site ou d'une application en fonction du type d'appareil. Par exemple, il est possible d'appliquer des styles différents pour la visualisation et l'impression d'une page web. 


<!--stackedit_data:
eyJoaXN0b3J5IjpbLTEzMzk4NDUxNTYsMTg0NjM0OTg5OCwtMT
QxODE5OTA3MSwxNzcyNDk1Mzk2LDExNDI1ODk5MjEsLTMzNDk2
MjE2XX0=
-->