<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>

<body>
    <h1>Formulario de Registro </h1>
    <form action="">
        <label for="nombre">Nombre: </label>
        <input type="text" id="nombre">
        <br />
        <br />
        <label for="apellido">Apellido:</label>
        <input type="text" id="apellido">
        <br />
        <br />
        <label for="modality">Modalidad de la cursada: </label>
        <input id="onDemand" type="radio">
        <label for="onDemand"> On-Demand</label>
        <input id="live" type="radio">
        <label for="live"> En vivo </label>
        <br />
        <br />
        <label for="email">Correo: </label>
        <input type="text" id="email">
        <br />
        <br />
        <input id="info" type="checkbox">
        <label for="info"> Deseo recibir información sobre nuevos posteos en la plataforma de Nucba.</label>
        <br />
        <br />
        <input id="terms" type="checkbox">
        <label for="terms"> Declaro que leí los terminos y condiciones y estoy listo para convertirme en desarrollador
            web Full Stack.
        </label>
        <br />
        <br />
        <input type="submit" name="Enviar">
    </form>
</body>

</html>
