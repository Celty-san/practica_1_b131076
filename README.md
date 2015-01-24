# practica_1_b131076
practica 1 programacion de apicaciones web
<html>
<head> </head>
<body>

<form action="insertar.php" method="post">

<br><br>
	<center>
		<table border="8"  width=25% height="25%">	
	<tr>
	<th colspan="2" ALIGN=LEFT ><h3>Nuevo Alumno</h3></th>
	</tr>

	<tr>
	<td> 
		<center>
		<table FRAME="void" RULES="none">	
			<tr>
			<th><h3> Matricula: </h3></th>
			<th><h3> <input type="text" size="20" maxlength="7"></h3></th>
			</tr>

			<tr>
			<td><h3> Nombre:</h3></td>
			<td><h3><input type="text" size="20" maxlength="20"></h3></td>
			</tr>

			<tr>
			<td><h3>Apellido<br>Paterno</h3></td>
			<td><h3><input type="text" size="20" maxlength="20"></h3></td>
			</tr>

			<tr>
			<td><h3>Apellido<br>Materno</h3></td>
			<td><h3><input type="text" size="20" maxlength="20"></h3></td>
			</tr>

		</table>
		</center>

	</td>

	<td><h3> 


			<center>
		<table FRAME="void" RULES="none">	
			<tr>
			<th><h3> Fecha de<br>Nacimiento </h3></th>
			<th><h3>
			<input type="date" id="deliveryDate" />
			</h3></th>
			</tr>

			<tr>
			<td><h3> Edad:</h3></td>
			<td><h3><input type="number" name="edad" min="5" max="100" step="1" value="15">
			</h3></td>
			</tr>

			<tr>
			<td><h3>Municipio:</h3></td>
			<td><h3>	<select name="municipio">
					<option value="1">opciones</option>
					<option value="2">Arriaga</option>
					<option value="3">Chamula</option>
					<option value="4">Escuintla</option>
					<option value="5">Palenque</option>
					<option value="6">Huixtla</option>
					<option value="7">otra</option>
					</select>
			</h3></td>

			</tr>

			<tr>
			<td><h3>Fotografia:</h3></td>
			<td><h3><input type="file" name="img" multiple></h3></td>
			</tr>

		</table>
		</center>


	</h3></td>

	</tr>

	<tr>
	<td colspan="2" ALIGN=RIGHT VALIGN=BOTTOM><br><h4><input type="submit" value="REGISTRAR"></h4></td>
	</tr>


</table>
			
</body>
</html>
