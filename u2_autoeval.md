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
   <div id='block-12' style='padding: 10px;'>
    <label for='option-12' style=' padding: 5px; font-size: 2.5rem;'>
      <input type='radio' name='option' value='6' id='option-12' style='transform: scale(1.6); margin-right: 10px; vertical-align: middle; margin-top: -2px;' />
      B. Evitar medicamentos innecesarios como antieméticos o paracetamol</label>
    <span id='result-12'></span>
  </div>
   <div id='block-13' style='padding: 10px;'>
    <label for='option-13' style=' padding: 5px; font-size: 2.5rem;'>
      <input type='radio' name='option' value='1/3' id='option-13' style='transform: scale(1.6); margin-right: 10px; vertical-align: middle; margin-top: -2px;' />
      C. Hay fármacos específicos para el tratamiento de la hepatitis A</label>
    <span id='result-13'></span>
  </div>
  <div id='block-14' style='padding: 10px;'>
    <label for='option-14' style=' padding: 5px; font-size: 2.5rem;'>
      <input type='radio' name='option' value='1/6' id='option-14' style='transform: scale(1.6); margin-right: 10px; vertical-align: middle; margin-top: -2px;' />
      D. La insuficiencia hepática aguda no es el principal criterio de hospitalización</label>
    <span id='result-14'></span>
  </div>
  div id='block-14' style='padding: 10px;'>
    <label for='option-14' style=' padding: 5px; font-size: 2.5rem;'>
      <input type='radio' name='option' value='1/6' id='option-14' style='transform: scale(1.6); margin-right: 10px; vertical-align: middle; margin-top: -2px;' />
      E. La hidratación no es uno de los principales aspectos del tratamiento de la hepatitis A</label>
    <span id='result-14'></span>
  </div>
  <hr />
  <button type='button' onclick='displayAnswer1()' style='width: 100px; height: 40px; border-radius: 3px; background-color: lightblue; font-weight: 700;'>Submit</button>
</div>
<a id='showanswer1'></a>
<script>
  //    The function evaluates the answer and displays result
  function displayAnswer1() {
    if (document.getElementById('option-11').checked) {
      document.getElementById('block-11').style.border = '3px solid limegreen'
      document.getElementById('result-11').style.color = 'limegreen'
      document.getElementById('result-11').innerHTML = 'Correct!'
    }
    if (document.getElementById('option-12').checked) {
      document.getElementById('block-12').style.border = '3px solid red'
      document.getElementById('result-12').style.color = 'red'
      document.getElementById('result-12').innerHTML = 'Incorrect!'
      showCorrectAnswer1()
    }
    if (document.getElementById('option-13').checked) {
      document.getElementById('block-13').style.border = '3px solid red'
      document.getElementById('result-13').style.color = 'red'
      document.getElementById('result-13').innerHTML = 'Incorrect!'
      showCorrectAnswer1()
    }
    if (document.getElementById('option-14').checked) {
      document.getElementById('block-14').style.border = '3px solid red'
      document.getElementById('result-14').style.color = 'red'
      document.getElementById('result-14').innerHTML = 'Incorrect!'
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
































<hr>

<p><a href="index.html">Índice</a> | <a href="u1.html">Unidad anterior</a> | <a href="u3.html">Siguiente unidad</a></p>

<p>Oficina de Inteligencia e Información Sanitaria OIIS, EsSalud, Perú - 2024</p>
