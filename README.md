<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Descubre tus Talentos y Habilidades</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f9f9f9;
            margin: 0;
            padding: 20px;
        }
        header {
            text-align: center;
            padding: 20px;
            background-color: #4CAF50;
            color: white;
        }
        main {
            max-width: 800px;
            margin: 0 auto;
            background-color: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h1, h2, h3 {
            color: #333;
        }
        section {
            margin-bottom: 20px;
        }
        .question {
            margin: 10px 0;
        }
        .question label {
            margin-right: 10px;
        }
        footer {
            text-align: center;
            margin-top: 20px;
            padding: 20px;
            background-color: #4CAF50;
            color: white;
        }
        button {
            background-color: #4CAF50;
            color: white;
            padding: 10px 20px;
            border: none;
            cursor: pointer;
        }
        button:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>

<header>
    <h1>Descubre tus Talentos y Habilidades</h1>
    <p>Un test para ayudarte a identificar tus talentos dados por Dios y cómo puedes desarrollarlos.</p>
</header>

<main>
    <section>
        <h2>Introducción</h2>
        <p>Dios ha puesto en cada uno de nosotros talentos únicos y habilidades especiales que nos hacen destacar. Este test te ayudará a identificar esos talentos y habilidades que puedes desarrollar para cumplir con el propósito que Dios tiene para tu vida.</p>
        <p><strong>¿Estás listo para descubrir el potencial que hay en ti? ¡Empecemos!</strong></p>
    </section>

    <section>
        <h2>Test de Autoevaluación</h2>
        <p>Responde a las siguientes preguntas con la mayor sinceridad posible:</p>

        <form id="talent-test">
            <div class="question">
                <h3>1. ¿Qué actividades disfrutas hacer en tu tiempo libre?</h3>
                <label><input type="radio" name="q1" value="a"> Dibujar, pintar o crear arte.</label><br>
                <label><input type="radio" name="q1" value="b"> Resolver problemas y puzzles.</label><br>
                <label><input type="radio" name="q1" value="c"> Ayudar a los demás y ser un buen oyente.</label><br>
                <label><input type="radio" name="q1" value="d"> Liderar equipos o proyectos.</label><br>
                <label><input type="radio" name="q1" value="e"> Investigar y aprender cosas nuevas.</label><br>
                <label><input type="radio" name="q1" value="f"> Tocar un instrumento, cantar o actuar.</label>
            </div>

            <div class="question">
                <h3>2. ¿Cómo te describirían tus amigos o familiares?</h3>
                <label><input type="radio" name="q2" value="a"> Creativo y original.</label><br>
                <label><input type="radio" name="q2" value="b"> Lógico y analítico.</label><br>
                <label><input type="radio" name="q2" value="c"> Empático y compasivo.</label><br>
                <label><input type="radio" name="q2" value="d"> Organizado y responsable.</label><br>
                <label><input type="radio" name="q2" value="e"> Curioso y explorador.</label><br>
                <label><input type="radio" name="q2" value="f"> Talentoso y apasionado en el arte o música.</label>
            </div>

            <div class="question">
                <h3>3. ¿Qué tipo de tareas disfrutas más en la escuela o en tu trabajo?</h3>
                <label><input type="radio" name="q3" value="a"> Proyectos artísticos o creativos.</label><br>
                <label><input type="radio" name="q3" value="b"> Resolución de problemas matemáticos o lógicos.</label><br>
                <label><input type="radio" name="q3" value="c"> Ayudar a compañeros o participar en actividades de voluntariado.</label><br>
                <label><input type="radio" name="q3" value="d"> Organizar eventos o liderar grupos de trabajo.</label><br>
                <label><input type="radio" name="q3" value="e"> Estudiar ciencia, historia o investigar.</label><br>
                <label><input type="radio" name="q3" value="f"> Participar en actividades de música, teatro o deportes.</label>
            </div>

            <div class="question">
                <h3>4. ¿Cuando enfrentas un desafío, cómo tiendes a resolverlo?</h3>
                <label><input type="radio" name="q4" value="a"> Busco una solución creativa o innovadora.</label><br>
                <label><input type="radio" name="q4" value="b"> Analizo todos los datos y pienso en las mejores opciones lógicas.</label><br>
                <label><input type="radio" name="q4" value="c"> Hablo con otros para entender sus sentimientos y obtener apoyo.</label><br>
                <label><input type="radio" name="q4" value="d"> Tomo la iniciativa y lidero a otros para resolverlo en equipo.</label><br>
                <label><input type="radio" name="q4" value="e"> Investigo y busco toda la información posible antes de actuar.</label><br>
                <label><input type="radio" name="q4" value="f"> Enfrento el desafío con pasión y dedicación, sin rendirme fácilmente.</label>
            </div>

            <div class="question">
                <h3>5. ¿Qué tipo de actividades te hacen sentir más vivo?</h3>
                <label><input type="radio" name="q5" value="a"> Crear algo nuevo, como un dibujo o una obra de arte.</label><br>
                <label><input type="radio" name="q5" value="b"> Resolver un problema complejo o descubrir algo nuevo.</label><br>
                <label><input type="radio" name="q5" value="c"> Ayudar a alguien en necesidad o escuchar a un amigo.</label><br>
                <label><input type="radio" name="q5" value="d"> Organizar o liderar una actividad o proyecto.</label><br>
                <label><input type="radio" name="q5" value="e"> Aprender sobre un tema nuevo o explorar un nuevo campo de conocimiento.</label><br>
                <label><input type="radio" name="q5" value="f"> Participar en una actividad artística, musical o deportiva.</label>
            </div>

            <button type="submit">Enviar y Ver Resultados</button>
        </form>
    </section>

    <section id="results" style="display:none;">
        <h2>Resultados</h2>
        <p id="result-text"></p>
    </section>

</main>

<footer>
    <p>© 2024 Descubre tus Talentos y Habilidades. Todos los derechos reservados.</p>
</footer>

<script>
    document.getElementById('talent-test').addEventListener('submit', function(event) {
        event.preventDefault();

        let q1 = document.querySelector('input[name="q1"]:checked').value;
        let q2 = document.querySelector('input[name="q2"]:checked').value;
        let q3 = document.querySelector('input[name="q3"]:checked').value;
        let q4 = document.querySelector('input[name="q4"]:checked').value;
        let q5 = document.querySelector('input[name="q5"]:checked').value;

        let answers = [q1, q2, q3, q4, q5];
        let counts = {a: 0, b: 0, c: 0, d: 0, e: 0, f: 0};

        answers.forEach(answer => {
            counts[answer]++;
        });

        let maxCount = Math.max(...Object.values(counts));
        let result = Object.keys(counts).find(key => counts[key] === maxCount);

        let resultText = "";
        switch(result) {
            case 'a':
                resultText = "Tu talento principal es creativo/artístico. Puedes desarrollarte en áreas como el arte, el &#8203;:contentReference[oaicite:0]{index=0}&#8203;
