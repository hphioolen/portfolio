# portfolio
basis portfolio bestanden voor sage theme


# Benodigd:
- Custom post type 'portfolio';
- 

# Dependancies
Fancybox

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