# google_translator
Usando a tradução do Google customizada no site.

Chamando scripts
Jquery: js/jquery-1.11.1.min.js

API do Google: //translate.google.com/translate_a/element.js?cb=googleTranslateElementInit

Função da tradução: js/tradutor.js


Para adicionar a tradução, basta adicionar o código abaixo e customizar de acordo com suas necessidades:

<div class="language">
			<div style="display:none;" id="google_translate_element"></div>
			<ul class="nav-language">
				<li><a href="javascript:void(0)" class="pt" onclick="ChangeLang('pt')" title="Traduzir para portugu&ecirc;s"><img src="img/portugues.gif" border="0" alt="Portugues" /></a></li>
				<li><a href="javascript:void(0)" class="en" onclick="ChangeLang('en')" title="Translate to English"><img src="img/english.gif" border="0" alt="English" /></a></li>
				<li><a href="javascript:void(0)" class="es" onclick="ChangeLang('es')" title="Traducir al espa&ntilde;ol"><img src="img/espanol.gif" border="0" alt="Spanish" /></a></li>
			</ul>
		</div>
