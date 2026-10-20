<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>Reserva</title>
    <link rel="stylesheet" href="styles.css" />
</head>
<body>
    <div class="container">
        <h1 id="title">Reserva tu lugar</h1>

        <form id="reservationForm">
            <label for="name" data-translate="nameLabel">Nombre:</label>
            <input type="text" id="name" name="name" required />

            <label for="date" data-translate="dateLabel">Fecha:</label>
            <input type="date" id="date" name="date" required />

            <label for="time" data-translate="timeLabel">Hora:</label>
            <input type="time" id="time" name="time" required />

            <button type="submit" id="submitBtn" data-translate="submitBtn">Reservar</button>
        </form>

        <div class="language-switch">
            <button onclick="setLanguage('es')">Español</button>
            <button onclick="setLanguage('en')">English</button>
        </div>
    </div>

    <script src="script.js"></script>
</body>
</html>
