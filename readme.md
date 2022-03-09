# Jak nainstalovat vývojové prostředí #
## Windows ##

1. Nainstalovat [Node.js](https://nodejs.org/en/download/releases/) (ver 16.4.2).
2. Spustit Node.js příkazový řádek (součástí instalace)
3. Nainstalovat globálně gulp `npm install gulp --global`
4. Nainstalovat gulp (do adresáře s šablonami)
`npm install`

## Mac OS ##

1. Nainstalovat [Node.js](https://nodejs.org/en/download/releases/) (ver 16.4.2).
2. Spustit Terminál.
3. Nainstalovat globálně gulp `sudo npm install gulp --global`
4. Nainstalovat gulp (do adresáře s šablonami)
`sudo npm install`

## Spuštění  ##
1. `gulp watch` slouží ke spuštění a soustavného hlídání změn a jejich kompilaci
2. `gulp build` provede jednorázovou kompilaci