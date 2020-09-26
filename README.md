<!DOCTYPE html>
<html lang="es">
<head>
	<title>Mineria</title>
	<meta charset="utf-8">
	<meta name="author" content="Daniel Muñoz">
	<meta name="keywords" lang="es" content="Mineria, mineros, personas, piedra">
	<meta name="description" lang="es" content="Pagina dedicada a la mineria">

 	<!--icono de pestaña-->
 	<link rel="shorcut icon" type="image/x-icon" href="img/favicon.png">

 	<!-- Codigo CSS-->
 	<style type="text/css">
 		/*comentario*/
 		/*Las imagenes siempre tienen un efecto en mosaico, se agrega background-repeat: no-repeat para eliminar el efecto moisaco solo se vera una imagen , pero se ve de color blanco, para salocuinarlo se pone lo siguiente. backgroun-size:100% 100% es para estirar la imagen ancho y alto. background-attachment:fixed: esto es para dejar la imagen fija en el navegador. 
		
		siempre es bueno poner la familia de la letra y el tamaño de la misma	
 		*/
 		body{
 			background-color: #FFFFFF;
 			background-image: url(img/fondo.jpg);
 			background-repeat: no-repeat;
 			background-size: 100% 100%;
 			background-attachment: fixed;

 			color: #000;
 			font-family: Arial, Century;
 			font-size: 12px;
 		}
 		/*Para los links*/
 		a:link{ color: #000;}
 		a:active{ color:#000;}
 		a:visited{color:#000;}
 		/*Para definir los espacios de los span, los dos numeros es para separlos primer numero arriba y abajo, y el segundo de derecha a izquierda va a ver una distancia de hasta 15px*/
 		span{margin: 0 15px;}
 		/*identificadores
 		margin: de arriba abajo tiene una distancia de 0; auto: a los lados se ajusta de forma automatica
		padding es la distancia interno
		span: es la distancia externa.
 		*/

 		#wrapper{ width: 1000px; margin:0 auto; background-color: #FFF;}
 		#header{ height: 100px; background-color: #f4c444; width: 1000px;}
 		#nav{ height: 48px;}
 		#footer{ height: 1000px; height: 110px; text-align: center; padding-top: 5px;}

 			/* indentificadores que cambian por pagina*/
 		#content{ width: 1000px; height: 600px; padding: 10px 0;}
 		#principal{width: 740px; height: 600px; float: left; padding: 10px 30px; font-size: 15px}
 		#lateral{width: 190px; height: 600px; float: left; padding: 10px 5px;}

 		/*Clases
		las clases se hacen con . se pueden usar en mas de un elemento.
 		*/
 		.menu{width: 198px; height: 48px; text-align: center; background-image: url(img/menu.jpg); font-size: 18px;}

 		.footerLadoA{width: 1000px; height: 50px;}
 		.footerLadoB{width:500px; height:60px; float: left; font-size: 12px;}


 		.contenido1{height: 100px; width: 150px; text-align: center; float: left;}
 		.contenido2{height: 100px; width: 350px; float: left;}

 	</style>
</head>
<body>

	<!-- contenedor-->
	<div id="wrapper">
		<!--encabezado-->
		<div id="header">
			<a href="index.html">
				<img src="img/encabezado.jpg" alt="Mineria" title="mineria">
			</a>
		</div>
		<!--menu-->
		<!-- la clase se puede reutilizar mas de una vez lo que hace es que une css con html-->
		<div id="nav">
			<table style="margin: 0 auto">
				<tr>
					<td class="menu"> <a href="index.html">Inicio</a></td>
					<td class="menu"> <a href="info.html">Información</a></td>
					<td class="menu"> <a href="galeria.html">Galeria</a></td>
					<td class="menu"> <a href="contacto.html">Contacto</a></td>

				</tr>

			</table>
			
		</div> 
		<!--contenido-->
		<div id="content">
			<!--Contenido principal-->
			<div id="principal">
				<br>
				<h2>Galeria:</h2>
				<hr><hr>
				<div style="margin: 40px auto; width: 500px;">
					<div class="contenido1">
						<img src="img/contacto.png" width="100" height="70" alt="Web minería">
					</div>

					<div class="contenido2">
						<h3>
							<a href="caricatura.html"> CARICATURAS</a>
						</h3>
					</div>

					<div class="contenido1">
						<img src="img/contacto.png" width="100" height="70" alt="Web minería">
					</div>
					<div class="contenido2">
						<h3>
							<a href="galerialista.html">GALERIA DE IMAGENES</a>
						</h3>
					</div>
				</div>
				
			</div>

			<!-- div lateral-->
			<div id="lateral">
				<img src="img/anuncio1.jpg" width="100%" height="270" alt="Publicidad">

				<p>Rindiendo un justo homenaje al peor virus humano que había parido la región, el pueblo nombrado por Enrique Creel era el área de lanzamiento de todas las pestes que aquejaban a las Barrancas del Cobre: minería a cielo abierto, tala de árboles indiscriminada, cultivo de drogas y turismo de autobús. Caballo se volvía loco si tenía que pasar mucho tiempo ahí, era como alojarse en un hostal enclavado en un campo de esclavos.<br><br><strong>"Nacidos para correr" (2009), Christopher McDougall</strong></p>

			</div>

		</div>
		<!-- bloque del pie de pagina-->
		<div id="footer">
			<!--Lado Superior-->
            <div class="footerLadoA">
				<hr>
				<p>
					<span>Condiciones de uso</span> / 
					<span>Políticas de privacidad</span> / 
					<span>Noticias</span>
				</p>
				<hr>
            </div><!--Fin FooterLadoA--> 
            <!--Lado Inferior-->
            <div class="footerLadoA">
                <div class="footerLadoB">
					<strong>Diseñado por: Daniel Muñoz<br>
                    Derechos Reservados</strong>
                </div>
				<div class="footerLadoB">
					<a href="http://es-es.facebook.com/trabajaenmineria" target="_blank">
						<img src="img/facebook.png" alt="Facebook" title="Facebook" width="150" height="50">
					</a>
					<a href="#">
						<img src="img/twitter.png" alt="Twitter" title="Twitter" width="150" height="50">
					</a>
					<a href="#">
						<img src="img/instagram.png" alt="Instagram" title="Instagram" width="150" height="50">
					</a>
				</div>
            </div><!--Fin FooterLadoA-->
			
		</div>
	</div>

</body>
</html>
