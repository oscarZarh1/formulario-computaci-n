# formulario-computaci-n
<html>
  <head>
    <meta charset="UTF-8">
    <title>Formulario De Muestra Computación</title>

  </head>

    <img src="https://www.google.com/imgres?imgurl=https%3A%2F%2Fstatic.vecteezy.com%2Fsystem%2Fresources%2Fpreviews%2F002%2F732%2F031%2Fnon_2x%2Fdark-gray-background-with-circles-abstract-illustration-with-colorful-spots-in-nature-style-pattern-for-wallpapers-curtains-vector.jpg&tbnid=Jn_sL3aBMfqMKM&vet=12ahUKEwjtopiinev9AhUlwMkDHeWrBCgQMygFegUIARDTAQ..i&imgrefurl=https%3A%2F%2Fes.vecteezy.com%2Farte-vectorial%2F2732031-fondo-de-vector-gris-oscuro-con-circulos-ilustracion-abstracta-con-manchas-de-colores-en-la-naturaleza-patron-de-estilo-para-papeles-pintados-cortinas&docid=g3htER0TNpzE5M&w=1960&h=980&q=background%20de%20circulos%20color%20gris&ved=2ahUKEwjtopiinev9AhUlwMkDHeWrBCgQMygFegUIARDTAQ">
  <body>
    <h1 style="color:blue;">Formulario de ejemplo computacion basica II</h1>
    <form action="procesar.php" method="POST">
      <label for="nombre">Nombre:</label><br>
      <input type="text" id="nombre" name="nombre"><br>

      <label for="email">apellidos:</label><br>
      <input type="apellidos" id="email" name="email"><br>

      <label for="mensaje">email:</label><br>
      <textarea id="email" name="mensaje"></textarea><br>

      <label for="mensaje">hora de registro:</label><br>
      <textarea id="mensaje" name="mensaje"></textarea><br>

      <label for="mensaje">fecha:</label><br>
      <textarea id="mensaje" name="mensaje"></textarea><br>

      <label for="mensaje">Mensaje:</label><br>
      <textarea id="mensaje" name="mensaje"></textarea><br>

      <label for="mensaje">hora de salida:</label><br>
      <textarea id="mensaje" name="mensaje"></textarea><br>

    </form>
      <input type="submit" value="Enviar" onclick="mostrarMensaje()">
    </form>

    <script>
      function mostrarMensaje() {
        alert("¡Gracias por enviar tu mensaje!");
      }
    </script>
  </body>
</html>
