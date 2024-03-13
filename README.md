<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Calculadora de Média</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="calculator">
        <h2>Calculadora de Média</h2>
        <div class="input-wrapper">
            <label for="cycle1">Ciclo 1:</label>
            <input type="number" id="cycle1" min="0" max="10">
        </div>
        <div class="input-wrapper">
            <label for="cycle2">Ciclo 2:</label>
            <input type="number" id="cycle2" min="0" max="10">
        </div>
        <div class="input-wrapper">
            <label for="cycle3">Ciclo 3:</label>
            <input type="number" id="cycle3" min="0" max="10">
        </div>
        <button onclick="calculateAverage()">Calcular Média</button>
        <div id="result"></div>
    </div>

    <script src="script.js"></script>
</body>
</html>
