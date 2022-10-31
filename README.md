# Tabla-periodica
<!DOCTYPE html>
<html>
<head>
	<title>Trabajo Final </title>
	<link rel="stylesheet" type="text/css" href="CSS/estilo.css">
	<link rel="shortcut icon" type="image/png" href="Imagenes/favicon1.png"/>
</head>
<body >

	<br>
	<br>
	<br>
	<br>
	<br>
	<br>
	<br>

	<main>
		<div class="contenedor-todo">
			<div class="cajatrasera">
				<div class="cajatraseralogin">
					<h3>&iquestYa tienes una cuenta?</h3>
					<p>Inicia sesión para entrar en la p&aacutegina</p>
					<button id="btn-inicio-sesion" onclick="login()"> Iniciar sesión</button>
				</div>

				<div class="cajatraseraregistro">
					<h3>&iquestAún no tienes una cuenta?</h3>
					<p>Registrate para que puedas inicar sesión </p>
					<button id="btn-register-sesion" onclick="register()"> Registrate</button>
			</div>
			
		</div>

		<div class="contenedorloginregister">
			<form class="formulariologin" name="form">
				<h2>Iniciar sesión</h2>
				<input type="text"  id="nusuario" name="nusuario" placeholder="Usuario">
				<input type="password"  id="contra" name="contra" placeholder="Contraseña"> <br>
		        <input type="button" value="INGRESAR" onclick="go()">
		       

			</form>
		
		<form class="formularioregistro">
		<h2>Registrarse</h2>
		<input type="text" id="nombrecompleto" name="nombrecompleto" placeholder="Nombre">
		<input type="text" id="PrimerA" placeholder="Apellido Paterno">
		<input type="text" id="SegundoA" placeholder="Apellido Materno">
		<input type="text" id="usuario" name="usuario" placeholder="Nombre de usuario">
		<input type="password" id="contrase" name="contrase" placeholder="Contraseña"> <br>
		<p>Genera solo tu codigo si lo crees necesario: </p><br>
		<input type="text" name="NombreC" id="nombreC" placeholder="Tu codigo es">
		<input type="button" value="Genera codigo" onclick="Calcular()">
		<br>

		<input type="button" value="REGISTRARSE" onclick="registro()">
		

	</form>
</form>
</div>
</div>

</main>


<script type="text/javascript" src="JS/operaciones.js"></script>
</body> 
</html>
