<html>
<head>
<title>Autoevaluación: Unidad 2</title>
</head>
<body>

<h1>Autoevaluación: Unidad 2</h1>
<p><i>Temas: Enfoque diagnóstico del síndrome febril. Dengue. Chikungunya. Fiebre amarilla. Zika. Bartonelosis. Leishmaniasis. Malaria. Principios de control vectorial para la prevención de arbovirosis y otras enfermedades metaxénicas.</i></p>
<p><a href="index.html">Índice</a> | <a href="u2.html">Unidad 2</a>

<div>
  <h3>¿Cuál de las siguientes opciones es correcta en el tratamiento de la hepatitis A?</h3>
  <p>Elige la respuesta correcta</p>
   <div id='block-11'>
    <label for='option-11'>
      <input type='radio' name='option' value='6/24' id='option-11'/>
      A. Se debe hospitalizar todos los casos</label>
    <span id='result-11'></span>
  </div>
   <div id='block-12'>
    <label for='option-12'>
      <input type='radio' name='option' value='6' id='option-12'/>
      B. Evitar medicamentos innecesarios como antieméticos o paracetamol</label>
    <span id='result-12'></span>
  </div>
   <div id='block-13'>
    <label for='option-13'>
      <input type='radio' name='option' value='1/3' id='option-13'/>
      C. Hay fármacos específicos para el tratamiento de la hepatitis A</label>
    <span id='result-13'></span>
  </div>
  <div id='block-14'>
    <label for='option-14'>
      <input type='radio' name='option' value='1/6' id='option-14'/>
      D. La insuficiencia hepática aguda no es el principal criterio de hospitalización</label>
    <span id='result-14'></span>
  </div>
  <div id='block-15'>
    <label for='option-15'>
      <input type='radio' name='option' value='1/6' id='option-15'/>
      E. La hidratación no es uno de los principales aspectos del tratamiento de la hepatitis A</label>
    <span id='result-15'></span>
  </div>
  <hr />
  <button type='button' onclick='displayAnswer1()' style='width: 100px; height: 40px; border-radius: 3px; background-color: lightblue; font-weight: 700;'>Enviar</button>
</div>
<a id='showanswer1'></a>
<script>
  //    The function evaluates the answer and displays result
  function displayAnswer1() {
    if (document.getElementById('option-11').checked) {
      document.getElementById('block-11').style.border = '3px solid red'
      document.getElementById('result-11').style.color = 'red'
      document.getElementById('result-11').innerHTML = 'Intenta otra vez'
    }
    if (document.getElementById('option-12').checked) {
      document.getElementById('block-12').style.border = '3px solid limegreen'
      document.getElementById('result-12').style.color = 'limegreen'
      document.getElementById('result-12').innerHTML = '¡Correcto! En el tratamiento de la hepatitis A, la hidratación es un aspecto clave. Es importante monitorizar la función hepática para detectar insuficiencia hepática aguda, porque es el principal criterio de hospitalización. Se debe evitar medicamentos innecesarios como antieméticos o paracetamol. No hay fármacos específicos para el tratamiento de la hepatitis A.'
      showCorrectAnswer1()
    }
    if (document.getElementById('option-13').checked) {
      document.getElementById('block-13').style.border = '3px solid red'
      document.getElementById('result-13').style.color = 'red'
      document.getElementById('result-13').innerHTML = 'Intenta otra vez'
      showCorrectAnswer1()
    }
    if (document.getElementById('option-14').checked) {
      document.getElementById('block-14').style.border = '3px solid red'
      document.getElementById('result-14').style.color = 'red'
      document.getElementById('result-14').innerHTML = 'Intenta otra vez'
      showCorrectAnswer1()
    }
    if (document.getElementById('option-15').checked) {
      document.getElementById('block-15').style.border = '3px solid red'
      document.getElementById('result-15').style.color = 'red'
      document.getElementById('result-15').innerHTML = 'Intenta otra vez'
      showCorrectAnswer1()
    }
  }
  // the functon displays the link to the correct answer
  function showCorrectAnswer1() {
    let showAnswer1 = document.createElement('p')
    showAnswer1.innerHTML = 'Show Corrent Answer'
    showAnswer1.style.position = 'relative'
    showAnswer1.style.top = '-180px'
    showAnswer1.style.fontSize = '1.75rem'
    document.getElementById('showanswer1').appendChild(showAnswer1)
    showAnswer1.addEventListener('click', () => {
      document.getElementById('block-11').style.border = '3px solid limegreen'
      document.getElementById('result-11').style.color = 'limegreen'
      document.getElementById('result-11').innerHTML = 'Correct!'
      document.getElementById('showanswer1').removeChild(showAnswer1)
    })
  }
