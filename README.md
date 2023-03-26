# hospitalcetis030
pagina de un hospital cetis030
<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8">
    <title>Formulario de hospital</title>
  </head>
  <body>
    <center>
      <img src="hospital.jpg" alt="Logo del hospital" width="100">
      <h1>Hospital San Juan</h1>
      <p>Dirección: Calle 123, Ciudad</p>
      <hr>
    </center>
    <h2>Datos del paciente</h2>
    <form>
      <label for="nombre">Nombre:</label>
      <input type="text" id="nombre" name="nombre" required><br><br>
      
      <label for="estado-civil">Estado civil:</label>
      <select id="estado-civil" name="estado-civil">
        <option value="soltero">Soltero/a</option>
        <option value="casado">Casado/a</option>
        <option value="viudo">Viudo/a</option>
        <option value="divorciado">Divorciado/a</option>
      </select><br><br>
      
      <label for="ocupacion">Ocupación:</label>
      <input type="text" id="ocupacion" name="ocupacion"><br><br>
      
      <label for="genero">Género:</label>
      <input type="radio" id="masculino" name="genero" value="masculino" required>
      <label for="masculino">Masculino</label>
      <input type="radio" id="femenino" name="genero" value="femenino">
      <label for="femenino">Femenino</label><br><br>
      
    </form>
    <h2>Datos del doctor</h2>
    <form>
      <label for="cedula">Cédula profesional:</label>
      <input type="text" id="cedula" name="cedula" required><br><br>
      
      <label for="nombre-doctor">Nombre:</label>
      <input type="text" id="nombre-doctor" name="nombre-doctor" required><br><br>
      
      <label for="especialidad">Especialidad:</label>
      <input type="text" id="especialidad" name="especialidad"><br><br>
      
    </form>
    <h2>Receta</h2>
    <form>
      <label for="medicamento">Medicamento:</label>
      <input type="text" id="medicamento" name="medicamento" required><br><br>
      
      <label for="dosis">Dosis:</label>
      <input type="text" id="dosis" name="dosis" required><br><br>
      
      <label for="indicaciones">Indicaciones:</label>
      <textarea id="indicaciones" name="indicaciones" rows="4" cols="50" required></textarea><br><br>
      
      <input type="submit" value="Enviar">
    </form>
  </body>
</html>
