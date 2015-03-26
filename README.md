# google_translator
Usando a tradução do Google customizada no site.

Chamando scripts
Jquery
<script type="text/javascript" src="js/jquery-1.11.1.min.js" language="javascript"></script>

API do Google
<script src="//translate.google.com/translate_a/element.js?cb=googleTranslateElementInit"></script>

Função da tradução
<script type="text/javascript" src="js/tradutor.js"></script>


para adicionar a tradução do google basta adicionar o código abaixo:

<div class="language">
			<div style="display:none;" id="google_translate_element"></div>
			<ul class="nav-language">
				<li><a href="javascript:void(0)" class="pt" onclick="ChangeLang('pt')" title="Traduzir para portugu&ecirc;s"><img src="img/portugues.gif" border="0" alt="Portugues" /></a></li>
				<li><a href="javascript:void(0)" class="en" onclick="ChangeLang('en')" title="Translate to English"><img src="img/english.gif" border="0" alt="English" /></a></li>
				<li><a href="javascript:void(0)" class="es" onclick="ChangeLang('es')" title="Traducir al espa&ntilde;ol"><img src="img/espanol.gif" border="0" alt="Spanish" /></a></li>
			</ul>
		</div>