</script>

<h2>ChatGPT</h2>

<form action="submit_exam.php" method="post">
    <fieldset>
        <legend>¿Cuál de las siguientes opciones es correcta en el tratamiento de la hepatitis A?</legend>
        <label>
            <input type="radio" name="q1" value="a"> a) Se debe hospitalizar todos los casos
        </label>
        <label>
            <input type="radio" name="q1" value="b"> b) Evitar medicamentos innecesarios como antieméticos o paracetamol
        </label>
        <label>
            <input type="radio" name="q1" value="c"> c) Hay fármacos específicos para el tratamiento de la hepatitis A
        </label>
        <label>
            <input type="radio" name="q1" value="d"> d) La insuficiencia hepática aguda no es el principal criterio de hospitalización
        </label>
        <label>
            <input type="radio" name="q1" value="e"> e) La hidratación no es uno de los principales aspectos del tratamiento de la hepatitis A
        </label>
    </fieldset>
    <fieldset>
        <legend>Question 2: What is the largest mammal on Earth?</legend>
        <label>
            <input type="radio" name="q2" value="a"> a) Elephant
        </label>
        <label>
            <input type="radio" name="q2" value="b"> b) Blue Whale
        </label>
        <label>
            <input type="radio" name="q2" value="c"> c) Giraffe
        </label>
    </fieldset>
    <input type="submit" value="Enviar">
<button type="button" onclick="submitForm()">Submit Exam</button>
</form>

<div id="results" class="hidden">
    <h2>Results</h2>
    <p id="resultQ1"></p>
    <p id="resultQ2"></p>
    <!-- Add more result paragraphs as needed -->
</div>

<script>
    function submitForm() {
        // Get the form element
        var form = document.getElementById('examForm');

        // Get the selected answers
        var q1Answer = getSelectedAnswer(form.elements['q1']);
        var q2Answer = getSelectedAnswer(form.elements['q2']);

        // Display results
        document.getElementById('resultQ1').innerHTML = 'Pregunta 1: Respondiste ' + q1Answer + '. La respuesta correcta es b) Evitar medicamentos innecesarios como antieméticos o paracetamol. En el tratamiento de la hepatitis A, la hidratación es un aspecto clave. Es importante monitorizar la función hepática para detectar insuficiencia hepática aguda, porque es el principal criterio de hospitalización. Se debe evitar medicamentos innecesarios como antieméticos o paracetamol. No hay fármacos específicos para el tratamiento de la hepatitis A.';
        document.getElementById('resultQ2').innerHTML = 'Pregunta 1: Respondiste ' + q2Answer + '. La respuesta correcta es d) 4 días después de la infección. Las pruebas de anticuerpo para detección de dengue son positivas desde 4 días después de la infección. ';

        // Show the results div
        document.getElementById('results').classList.remove('hidden');
    }

    function getSelectedAnswer(radioGroup) {
        for (var i = 0; i < radioGroup.length; i++) {
            if (radioGroup[i].checked) {
                return radioGroup[i].value;
            }
        }
        return 'No has seleccionado ninguna respuesta.';
    }
</script>




























<hr>

<p><a href="index.html">Índice</a> | <a href="u1.html">Unidad anterior</a> | <a href="u3.html">Siguiente unidad</a></p>

<p>Oficina de Inteligencia e Información Sanitaria OIIS, EsSalud, Perú - 2024</p>
