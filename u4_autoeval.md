<html>
<head>
<title>Autoevaluación: Unidad 4</title>
</head>
<body>

<h1>Autoevaluación: Unidad 4</h1>
<p><i>Temas: Esquema de vacunación vigente. Sarampión. Enfermedades eruptivas infantiles. Tos ferina. Meningitis.</i></p>
<p><a href="index.html">Inicio</a> | <a href="u4.html">Unidad 4</a>

<div>
<h3>¿Cuál es el periodo de contagio de sarampión?</h3>
<p>Elige la respuesta correcta</p>
  <div id='block-11'>
    <label for='option-11'>
      <input type='radio' name='option' value='A' id='option-11'/>
      A. Desde 4 días antes hasta 5 días después de la aparición del exantema</label>
    <span id='result-11'></span>
  </div>
   <div id='block-12'>
    <label for='option-12'>
      <input type='radio' name='option' value='B' id='option-12'/>
      B. Hasta 14 días luego de la aparición del exantema</label>
    <span id='result-12'></span>
  </div>
   <div id='block-13'>
    <label for='option-13'>
      <input type='radio' name='option' value='C' id='option-13'/>
      C. No es contagioso</label>
    <span id='result-13'></span>
  </div>
  <div id='block-14'>
    <label for='option-14'>
      <input type='radio' name='option' value='D' id='option-14'/>
      D. Desde un día antes hasta un día después de la aparición del exantema</label>
    <span id='result-14'></span>
  </div>
  <div id='block-15'>
    <label for='option-15'>
      <input type='radio' name='option' value='E' id='option-15'/>
      E. Hasta que aparece el exantema</label>
    <span id='result-15'></span>
  </div>
  <br>
  <button type='button' onclick='displayAnswer1()' style='width: 100px; height: 40px; border-radius: 3px; background-color: lightblue; font-weight: 700;'>Enviar</button>
