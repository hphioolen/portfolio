# portfolio
basis portfolio bestanden voor sage theme


## Benodigd:
- Custom post type 'portfolio';
- Custom Taxonomy 'portfolio-categorie'
- Variabelen om single-post te vullen.

## CSS
Geintegreerde CSS is die van hover effectideas set 1 en 2:
http://tympanus.net/Development/HoverEffectIdeas/

## Less
Om de less bestanden te gebruiken moet de volgende regel worden toegevoegd aan de main.less files:

@import "components/_portfolio";

Verplaats vervolgens de less bestanden naar de components folder en geef het gulp commando.

## Template files
De opbouw van de bestanden in de template is als volgt:

- Sectie op de Homepage

# Dependancies

## Fancybox

| pakket   | Overrides | 
|----------|-----------|-------------|
| fancybox | Yes       | kopieer alle image files uit de fancy box naar de asset folder

Fancy box mist wel eens de bower.json, die moet dan met de hand worden toegeveoegd:
{
	"name": "fancybox",
	"version": "2.1.5",
	"main": [
		"source/jquery.fancybox.js",
		"source/jquery.fancybox.css"
	],
	"ignore": [
    	"**/.*",
    	"fancybox.jquery.json",
    	"demo"
	],
	"dependencies": {
		"jquery": ">=1.10"
	}
}

