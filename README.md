Source files for cabezas_caribe
=====

## Description

Please provide a short description of this project

## Data
Please link to any external data used, as well as scripts for cleaning and analyzing that data, all of which should live in the `/data` directory.

## Installation
After cloning the repository run:
```
npm install
```

To start watching the project and opening in the browser run:
```
npm start
```

To deploy to GitHub pages run:
```
npm run deploy
```

---

## Embeding on LSV
To embed on a webpage use this code:
```html
<!-- START OF OUR INTERACTIVE -->
<script type="text/javascript">
  window.capturados_cordoba_data = {
	"instrucciones": "**Instrucciones:** Haga clic en cada personaje en líos (rojos) para leer el estado de su proceso, su lío y su conexión política",
	"dataUri": "https://lsv-data-visualizations.firebaseio.com/cabezas_caribe.json"
  }
</script>
<div class="lsv-interactive" id="capturados_cordoba">
<img src="https://la-silla-vacia.github.io/cabezas_caribe/screenshot.png" class="screenshot" style="width:100%;">
</div>
<script defer type="text/javascript" src="https://la-silla-vacia.github.io/cabezas_caribe/script.js"></script>
<!-- END OF OUR INTERACTIE -->
```