</div>
<script>
  //    The function evaluates the answer and displays result
  function displayAnswer1() {
    if (document.getElementById('option-11').checked) {
      document.getElementById('block-11').style.border = '3px solid limegreen'
      document.getElementById('result-11').style.color = 'limegreen'
      document.getElementById('result-11').innerHTML = '¡Correcto! &#128175; El periodo de contagio de sarampión es desde 4 días antes hasta 5 días después de la aparición del exantema. &#127775;'
      document.getElementById('block-12').style.border = 'initial';
      document.getElementById('result-12').style.color = 'initial';
      document.getElementById('result-12').innerHTML = '';
      document.getElementById('block-13').style.border = 'initial';
      document.getElementById('result-13').style.color = 'initial';
      document.getElementById('result-13').innerHTML = '';
      document.getElementById('block-14').style.border = 'initial';
      document.getElementById('result-14').style.color = 'initial';
      document.getElementById('result-14').innerHTML = '';
      document.getElementById('block-15').style.border = 'initial';
      document.getElementById('result-15').style.color = 'initial';
      document.getElementById('result-15').innerHTML = '';
    }
    if (document.getElementById('option-12').checked) {
      document.getElementById('block-12').style.border = '3px solid red'
      document.getElementById('result-12').style.color = 'red'
      document.getElementById('result-12').innerHTML = 'Intenta otra vez &#128552;'
      document.getElementById('block-11').style.border = 'initial';
      document.getElementById('result-11').style.color = 'initial';
      document.getElementById('result-11').innerHTML = '';
      document.getElementById('block-13').style.border = 'initial';
      document.getElementById('result-13').style.color = 'initial';
      document.getElementById('result-13').innerHTML = '';
      document.getElementById('block-14').style.border = 'initial';
      document.getElementById('result-14').style.color = 'initial';
      document.getElementById('result-14').innerHTML = '';
      document.getElementById('block-15').style.border = 'initial';
      document.getElementById('result-15').style.color = 'initial';
      document.getElementById('result-15').innerHTML = '';
    }
    if (document.getElementById('option-13').checked) {
      document.getElementById('block-13').style.border = '3px solid red'
      document.getElementById('result-13').style.color = 'red'
      document.getElementById('result-13').innerHTML = 'Intenta otra vez &#128552;'
      document.getElementById('block-11').style.border = 'initial';
      document.getElementById('result-11').style.color = 'initial';
      document.getElementById('result-11').innerHTML = '';
      document.getElementById('block-12').style.border = 'initial';
      document.getElementById('result-12').style.color = 'initial';
      document.getElementById('result-12').innerHTML = '';
      document.getElementById('block-14').style.border = 'initial';
      document.getElementById('result-14').style.color = 'initial';
      document.getElementById('result-14').innerHTML = '';
      document.getElementById('block-15').style.border = 'initial';
      document.getElementById('result-15').style.color = 'initial';
      document.getElementById('result-15').innerHTML = '';
    }
    if (document.getElementById('option-14').checked) {
      document.getElementById('block-14').style.border = '3px solid red'
      document.getElementById('result-14').style.color = 'red'
      document.getElementById('result-14').innerHTML = 'Intenta otra vez &#128552;'
      document.getElementById('block-11').style.border = 'initial';
      document.getElementById('result-11').style.color = 'initial';
      document.getElementById('result-11').innerHTML = '';
      document.getElementById('block-12').style.border = 'initial';
      document.getElementById('result-12').style.color = 'initial';
      document.getElementById('result-12').innerHTML = '';
      document.getElementById('block-13').style.border = 'initial';
      document.getElementById('result-13').style.color = 'initial';
      document.getElementById('result-13').innerHTML = '';
      document.getElementById('block-15').style.border = 'initial';
      document.getElementById('result-15').style.color = 'initial';
      document.getElementById('result-15').innerHTML = '';
    }
    if (document.getElementById('option-15').checked) {
      document.getElementById('block-15').style.border = '3px solid red'
      document.getElementById('result-15').style.color = 'red'
      document.getElementById('result-15').innerHTML = 'Intenta otra vez &#128552;'
      document.getElementById('block-11').style.border = 'initial';
      document.getElementById('result-11').style.color = 'initial';
      document.getElementById('result-11').innerHTML = '';
      document.getElementById('block-12').style.border = 'initial';
      document.getElementById('result-12').style.color = 'initial';
      document.getElementById('result-12').innerHTML = '';
      document.getElementById('block-13').style.border = 'initial';
      document.getElementById('result-13').style.color = 'initial';
      document.getElementById('result-13').innerHTML = '';
      document.getElementById('block-14').style.border = 'initial';
      document.getElementById('result-14').style.color = 'initial';
      document.getElementById('result-14').innerHTML = '';
    }
  }
</script>

<hr>

<div>
<h3>¿Cuál es la lesión característica del sarampión?</h3>
<p>Elige la respuesta correcta</p>
  <div id='block-21'>
    <label for='option-21'>
      <input type='radio' name='option' value='A' id='option-21'/>
      A. Exantema máculo papular no vesicular céfalo caudal</label>
    <span id='result-21'></span>
  </div>
   <div id='block-22'>
    <label for='option-22'>
      <input type='radio' name='option' value='B' id='option-22'/>
      B. Ronchas, pápulas, vesículas y túneles finos con leve descamación, y costras</label>
    <span id='result-22'></span>
  </div>
   <div id='block-23'>
    <label for='option-23'>
      <input type='radio' name='option' value='C' id='option-23'/>
      C. Exantema máculo papular no vesicular caudo cefálico</label>
    <span id='result-23'></span>
  </div>
  <div id='block-24'>
    <label for='option-24'>
      <input type='radio' name='option' value='D' id='option-24'/>
      D. Exantema máculo papular vesicular céfalo caudal</label>
    <span id='result-24'></span>
  </div>
  <div id='block-25'>
    <label for='option-25'>
      <input type='radio' name='option' value='E' id='option-25'/>
      E. Exantema pustular céfalo caudal</label>
    <span id='result-25'></span>
  </div>
  <br>
  <button type='button' onclick='displayAnswer2()' style='width: 100px; height: 40px; border-radius: 3px; background-color: lightblue; font-weight: 700;'>Enviar</button>
