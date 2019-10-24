# Responsive

## Activer le responsive

Par défaut, les navigateurs mobiles va partir du principe que votre site internet n'est pas adapté aux téléphones portables. Ainsi, ils vont afficher les sites web avec une largeur de `1024px` (par exemple), alors même que votre téléphone ne fait que `360px`. Pour un exemple concret, vous pouvez visiter [le site de majorette](https://www.majorette.com/fr/accueil/) avec votre téléphone ou avec le [mode mobile de Chrome](https://developers.google.com/web/tools/chrome-devtools/device-mode/#viewport).

Vous pouvez indiquer que votre site internet est responsive à l'aide d'une balise `<meta>` placé dans la partie `<head>` de votre document HTML :

```html
<meta name="viewport" content="width=device-width,initial-scale=1">
```

## Les requêtes média

Les requêtes média (_media queries_) permettent de modifier l'apparence d'un site en fonction du type d'appareil. La plupart du temps elles permettent d'appliquer certains styles en fonction de ses caractéristiques, notamment la largeur de la zone d'affichage (_viewport_).

Voici une 

```css
@media (max-width: 560px) {  
	.title {  
		font-size: 24px;  
	}
}
```

Dans cette 

<!--stackedit_data:
eyJoaXN0b3J5IjpbMzMzNzg1Njc0LC0xNTkzMTg4MDMyLDE4ND
YzNDk4OTgsLTE0MTgxOTkwNzEsMTc3MjQ5NTM5NiwxMTQyNTg5
OTIxLC0zMzQ5NjIxNl19
-->