# rkarina07.git.io.
https://github.com/rkarina07-pixel/San-Valent-n-.git
<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<title>Cita de San Valentín 💘</title>
<style>
body {
  font-family: 'Arial', sans-serif;
  background: linear-gradient(#ff9a9e, #fad0c4);
  text-align: center;
  padding: 30px;
}

.game {
  background: white;
  border-radius: 20px;
  padding: 25px;
  max-width: 420px;
  margin: auto;
  box-shadow: 0 10px 25px rgba(0,0,0,0.2);
}

h1 {
  color: #e91e63;
}

.nombre {
  font-size: 18px;
  margin-bottom: 15px;
  color: #555;
}

button {
  width: 90%;
  padding: 15px;
  margin: 10px 0;
  font-size: 18px;
  border: none;
  border-radius: 15px;
  cursor: pointer;
}

.a { background: #ff4081; color: white; }
.b { background: #ffc107; }
.c { background: #8bc34a; color: white; }

button:hover {
  transform: scale(1.05);
}

#resultado {
  margin-top: 20px;
  font-size: 20px;
  color: #d81b60;
}
</style>
</head>

<body>

<div class="game">
  <h1>💖 ¿Aceptas una cita de San Valentín? 💖</h1>
  <div class="nombre">
    <strong id="textoNombres"></strong>
  </div>

  <button class="a" onclick="respuestaA()">💘 Sí, cita asegurada</button>
  <button class="b" onclick="respuestaB()">✨ Tal vez… sorpréndeme</button>
  <button class="c" onclick="respuestaC()">😊 Repetir nivel (otra cita)</button>

  <div id="resultado"></div>
</div>

<script>
const quienInvita = "Karina";   // TU NOMBRE
const invitado = "Alex";       // SU NOMBRE

document.getElementById("textoNombres").innerText =
  quienInvita + " te invita a una cita especial, " + invitado + " 💕

function respuestaA() {
  document.getElementById("resultado").innerHTML =
  "🎉 ¡" + invitado + " aceptó! 💕 " + quienInvita + " ya está planeando la cita 🥰";
}

function respuestaB() {
  document.getElementById("resultado").innerHTML =
  "😏 " + invitado + " quiere ser sorprendido… " + quienInvita + " tiene una misión 💐";
}

function respuestaC() {
  document.getElementById("resultado").innerHTML =
  "😍 Nivel extra desbloqueado: más citas para " + quienInvita + " y " + invitado + " 💖";
}
</script>

</body>
</html>