</div>
<script>
  //    The function evaluates the answer and displays result
  function displayAnswer2() {
    if (document.getElementById('option-21').checked) {
      document.getElementById('block-21').style.border = '3px solid limegreen'
      document.getElementById('result-21').style.color = 'limegreen'
      document.getElementById('result-21').innerHTML = '¡Correcto! &#128175; La lesión característica del sarampión es un exantema máculo papular no vesicular céfalo caudal. &#127775;'
      document.getElementById('block-22').style.border = 'initial';
      document.getElementById('result-22').style.color = 'initial';
      document.getElementById('result-22').innerHTML = '';
      document.getElementById('block-23').style.border = 'initial';
      document.getElementById('result-23').style.color = 'initial';
      document.getElementById('result-23').innerHTML = '';
      document.getElementById('block-24').style.border = 'initial';
      document.getElementById('result-24').style.color = 'initial';
      document.getElementById('result-24').innerHTML = '';
      document.getElementById('block-25').style.border = 'initial';
      document.getElementById('result-25').style.color = 'initial';
      document.getElementById('result-25').innerHTML = '';
    }
    if (document.getElementById('option-22').checked) {
      document.getElementById('block-22').style.border = '3px solid red'
      document.getElementById('result-22').style.color = 'red'
      document.getElementById('result-22').innerHTML = 'Intenta otra vez &#128552;'
      document.getElementById('block-21').style.border = 'initial';
      document.getElementById('result-21').style.color = 'initial';
      document.getElementById('result-21').innerHTML = '';
      document.getElementById('block-23').style.border = 'initial';
      document.getElementById('result-23').style.color = 'initial';
      document.getElementById('result-23').innerHTML = '';
      document.getElementById('block-24').style.border = 'initial';
      document.getElementById('result-24').style.color = 'initial';
      document.getElementById('result-24').innerHTML = '';
      document.getElementById('block-25').style.border = 'initial';
      document.getElementById('result-25').style.color = 'initial';
      document.getElementById('result-25').innerHTML = '';
    }
    if (document.getElementById('option-23').checked) {
      document.getElementById('block-23').style.border = '3px solid red'
      document.getElementById('result-23').style.color = 'red'
      document.getElementById('result-23').innerHTML = 'Intenta otra vez &#128552;'
      document.getElementById('block-21').style.border = 'initial';
      document.getElementById('result-21').style.color = 'initial';
      document.getElementById('result-21').innerHTML = '';
      document.getElementById('block-22').style.border = 'initial';
      document.getElementById('result-22').style.color = 'initial';
      document.getElementById('result-22').innerHTML = '';
      document.getElementById('block-24').style.border = 'initial';
      document.getElementById('result-24').style.color = 'initial';
      document.getElementById('result-24').innerHTML = '';
      document.getElementById('block-25').style.border = 'initial';
      document.getElementById('result-25').style.color = 'initial';
      document.getElementById('result-25').innerHTML = '';
    }
    if (document.getElementById('option-24').checked) {
      document.getElementById('block-24').style.border = '3px solid red'
      document.getElementById('result-24').style.color = 'red'
      document.getElementById('result-24').innerHTML = 'Intenta otra vez &#128552;'
      document.getElementById('block-21').style.border = 'initial';
      document.getElementById('result-21').style.color = 'initial';
      document.getElementById('result-21').innerHTML = '';
      document.getElementById('block-22').style.border = 'initial';
      document.getElementById('result-22').style.color = 'initial';
      document.getElementById('result-22').innerHTML = '';
      document.getElementById('block-23').style.border = 'initial';
      document.getElementById('result-23').style.color = 'initial';
      document.getElementById('result-23').innerHTML = '';
      document.getElementById('block-25').style.border = 'initial';
      document.getElementById('result-25').style.color = 'initial';
      document.getElementById('result-25').innerHTML = '';
    }
    if (document.getElementById('option-25').checked) {
      document.getElementById('block-25').style.border = '3px solid red'
      document.getElementById('result-25').style.color = 'red'
      document.getElementById('result-25').innerHTML = 'Intenta otra vez &#128552;'
      document.getElementById('block-21').style.border = 'initial';
      document.getElementById('result-21').style.color = 'initial';
      document.getElementById('result-21').innerHTML = '';
      document.getElementById('block-22').style.border = 'initial';
      document.getElementById('result-22').style.color = 'initial';
      document.getElementById('result-22').innerHTML = '';
      document.getElementById('block-23').style.border = 'initial';
      document.getElementById('result-23').style.color = 'initial';
      document.getElementById('result-23').innerHTML = '';
      document.getElementById('block-24').style.border = 'initial';
      document.getElementById('result-24').style.color = 'initial';
      document.getElementById('result-24').innerHTML = '';
    }
  }
