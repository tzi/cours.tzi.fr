# Responsive

Le responsive est le fait d'adapter un site internet aux différents type d'appareils, notamment aux téléphones.

## Activer le responsive

Par défaut, les navigateurs mobiles va partir du principe que votre site internet n'est pas adapté aux téléphones portables. Ainsi, ils vont afficher les sites web avec une largeur de `1024px` (par exemple), alors même que votre téléphone ne fait que `360px`. Pour un exemple concret, vous pouvez visiter [le site de majorette](https://www.majorette.com/fr/accueil/) avec votre téléphone ou avec le [mode mobile de Chrome](https://developers.google.com/web/tools/chrome-devtools/device-mode/#viewport).

Vous pouvez indiquer que votre site internet est responsive à l'aide d'une balise `<meta>` placé dans la partie `<head>` de votre document HTML :

```html
<meta name="viewport" content="width=device-width,initial-scale=1">
```

## Les requêtes média

Les requêtes média (_media queries_) permettent de modifier l'apparence d'un site en fonction du type d'appareil. La plupart du temps elles permettent d'appliquer certains styles en fonction de ses caractéristiques, notamment la largeur de la zone d'affichage (_viewport_).

Exemple de syntaxe :

```css
/* Des titres asssez grands par défaut (quelque soit l'appareil) */
h1 {  
	font-size: 36px;  
}

/* Des titres plus petits pour les appareils qui font maximum 560px de large */
@media (max-width: 560px) {  
	h1 {  
		font-size: 24px;  
	}
}
```

## Flexbox
<!--stackedit_data:
eyJoaXN0b3J5IjpbNjYyNzA3NzY4LDExMTE0ODY4NTYsLTEyMz
UxNTk1MDMsLTEwMDUzMTU3MDgsLTE1OTMxODgwMzIsMTg0NjM0
OTg5OCwtMTQxODE5OTA3MSwxNzcyNDk1Mzk2LDExNDI1ODk5Mj
EsLTMzNDk2MjE2XX0=
-->