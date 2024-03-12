```html
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fiche de Contrôle de Grading</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        .container {
            max-width: 600px;
            margin: 20px auto;
            padding: 20px;
            border: 1px solid #ccc;
            border-radius: 5px;
            background-color: #f9f9f9;
        }
        img {
            max-width: 100%;
            height: auto;
            display: block;
            margin: 20px auto;
        }
        .grading {
            display: flex;
            align-items: center;
            justify-content: space-between;
            margin-bottom: 10px;
        }
        .grading label {
            font-weight: bold;
        }
        .grading input {
            width: 50px;
            text-align: center;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Fiche de Contrôle de Grading</h1>
        <img src="lien_de_votre_image" alt="Nom de la carte">
        <div class="grading">
        <h2>Nom de la carte</h2>
            <label>Note 10:</label>
            <input type="number" name="note10" value="0" min="0" readonly>
        </div>
        <div class="grading">
            <label>Note 9.5:</label>
            <input type="number" name="note9.5" value="0" min="0" readonly>
        </div>
        <div class="grading">
            <label>Note 9:</label>
            <input type="number" name="note9" value="0" min="0" readonly>
        </div>
        <div class="grading">
            <label>Note 8.5:</label>
            <input type="number" name="note8.5" value="0" min="0" readonly>
        </div>
        <div class="grading">
            <label>Note 8:</label>
            <input type="number" name="note8" value="0" min="0" readonly>
        </div>
        <div class="grading">
            <label>Note 7.5:</label>
            <input type="number" name="note7.5" value="0" min="0" readonly>
        </div>
        <div class="grading">
            <label>Note 7:</label>
            <input type="number" name="note7" value="0" min="0" readonly>
        </div>
        <div class="grading">
            <label>Note 6.5:</label>
            <input type="number" name="note6.5" value="0" min="0" readonly>
        </div>
        <div class="grading">
            <label>Note 6:</label>
            <input type="number" name="note6" value="0" min="0" readonly>
        </div>
        <div class="grading">
            <label>Note 5.5:</label>
            <input type="number" name="note5.5" value="0" min="0" readonly>
        </div>
        <div class="grading">
            <label>Note 5:</label>
            <input type="number" name="note5" value="0" min="0" readonly>
        </div>
    </div>
</body>
</html>