</script>

<hr>

<div>
<h3>¿Cuál es el tratamiento de elección para tos convulsiva?</h3>
<p>Elige la respuesta correcta</p>
  <div id='block-31'>
    <label for='option-31'>
      <input type='radio' name='option' value='A' id='option-31'/>
      A. Eritromicina</label>
    <span id='result-31'></span>
  </div>
   <div id='block-32'>
    <label for='option-32'>
      <input type='radio' name='option' value='B' id='option-32'/>
      B. Sulfametoxazol-trimetoprim</label>
    <span id='result-32'></span>
  </div>
   <div id='block-33'>
    <label for='option-33'>
      <input type='radio' name='option' value='C' id='option-33'/>
      C. Azitromicina</label>
    <span id='result-33'></span>
  </div>
  <div id='block-34'>
    <label for='option-34'>
      <input type='radio' name='option' value='D' id='option-34'/>
      D. Aztreonam</label>
    <span id='result-34'></span>
  </div>
  <div id='block-35'>
    <label for='option-35'>
      <input type='radio' name='option' value='E' id='option-35'/>
      E. Dicloxacilina</label>
    <span id='result-35'></span>
  </div>
  <br>
  <button type='button' onclick='displayAnswer3()' style='width: 100px; height: 40px; border-radius: 3px; background-color: lightblue; font-weight: 700;'>Enviar</button>
