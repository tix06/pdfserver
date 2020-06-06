# page internet
aller sur [https://pdfshowy.netlify.app/](https://pdfshowy.netlify.app/)

# serveur local
pour tester les pages en local

dans la console, se rendre dans le dossier du projet : Documents/GitHub/pdfserver

Puis écrire : 

```
python3 -m http.server
```

Dans le navigateur : 

```python
http://0.0.0.0:8000/
```

# comment utiliser le site
* mettre les fichiers pdf dans /web
* et mettre en lien dans le fichier `index_SNT` ou `index_NSI` ou `index_PC` 

numeroter de la manière suivante pour permettre le classement : 

* `C52_D51` pour le premier document du chapitre D5 de la classe de seconde PC
* `C51_D51` pour le premier document du chapitre D5 de la classe de seconde SNT
* `C71_D12` pour le 2e document du chapitre D1 de la classe de terminale NSI

# Liens

* Setup PDF.js in a website : [https://github.com/mozilla/pdf.js/wiki/Setup-pdf.js-in-a-website](https://github.com/mozilla/pdf.js/wiki/Setup-pdf.js-in-a-website)
* Rendering PDF Files in the Browser with PDF.js : [https://pspdfkit.com/blog/2018/render-pdfs-in-the-browser-with-pdf-js/](https://pspdfkit.com/blog/2018/render-pdfs-in-the-browser-with-pdf-js/)
