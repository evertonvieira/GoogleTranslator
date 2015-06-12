# google_translator
Usando a tradução do Google customizada no site.

Chamando scripts:
```bash
Jquery: js/jquery-1.11.1.min.js
```
API do Google: 
```bash
//translate.google.com/translate_a/element.js?cb=googleTranslateElementInit
```

Função da tradução: 
```bash
js/tradutor.js
```

Para adicionar a tradução, basta adicionar o código abaixo e customizar de acordo com suas necessidades:

```bash
<div class="language">
	<div style="display:none;" id="google_translate_element"></div>
	<ul class="nav-language">
		<li><a href="javascript:void(0)" class="pt" onclick="ChangeLang('pt')" title="Traduzir para português"><img src="img/portugues.gif" alt="Portugues" /></a></li>
		<li><a href="javascript:void(0)" class="en" onclick="ChangeLang('en')" title="Translate to English"><img src="img/english.gif" alt="English" /></a></li>
		<li><a href="javascript:void(0)" class="es" onclick="ChangeLang('es')" title="Traducir al espanhol"><img src="img/espanol.gif" alt="Spanish" /></a></li>
	</ul>
</div>
```