</div>
<script>
  //    The function evaluates the answer and displays result
  function displayAnswer3() {
    if (document.getElementById('option-31').checked) {
      document.getElementById('block-31').style.border = '3px solid red'
      document.getElementById('result-31').style.color = 'red'
      document.getElementById('result-31').innerHTML = 'Intenta otra vez &#128552;'
      document.getElementById('block-32').style.border = 'initial';
      document.getElementById('result-32').style.color = 'initial';
      document.getElementById('result-32').innerHTML = '';
      document.getElementById('block-33').style.border = 'initial';
      document.getElementById('result-33').style.color = 'initial';
      document.getElementById('result-33').innerHTML = '';
      document.getElementById('block-34').style.border = 'initial';
      document.getElementById('result-34').style.color = 'initial';
      document.getElementById('result-34').innerHTML = '';
      document.getElementById('block-35').style.border = 'initial';
      document.getElementById('result-35').style.color = 'initial';
      document.getElementById('result-35').innerHTML = '';
    }
    if (document.getElementById('option-32').checked) {
      document.getElementById('block-32').style.border = '3px solid red'
      document.getElementById('result-32').style.color = 'red'
      document.getElementById('result-32').innerHTML = 'Intenta otra vez &#128552;'
      document.getElementById('block-31').style.border = 'initial';
      document.getElementById('result-31').style.color = 'initial';
      document.getElementById('result-31').innerHTML = '';
      document.getElementById('block-33').style.border = 'initial';
      document.getElementById('result-33').style.color = 'initial';
      document.getElementById('result-33').innerHTML = '';
      document.getElementById('block-34').style.border = 'initial';
      document.getElementById('result-34').style.color = 'initial';
      document.getElementById('result-34').innerHTML = '';
      document.getElementById('block-35').style.border = 'initial';
      document.getElementById('result-35').style.color = 'initial';
      document.getElementById('result-35').innerHTML = '';
    }
    if (document.getElementById('option-33').checked) {
      document.getElementById('block-33').style.border = '3px solid limegreen'
      document.getElementById('result-33').style.color = 'limegreen'
      document.getElementById('result-33').innerHTML = '¡Correcto! &#128175; El fármaco de elección es azitromicina. La eritromicina es otro fármaco recomendado, pero no en menores de un mes, porque se asocia a estenosis pilórica. SMX/TMP es un fármaco alternativo, pero contraindicado en lactantes menores de 2 meses por el riesgo de kernícterus. &#127775;'
      document.getElementById('block-31').style.border = 'initial';
      document.getElementById('result-31').style.color = 'initial';
      document.getElementById('result-31').innerHTML = '';
      document.getElementById('block-32').style.border = 'initial';
      document.getElementById('result-32').style.color = 'initial';
      document.getElementById('result-32').innerHTML = '';
      document.getElementById('block-34').style.border = 'initial';
      document.getElementById('result-34').style.color = 'initial';
      document.getElementById('result-34').innerHTML = '';
      document.getElementById('block-35').style.border = 'initial';
      document.getElementById('result-35').style.color = 'initial';
      document.getElementById('result-35').innerHTML = '';
    }
    if (document.getElementById('option-34').checked) {
      document.getElementById('block-34').style.border = '3px solid red'
      document.getElementById('result-34').style.color = 'red'
      document.getElementById('result-34').innerHTML = 'Intenta otra vez &#128552;'
      document.getElementById('block-31').style.border = 'initial';
      document.getElementById('result-31').style.color = 'initial';
      document.getElementById('result-31').innerHTML = '';
      document.getElementById('block-32').style.border = 'initial';
      document.getElementById('result-32').style.color = 'initial';
      document.getElementById('result-32').innerHTML = '';
      document.getElementById('block-33').style.border = 'initial';
      document.getElementById('result-33').style.color = 'initial';
      document.getElementById('result-33').innerHTML = '';
      document.getElementById('block-35').style.border = 'initial';
      document.getElementById('result-35').style.color = 'initial';
      document.getElementById('result-35').innerHTML = '';
    }
    if (document.getElementById('option-35').checked) {
      document.getElementById('block-35').style.border = '3px solid red'
      document.getElementById('result-35').style.color = 'red'
      document.getElementById('result-35').innerHTML = 'Intenta otra vez &#128552;'
      document.getElementById('block-31').style.border = 'initial';
      document.getElementById('result-31').style.color = 'initial';
      document.getElementById('result-31').innerHTML = '';
      document.getElementById('block-32').style.border = 'initial';
      document.getElementById('result-32').style.color = 'initial';
      document.getElementById('result-32').innerHTML = '';
      document.getElementById('block-33').style.border = 'initial';
      document.getElementById('result-33').style.color = 'initial';
      document.getElementById('result-33').innerHTML = '';
      document.getElementById('block-34').style.border = 'initial';
      document.getElementById('result-34').style.color = 'initial';
      document.getElementById('result-34').innerHTML = '';
    }
  }
</script>

<hr>

<p><a href="index.html">Índice</a> | <a href="u1.html">Unidad anterior</a> | <a href="u5.html">Siguiente unidad</a></p>

<p>Oficina de Inteligencia e Información Sanitaria OIIS, EsSalud, Perú - 2024</p>
