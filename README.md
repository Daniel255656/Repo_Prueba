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
 		a:active{ color: #000;}
 		a:visited{color: #000;}
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
 		#content{ width: 1000px; height: 780px; padding: 10px 0;}
 		#principal{width: 740px; height: 780px; float: left; padding: 10px 30px; font-size: 17px; text-align: justify; background-color: #f1f800;}
 		#lateral{width: 190px; height: 780px; float: left; padding: 10px 5px;}

 		/*Clases
		las clases se hacen con .
 		*/
 		.menu{width: 198px; height: 48px; text-align: center; background-image: url(img/menu.jpg); font-size: 18px;}

 		.footerLadoA{width: 1000px; height: 50px;}
 		.footerLadoB{width:500px; height:60px; float: left; font-size: 12px;}

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
				<h2 style="text-align: center;">Información sobre la minería</h2>

				<!--Parrafo 1-->
				<table>
					<tr>
						<td style="width:70%; height: 100px;background-color: red;">
							<p>La minería es la extracción selectiva de los minerales y otros materiales de la corteza terrestre de los cuales se puede obtener un beneficio económico, así como la actividad económica primaria relacionada con ella. Dependiendo del tipo de material a extraer la minería se divide en metálica, no metálica y piedras ornamentales y de construcción. Existen más de 7000 minas en producción y se construyen más cada año. La minería ha tenido un significativo impacto en el desarrollo de muchos países (incluso algunos que hoy en día no tienen industria minera).</p>
						</td>
						<td style="width: 30%; text-align: center; background-color: pink">
							<img src="img/miniMineros01.jpg" width="150" height="100" alt="mineros">
						</td>
					</tr>
				</table>

				<!--Parrafo 2-->
				<table>
					<tr>
						<td style="width: 30%; text-align: center;">
							<img src="img/minimineros02.jpg" width="150" height="100" alt="mineros">	
						</td>
						<td style="width:70%; height: 100px;">
							<p>Los métodos de explotación pueden ser a cielo abierto o subterráneo. Los factores que lo determinarán serán entre otros la geología y geometría del yacimiento y la característica geomecánica del mineral y el estéril, también influyen factores económicos que rigen la industria minera actual.</p>
						</td>
					</tr>
				</table>

				<!--Parrafo 3-->
				<table>
					<tr>
						<td style="width:70%; height: 100px;">
							<p>El proceso de minería involucra diferentes etapas las cuales son llevadas a cabo para desarrollar un proyecto minero, dentro de estas etapas se encuentran; la búsqueda y estimación de recursos, proyecto (prefactibilidad, factibilidad, ingeniería de detalles), obras, desarrollo minero ó explotación (arranque y manejo de materiales), procesamiento y comercialización.</p>
						</td>
						<td style="width: 30%; text-align: center;">
							<img src="img/minimineros03.jpg" width="150" height="100" alt="mineros">	
						</td>
						
					</tr>
				</table>

				<!--Parrafo 4-->
				<table>
					<tr>
						<td style="width: 30%; text-align: center;">
							<img src="img/minimineros04.jpg" width="150" height="100" alt="mineros">
						</td>	
						<td style="width:70%; height: 100px;">
							<p>La mina más antigua que se tiene constancia arqueológica es "Cueva del León", en Suazilandia. En este lugar, que de acuerdo con las dataciones por el método del carbono 14 tiene una edad de 43.000 años, los hombres del paleolítico excavaban buscando hematites, un mineral que contiene hierro, con el que probablemente producían pigmentos de color ocre.</p>
						</td>
					</tr>
				</table>
				
			</div>

			<!-- div lateral-->
			<div id="lateral">
					<img src="img/anuncio1.jpg" width="100%" height="270;" alt="Publicidad">

					<p>Peores consecuencias que la sangre y el fuego de la guerra tuvo la implantación de una economía minera. Las minas exigían grandes desplazamientos de población y desarticulaban las unidades agrícolas comunitarias; no sólo extinguían vidas innumerables a través del trabajo forzado, sino que además, indirectamente, abatían el sistema colectivo de cultivos. <br><br><strong>"Las venas abiertas de América Latina" (1971), Eduardo Galeano</strong></p>

					<img src="img/anuncio3.jpg" width="100%" height="270;" alt="Publicidad">
					


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
