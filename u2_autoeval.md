<html>
<head>
<title>Autoevaluación: Unidad 2</title>
</head>
<body>

<h1>Autoevaluación: Unidad 2</h1>
<p><i>Temas: Enfoque diagnóstico del síndrome febril. Dengue. Chikungunya. Fiebre amarilla. Zika. Bartonelosis. Leishmaniasis. Malaria. Principios de control vectorial para la prevención de arbovirosis y otras enfermedades metaxénicas.</i></p>
<p><a href="index.html">Inicio</a> | <a href="u2.html">Unidad 2</a>

<div>
<h3>¿Cuáles de los siguientes pueden ser criaderos de <i>Aedes aegypti</i>?</h3>
<p>Marca las 4 alternativas correctas</p>
  <div id='block-151'>
    <label for='option-151'>
      <input type='checkbox' name='option' value='A' id='option-151'/>
      A. Recipientes y bebederos con agua sin tapa</label>
    <span id='result-151'></span>
  </div>
   <div id='block-152'>
    <label for='option-152'>
      <input type='checkbox' name='option' value='B' id='option-152'/>
      B. Floreros con arena húmeda</label>
    <span id='result-152'></span>
  </div>
   <div id='block-153'>
    <label for='option-153'>
      <input type='checkbox' name='option' value='C' id='option-153'/>
      C. Llantas con agua de lluvia</label>
    <span id='result-153'></span>
  </div>
  <div id='block-154'>
    <label for='option-154'>
      <input type='checkbox' name='option' value='D' id='option-154'/>
      D. Tanques de agua sin tapa</label>
    <span id='result-154'></span>
  </div>
  <div id='block-155'>
    <label for='option-155'>
      <input type='checkbox' name='option' value='E' id='option-155'/>
      E. Piscinas con agua sin cubierta</label>
    <span id='result-155'></span>
  </div>
  <div id='result-container-15'></div>
  <br>
  <button type='button' onclick='display15()' style='width: 100px; height: 40px; border-radius: 3px; background-color: lightblue; font-weight: 700;'>Enviar</button>
</div>
<script>
var textDisplayed = false; // Declare textDisplayed globally
function display15() {
    displayAnswer15();
    displayText15();
}  
  //    The function evaluates the answer and displays result
  function displayAnswer15() {
    if (document.getElementById('option-151').checked) {
      document.getElementById('block-151').style.border = '3px solid limegreen'
      document.getElementById('result-151').style.color = 'limegreen'
      document.getElementById('result-151').innerHTML = '¡Correcto! &#127775;'
    } else {
      document.getElementById('block-151').style.border = 'initial';
      document.getElementById('result-151').style.color = 'initial';
      document.getElementById('result-151').innerHTML = '';
    }
    if (document.getElementById('option-152').checked) {
      document.getElementById('block-152').style.border = '3px solid red'
      document.getElementById('result-152').style.color = 'red'
      document.getElementById('result-152').innerHTML = 'Incorrecto &#128552;'
    } else {
      document.getElementById('block-152').style.border = 'initial';
      document.getElementById('result-152').style.color = 'initial';
      document.getElementById('result-152').innerHTML = '';
    }
    if (document.getElementById('option-153').checked) {
      document.getElementById('block-153').style.border = '3px solid limegreen'
      document.getElementById('result-153').style.color = 'limegreen'
      document.getElementById('result-153').innerHTML = '¡Correcto! &#127775;'
    } else {
      document.getElementById('block-153').style.border = 'initial';
      document.getElementById('result-153').style.color = 'initial';
      document.getElementById('result-153').innerHTML = '';
    }
    if (document.getElementById('option-154').checked) {
      document.getElementById('block-154').style.border = '3px solid limegreen'
      document.getElementById('result-154').style.color = 'limegreen'
      document.getElementById('result-154').innerHTML = '¡Correcto! &#127775;'
    } else {
      document.getElementById('block-154').style.border = 'initial';
      document.getElementById('result-154').style.color = 'initial';
      document.getElementById('result-154').innerHTML = '';
    }
    if (document.getElementById('option-155').checked) {
      document.getElementById('block-155').style.border = '3px solid limegreen'
      document.getElementById('result-155').style.color = 'limegreen'
      document.getElementById('result-155').innerHTML = '¡Correcto! &#127775;'
    } else {
      document.getElementById('block-155').style.border = 'initial';
      document.getElementById('result-155').style.color = 'initial';
      document.getElementById('result-155').innerHTML = '';
    }
  }
  //    The function evaluates the answer and displays an explanatory text
function displayText15() {
  if (document.getElementById('option-151').checked && 
      document.getElementById('option-153').checked && 
      document.getElementById('option-154').checked && 
      document.getElementById('option-155').checked) {
    // Check if the div already exists
    if (!document.getElementById('block-A15')) {
      // Create a new div element
      var newDiv = document.createElement('div');
      // Set the id and style properties for the new div
      newDiv.id = 'block-A15';
      newDiv.style.border = '3px solid limegreen';
      newDiv.style.color = 'limegreen';
      // Set the inner HTML content for the new div
      newDiv.innerHTML = "<label>La hembra del mosquito <i>Aedes aegypti</i> coloca sus huevos en reservorios de agua. Por eso es importante mantenerlos cerrados con tapa, y usar arena húmeda en floreros en lugar de agua</label>";
      // Append the new div to the result-container-15
      document.getElementById('result-container-15').appendChild(newDiv);
    }
  }
}
</script>

<hr>

<div>
<h3>¿Qué enunciados son verdaderos sobre el mosquito <i>Aedes aegypti</i>?</h3>
<p>Marca todas las alternativas correctas:</p>
  <div id='block-161'>
    <label for='option-161'>
      <input type='checkbox' name='option' value='A' id='option-161'/>
      A. Use ropa de manga larga y pantalones para prevenir su picadura</label>
    <span id='result-161'></span>
  </div>
   <div id='block-162'>
    <label for='option-162'>
      <input type='checkbox' name='option' value='B' id='option-162'/>
      B. Evite usar perfume con olor a flores para prevenir la picadura de <i>Aedes</i></label>
    <span id='result-162'></span>
  </div>
   <div id='block-163'>
    <label for='option-163'>
      <input type='checkbox' name='option' value='C' id='option-163'/>
      C. Use ropa de color claro para prevenir la picadura de <i>Aedes aegypti</i></label>
    <span id='result-163'></span>
  </div>
  <div id='block-164'>
    <label for='option-164'>
      <input type='checkbox' name='option' value='D' id='option-164'/>
      D. Proteja cunas de bebés y camas con mosquiteros en zonas con muchos mosquitos</label>
    <span id='result-164'></span>
  </div>
  <div id='block-165'>
    <label for='option-165'>
      <input type='checkbox' name='option' value='E' id='option-165'/>
      E. El mosquito <i>Aedes aegypti</i> puede transmitir dengue, chikungunya y Zika en una sola picadura</label>
    <span id='result-165'></span>
  </div>
  <div id='result-container-16'></div>
  <br>
  <button type='button' onclick='display16()' style='width: 100px; height: 40px; border-radius: 3px; background-color: lightblue; font-weight: 700;'>Enviar</button>
</div>
<script>
var textDisplayed = false; // Declare textDisplayed globally
function display16() {
    displayAnswer16();
    displayText16();
}  
  //    The function evaluates the answer and displays result
  function displayAnswer16() {
    if (document.getElementById('option-161').checked) {
      document.getElementById('block-161').style.border = '3px solid limegreen'
      document.getElementById('result-161').style.color = 'limegreen'
      document.getElementById('result-161').innerHTML = '¡Correcto! &#127775;'
    } else {
      document.getElementById('block-161').style.border = 'initial';
      document.getElementById('result-161').style.color = 'initial';
      document.getElementById('result-161').innerHTML = '';
    }
    if (document.getElementById('option-162').checked) {
      document.getElementById('block-162').style.border = '3px solid limegreen'
      document.getElementById('result-162').style.color = 'limegreen'
      document.getElementById('result-162').innerHTML = '¡Correcto! &#127775;'
    } else {
      document.getElementById('block-162').style.border = 'initial';
      document.getElementById('result-162').style.color = 'initial';
      document.getElementById('result-162').innerHTML = '';
    }
    if (document.getElementById('option-163').checked) {
      document.getElementById('block-163').style.border = '3px solid limegreen'
      document.getElementById('result-163').style.color = 'limegreen'
      document.getElementById('result-163').innerHTML = '¡Correcto! &#127775;'
    } else {
      document.getElementById('block-163').style.border = 'initial';
      document.getElementById('result-163').style.color = 'initial';
      document.getElementById('result-163').innerHTML = '';
    }
    if (document.getElementById('option-164').checked) {
      document.getElementById('block-164').style.border = '3px solid limegreen'
      document.getElementById('result-164').style.color = 'limegreen'
      document.getElementById('result-164').innerHTML = '¡Correcto! &#127775;'
    } else {
      document.getElementById('block-164').style.border = 'initial';
      document.getElementById('result-164').style.color = 'initial';
      document.getElementById('result-164').innerHTML = '';
    }
    if (document.getElementById('option-165').checked) {
      document.getElementById('block-165').style.border = '3px solid limegreen'
      document.getElementById('result-165').style.color = 'limegreen'
      document.getElementById('result-165').innerHTML = '¡Correcto! &#127775;'
    } else {
      document.getElementById('block-165').style.border = 'initial';
      document.getElementById('result-165').style.color = 'initial';
      document.getElementById('result-165').innerHTML = '';
    }
  }
  //    The function evaluates the answer and displays an explanatory text
function displayText16() {
  if (document.getElementById('option-161').checked && 
      document.getElementById('option-163').checked && 
      document.getElementById('option-164').checked && 
      document.getElementById('option-165').checked) {
    // Check if the div already exists
    if (!document.getElementById('block-A16')) {
      // Create a new div element
      var newDiv = document.createElement('div');
      // Set the id and style properties for the new div
      newDiv.id = 'block-A16';
      newDiv.style.border = '3px solid limegreen';
      newDiv.style.color = 'limegreen';
      // Set the inner HTML content for the new div
      newDiv.innerHTML = "<label>Todas son correctas.</label>";
      // Append the new div to the result-container-16
      document.getElementById('result-container-16').appendChild(newDiv);
    }
  }
}
</script>

<hr>

<div>
<h3>¿Cuáles son los principales problemas de salud que se presentan después de una inundación?</h3>
<p>Marca todas las alternativas correctas:</p>
  <div id='block-171'>
    <label for='option-171'>
      <input type='checkbox' name='option' value='A' id='option-171'/>
      A. Enfermedades diarreicas</label>
    <span id='result-171'></span>
  </div>
   <div id='block-172'>
    <label for='option-172'>
      <input type='checkbox' name='option' value='B' id='option-172'/>
      B. Enfermedades transmitidas por vectores</label>
    <span id='result-172'></span>
  </div>
   <div id='block-173'>
    <label for='option-173'>
      <input type='checkbox' name='option' value='C' id='option-173'/>
      C. Infecciones cutáneas</label>
    <span id='result-173'></span>
  </div>
  <div id='block-174'>
    <label for='option-174'>
      <input type='checkbox' name='option' value='D' id='option-174'/>
      D. Infecciones respiratorias</label>
    <span id='result-174'></span>
  </div>
  <div id='block-175'>
    <label for='option-175'>
      <input type='checkbox' name='option' value='E' id='option-175'/>
      E. Enfermedades reumatológicas</label>
    <span id='result-175'></span>
  </div>
  <div id='result-container-17'></div>
  <br>
  <button type='button' onclick='display17()' style='width: 100px; height: 40px; border-radius: 3px; background-color: lightblue; font-weight: 700;'>Enviar</button>
</div>
<script>
var textDisplayed = false; // Declare textDisplayed globally
function display17() {
    displayAnswer17();
    displayText17();
}  
  //    The function evaluates the answer and displays result
  function displayAnswer17() {
    if (document.getElementById('option-171').checked) {
      document.getElementById('block-171').style.border = '3px solid limegreen'
      document.getElementById('result-171').style.color = 'limegreen'
      document.getElementById('result-171').innerHTML = '¡Correcto! &#127775;'
    } else {
      document.getElementById('block-171').style.border = 'initial';
      document.getElementById('result-171').style.color = 'initial';
      document.getElementById('result-171').innerHTML = '';
    }
    if (document.getElementById('option-172').checked) {
      document.getElementById('block-172').style.border = '3px solid limegreen'
      document.getElementById('result-172').style.color = 'limegreen'
      document.getElementById('result-172').innerHTML = '¡Correcto! &#127775;'
    } else {
      document.getElementById('block-172').style.border = 'initial';
      document.getElementById('result-172').style.color = 'initial';
      document.getElementById('result-172').innerHTML = '';
    }
    if (document.getElementById('option-173').checked) {
      document.getElementById('block-173').style.border = '3px solid limegreen'
      document.getElementById('result-173').style.color = 'limegreen'
      document.getElementById('result-173').innerHTML = '¡Correcto! &#127775;'
    } else {
      document.getElementById('block-173').style.border = 'initial';
      document.getElementById('result-173').style.color = 'initial';
      document.getElementById('result-173').innerHTML = '';
    }
    if (document.getElementById('option-174').checked) {
      document.getElementById('block-174').style.border = '3px solid limegreen'
      document.getElementById('result-174').style.color = 'limegreen'
      document.getElementById('result-174').innerHTML = '¡Correcto! &#127775;'
    } else {
      document.getElementById('block-174').style.border = 'initial';
      document.getElementById('result-174').style.color = 'initial';
      document.getElementById('result-174').innerHTML = '';
    }
    if (document.getElementById('option-175').checked) {
      document.getElementById('block-175').style.border = '3px solid red'
      document.getElementById('result-175').style.color = 'red'
      document.getElementById('result-175').innerHTML = 'Incorrecto &#128552;'
    } else {
      document.getElementById('block-175').style.border = 'initial';
      document.getElementById('result-175').style.color = 'initial';
      document.getElementById('result-175').innerHTML = '';
    }
  }
  //    The function evaluates the answer and displays an explanatory text
function displayText17() {
  if (document.getElementById('option-171').checked && 
      document.getElementById('option-172').checked && 
      document.getElementById('option-173').checked && 
      document.getElementById('option-174').checked && 
      document.getElementById('option-175').checked) {
    // Check if the div already exists
    if (!document.getElementById('block-A17')) {
      // Create a new div element
      var newDiv = document.createElement('div');
      // Set the id and style properties for the new div
      newDiv.id = 'block-A17';
      newDiv.style.border = '3px solid limegreen';
      newDiv.style.color = 'limegreen';
      // Set the inner HTML content for the new div
      newDiv.innerHTML = "<label>Los principales problemas de salud que se presentan después de una inundación son: enfermedades diarreicas, enfermedades transmitidas por vectores, infecciones cutáneas e infecciones respiratorias.</label>";
      // Append the new div to the result-container-17
      document.getElementById('result-container-17').appendChild(newDiv);
    }
  }
}
</script>

<hr>

<div>
<h3>¿Cuál de los siguientes es criterio para dengue grave?</h3>
<p>Marca todas las alternativas correctas:</p>
  <div id='block-181'>
    <label for='option-181'>
      <input type='checkbox' name='option' value='A' id='option-181'/>
      A. Shock</label>
    <span id='result-181'></span>
  </div>
   <div id='block-182'>
    <label for='option-182'>
      <input type='checkbox' name='option' value='B' id='option-182'/>
      B. Distrés respiratorio con acumulación de fluidos</label>
    <span id='result-182'></span>
  </div>
   <div id='block-183'>
    <label for='option-183'>
      <input type='checkbox' name='option' value='C' id='option-183'/>
      C. Sangrado severo</label>
    <span id='result-183'></span>
  </div>
  <div id='block-184'>
    <label for='option-184'>
      <input type='checkbox' name='option' value='D' id='option-184'/>
      D. Compromiso orgánico severo: TGO/TGP > 1000 UI/L</label>
    <span id='result-184'></span>
  </div>
  <div id='block-185'>
    <label for='option-185'>
      <input type='checkbox' name='option' value='E' id='option-185'/>
      E. Fiebre</label>
    <span id='result-185'></span>
  </div>
    <div id='block-186'>
    <label for='option-186'>
      <input type='checkbox' name='option' value='E' id='option-186'/>
      F. Alteración del estado de conciencia</label>
    <span id='result-186'></span>
  </div>
    <div id='block-187'>
    <label for='option-187'>
      <input type='checkbox' name='option' value='E' id='option-187'/>
      G. Disfunción sistémica</label>
    <span id='result-187'></span>
  </div>
  <div id='result-container-18'></div>
  <br>
  <button type='button' onclick='display18()' style='width: 100px; height: 40px; border-radius: 3px; background-color: lightblue; font-weight: 700;'>Enviar</button>
</div>
<script>
var textDisplayed = false; // Declare textDisplayed globally
function display18() {
    displayAnswer18();
    displayText18();
}  
  //    The function evaluates the answer and displays result
  function displayAnswer18() {
    if (document.getElementById('option-181').checked) {
      document.getElementById('block-181').style.border = '3px solid limegreen'
      document.getElementById('result-181').style.color = 'limegreen'
      document.getElementById('result-181').innerHTML = '¡Correcto! &#127775;'
    } else {
      document.getElementById('block-181').style.border = 'initial';
      document.getElementById('result-181').style.color = 'initial';
      document.getElementById('result-181').innerHTML = '';
    }
    if (document.getElementById('option-182').checked) {
      document.getElementById('block-182').style.border = '3px solid limegreen'
      document.getElementById('result-182').style.color = 'limegreen'
      document.getElementById('result-182').innerHTML = '¡Correcto! &#127775;'
    } else {
      document.getElementById('block-182').style.border = 'initial';
      document.getElementById('result-182').style.color = 'initial';
      document.getElementById('result-182').innerHTML = '';
    }
    if (document.getElementById('option-183').checked) {
      document.getElementById('block-183').style.border = '3px solid limegreen'
      document.getElementById('result-183').style.color = 'limegreen'
      document.getElementById('result-183').innerHTML = '¡Correcto! &#127775;'
    } else {
      document.getElementById('block-183').style.border = 'initial';
      document.getElementById('result-183').style.color = 'initial';
      document.getElementById('result-183').innerHTML = '';
    }
    if (document.getElementById('option-184').checked) {
      document.getElementById('block-184').style.border = '3px solid limegreen'
      document.getElementById('result-184').style.color = 'limegreen'
      document.getElementById('result-184').innerHTML = '¡Correcto! &#127775;'
    } else {
      document.getElementById('block-184').style.border = 'initial';
      document.getElementById('result-184').style.color = 'initial';
      document.getElementById('result-184').innerHTML = '';
    }
    if (document.getElementById('option-185').checked) {
      document.getElementById('block-185').style.border = '3px solid red'
      document.getElementById('result-185').style.color = 'red'
      document.getElementById('result-185').innerHTML = 'Incorrecto &#128552;'
    } else {
      document.getElementById('block-185').style.border = 'initial';
      document.getElementById('result-185').style.color = 'initial';
      document.getElementById('result-185').innerHTML = '';
    }
    if (document.getElementById('option-186').checked) {
      document.getElementById('block-186').style.border = '3px solid limegreen'
      document.getElementById('result-186').style.color = 'limegreen'
      document.getElementById('result-186').innerHTML = '¡Correcto! &#127775;'
    } else {
      document.getElementById('block-186').style.border = 'initial';
      document.getElementById('result-186').style.color = 'initial';
      document.getElementById('result-186').innerHTML = '';
    }
    if (document.getElementById('option-187').checked) {
      document.getElementById('block-187').style.border = '3px solid limegreen'
      document.getElementById('result-187').style.color = 'limegreen'
      document.getElementById('result-187').innerHTML = '¡Correcto! &#127775;'
    } else {
      document.getElementById('block-187').style.border = 'initial';
      document.getElementById('result-187').style.color = 'initial';
      document.getElementById('result-187').innerHTML = '';
    }
  }
  //    The function evaluates the answer and displays an explanatory text
function displayText18() {
  if (document.getElementById('option-181').checked && 
      document.getElementById('option-182').checked && 
      document.getElementById('option-183').checked && 
      document.getElementById('option-184').checked && 
      document.getElementById('option-186').checked && 
      document.getElementById('option-187').checked) {
    // Check if the div already exists
    if (!document.getElementById('block-A18')) {
      // Create a new div element
      var newDiv = document.createElement('div');
      // Set the id and style properties for the new div
      newDiv.id = 'block-A18';
      newDiv.style.border = '3px solid limegreen';
      newDiv.style.color = 'limegreen';
      // Set the inner HTML content for the new div
      newDiv.innerHTML = "<label>Los criterios para dengue grave son: shock, distrés respiratorio con acumulación de fluidos, sangrado severo, compromiso orgánico severo, alteración del estado de conciencia y disfunción sistémica.</label>";
      // Append the new div to the result-container-18
      document.getElementById('result-container-18').appendChild(newDiv);
    }
  }
}
</script>

<hr>

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
  <br>
  <button type='button' onclick='displayAnswer1()' style='width: 100px; height: 40px; border-radius: 3px; background-color: lightblue; font-weight: 700;'>Enviar</button>
</div>
<script>
  //    The function evaluates the answer and displays result
  function displayAnswer1() {
    if (document.getElementById('option-11').checked) {
      document.getElementById('block-11').style.border = '3px solid red'
      document.getElementById('result-11').style.color = 'red'
      document.getElementById('result-11').innerHTML = 'Intenta otra vez &#128552;'
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
      document.getElementById('block-12').style.border = '3px solid limegreen'
      document.getElementById('result-12').style.color = 'limegreen'
      document.getElementById('result-12').innerHTML = '¡Correcto! &#128175; En el tratamiento de la hepatitis A, la hidratación es un aspecto clave. Es importante monitorizar la función hepática para detectar insuficiencia hepática aguda, porque es el principal criterio de hospitalización. Se debe evitar medicamentos innecesarios como antieméticos o paracetamol. No hay fármacos específicos para el tratamiento de la hepatitis A. &#127775;'
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
<h3>¿Desde qué día son positivas las pruebas de anticuerpo (IgG e IgM) de dengue?</h3>
<p>Elige la respuesta correcta</p>
  <div id='block-21'>
    <label for='option-21'>
      <input type='radio' name='option' value='A' id='option-21'/>
      A. Inmediatamente</label>
    <span id='result-21'></span>
  </div>
   <div id='block-22'>
    <label for='option-22'>
      <input type='radio' name='option' value='B' id='option-22'/>
      B. 24 horas después de la infección</label>
    <span id='result-22'></span>
  </div>
   <div id='block-23'>
    <label for='option-23'>
      <input type='radio' name='option' value='C' id='option-23'/>
      C. 48 horas después de la infección</label>
    <span id='result-23'></span>
  </div>
  <div id='block-24'>
    <label for='option-24'>
      <input type='radio' name='option' value='D' id='option-24'/>
      D. 4 días después de la infección</label>
    <span id='result-24'></span>
  </div>
  <div id='block-25'>
    <label for='option-25'>
      <input type='radio' name='option' value='E' id='option-25'/>
      E. Una semana después de la infección</label>
    <span id='result-25'></span>
  </div>
  <br>
  <button type='button' onclick='displayAnswer2()' style='width: 100px; height: 40px; border-radius: 3px; background-color: lightblue; font-weight: 700;'>Enviar</button>
</div>
<script>
  //    The function evaluates the answer and displays result
  function displayAnswer2() {
    if (document.getElementById('option-21').checked) {
      document.getElementById('block-21').style.border = '3px solid red'
      document.getElementById('result-21').style.color = 'red'
      document.getElementById('result-21').innerHTML = 'Intenta otra vez &#128552;'
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
      document.getElementById('block-24').style.border = '3px solid limegreen'
      document.getElementById('result-24').style.color = 'limegreen'
      document.getElementById('result-24').innerHTML = '¡Correcto! &#128175; Las pruebas de anticuerpo para detección de dengue son positivas desde 4 días después de la infección. &#127775;'
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
<h3>¿Cuáles son los síntomas más frecuentes de chikungunya?</h3>
<p>Elige la respuesta correcta</p>
  <div id='block-31'>
    <label for='option-31'>
      <input type='radio' name='option' value='A' id='option-31'/>
      A. Fiebre y dolor articular</label>
    <span id='result-31'></span>
  </div>
   <div id='block-32'>
    <label for='option-32'>
      <input type='radio' name='option' value='B' id='option-32'/>
      B. Diarrea</label>
    <span id='result-32'></span>
  </div>
   <div id='block-33'>
    <label for='option-33'>
      <input type='radio' name='option' value='C' id='option-33'/>
      C. Descompensación y mareos</label>
    <span id='result-33'></span>
  </div>
  <div id='block-34'>
    <label for='option-34'>
      <input type='radio' name='option' value='D' id='option-34'/>
      D. Sangrado</label>
    <span id='result-34'></span>
  </div>
  <div id='block-35'>
    <label for='option-35'>
      <input type='radio' name='option' value='E' id='option-35'/>
      E. Dolor abdominal</label>
    <span id='result-35'></span>
  </div>
  <br>
  <button type='button' onclick='displayAnswer3()' style='width: 100px; height: 40px; border-radius: 3px; background-color: lightblue; font-weight: 700;'>Enviar</button>
</div>
<script>
  //    The function evaluates the answer and displays result
  function displayAnswer3() {
    if (document.getElementById('option-31').checked) {
      document.getElementById('block-31').style.border = '3px solid limegreen'
      document.getElementById('result-31').style.color = 'limegreen'
      document.getElementById('result-31').innerHTML = '¡Correcto! &#128175; Los síntomas más frecuentes de chikungunya son fiebre y dolor articular o artralgias. &#127775;'
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
      document.getElementById('block-33').style.border = '3px solid red'
      document.getElementById('result-33').style.color = 'red'
      document.getElementById('result-33').innerHTML = 'Intenta otra vez &#128552;'
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

<div>
<h3>¿Cuánto dura la fiebre en dengue?</h3>
<p>Elige la respuesta correcta</p>
  <div id='block-41'>
    <label for='option-41'>
      <input type='radio' name='option' value='A' id='option-41'/>
      A. 24 horas</label>
    <span id='result-41'></span>
  </div>
   <div id='block-42'>
    <label for='option-42'>
      <input type='radio' name='option' value='B' id='option-42'/>
      B. Un mes</label>
    <span id='result-42'></span>
  </div>
   <div id='block-43'>
    <label for='option-43'>
      <input type='radio' name='option' value='C' id='option-43'/>
      C. 14 días o menos</label>
    <span id='result-43'></span>
  </div>
  <div id='block-44'>
    <label for='option-44'>
      <input type='radio' name='option' value='D' id='option-44'/>
      D. 7 días o menos</label>
    <span id='result-44'></span>
  </div>
  <div id='block-45'>
    <label for='option-45'>
      <input type='radio' name='option' value='E' id='option-45'/>
      E. No hay fiebre en dengue</label>
    <span id='result-45'></span>
  </div>
  <br>
  <button type='button' onclick='displayAnswer4()' style='width: 100px; height: 40px; border-radius: 3px; background-color: lightblue; font-weight: 700;'>Enviar</button>
</div>
<script>
  //    The function evaluates the answer and displays result
  function displayAnswer4() {
    if (document.getElementById('option-41').checked) {
      document.getElementById('block-41').style.border = '3px solid red'
      document.getElementById('result-41').style.color = 'red'
      document.getElementById('result-41').innerHTML = 'Intenta otra vez &#128552;'
      document.getElementById('block-42').style.border = 'initial';
      document.getElementById('result-42').style.color = 'initial';
      document.getElementById('result-42').innerHTML = '';
      document.getElementById('block-43').style.border = 'initial';
      document.getElementById('result-43').style.color = 'initial';
      document.getElementById('result-43').innerHTML = '';
      document.getElementById('block-44').style.border = 'initial';
      document.getElementById('result-44').style.color = 'initial';
      document.getElementById('result-44').innerHTML = '';
      document.getElementById('block-45').style.border = 'initial';
      document.getElementById('result-45').style.color = 'initial';
      document.getElementById('result-45').innerHTML = '';
    }
    if (document.getElementById('option-42').checked) {
      document.getElementById('block-42').style.border = '3px solid red'
      document.getElementById('result-42').style.color = 'red'
      document.getElementById('result-42').innerHTML = 'Intenta otra vez &#128552;'
      document.getElementById('block-41').style.border = 'initial';
      document.getElementById('result-41').style.color = 'initial';
      document.getElementById('result-41').innerHTML = '';
      document.getElementById('block-43').style.border = 'initial';
      document.getElementById('result-43').style.color = 'initial';
      document.getElementById('result-43').innerHTML = '';
      document.getElementById('block-44').style.border = 'initial';
      document.getElementById('result-44').style.color = 'initial';
      document.getElementById('result-44').innerHTML = '';
      document.getElementById('block-45').style.border = 'initial';
      document.getElementById('result-45').style.color = 'initial';
      document.getElementById('result-45').innerHTML = '';
    }
    if (document.getElementById('option-43').checked) {
      document.getElementById('block-43').style.border = '3px solid red'
      document.getElementById('result-43').style.color = 'red'
      document.getElementById('result-43').innerHTML = 'Intenta otra vez &#128552;'
      document.getElementById('block-41').style.border = 'initial';
      document.getElementById('result-41').style.color = 'initial';
      document.getElementById('result-41').innerHTML = '';
      document.getElementById('block-42').style.border = 'initial';
      document.getElementById('result-42').style.color = 'initial';
      document.getElementById('result-42').innerHTML = '';
      document.getElementById('block-44').style.border = 'initial';
      document.getElementById('result-44').style.color = 'initial';
      document.getElementById('result-44').innerHTML = '';
      document.getElementById('block-45').style.border = 'initial';
      document.getElementById('result-45').style.color = 'initial';
      document.getElementById('result-45').innerHTML = '';
    }
    if (document.getElementById('option-44').checked) {
      document.getElementById('block-44').style.border = '3px solid limegreen'
      document.getElementById('result-44').style.color = 'limegreen'
      document.getElementById('result-44').innerHTML = '¡Correcto! &#128175; El cuadro típico de dengue es fiebre menor a siete días, generalmente acompañado de dolor retrocular. Si el paciente tiene fiebre por más de 7 días, se debe descartar otras causas. &#127775;'
      document.getElementById('block-41').style.border = 'initial';
      document.getElementById('result-41').style.color = 'initial';
      document.getElementById('result-41').innerHTML = '';
      document.getElementById('block-42').style.border = 'initial';
      document.getElementById('result-42').style.color = 'initial';
      document.getElementById('result-42').innerHTML = '';
      document.getElementById('block-43').style.border = 'initial';
      document.getElementById('result-43').style.color = 'initial';
      document.getElementById('result-43').innerHTML = '';
      document.getElementById('block-45').style.border = 'initial';
      document.getElementById('result-45').style.color = 'initial';
      document.getElementById('result-45').innerHTML = '';
    }
    if (document.getElementById('option-45').checked) {
      document.getElementById('block-45').style.border = '3px solid red'
      document.getElementById('result-45').style.color = 'red'
      document.getElementById('result-45').innerHTML = 'Intenta otra vez &#128552;'
      document.getElementById('block-41').style.border = 'initial';
      document.getElementById('result-41').style.color = 'initial';
      document.getElementById('result-41').innerHTML = '';
      document.getElementById('block-42').style.border = 'initial';
      document.getElementById('result-42').style.color = 'initial';
      document.getElementById('result-42').innerHTML = '';
      document.getElementById('block-43').style.border = 'initial';
      document.getElementById('result-43').style.color = 'initial';
      document.getElementById('result-43').innerHTML = '';
      document.getElementById('block-44').style.border = 'initial';
      document.getElementById('result-44').style.color = 'initial';
      document.getElementById('result-44').innerHTML = '';
    }
  }
</script>

<hr>

<div>
<h3>¿Cuándo se puede tomar PCR para confirmar dengue, chikungunya, zika o fiebre amarilla?</h3>
<p>Elige la respuesta correcta</p>
  <div id='block-51'>
    <label for='option-51'>
      <input type='radio' name='option' value='A' id='option-51'/>
      A. No hay prueba PCR para estas enfermedades</label>
    <span id='result-51'></span>
  </div>
   <div id='block-52'>
    <label for='option-52'>
      <input type='radio' name='option' value='B' id='option-52'/>
      B. 1 a 14 días desde la infección</label>
    <span id='result-52'></span>
  </div>
   <div id='block-53'>
    <label for='option-53'>
      <input type='radio' name='option' value='C' id='option-53'/>
      C. Hasta un mes desde la infección</label>
    <span id='result-53'></span>
  </div>
  <div id='block-54'>
    <label for='option-54'>
      <input type='radio' name='option' value='D' id='option-54'/>
      D. 1 a 5 días desde la infección</label>
    <span id='result-54'></span>
  </div>
  <div id='block-55'>
    <label for='option-55'>
      <input type='radio' name='option' value='E' id='option-55'/>
      E. Son positivas de por vida</label>
    <span id='result-55'></span>
  </div>
  <br>
  <button type='button' onclick='displayAnswer5()' style='width: 100px; height: 40px; border-radius: 3px; background-color: lightblue; font-weight: 700;'>Enviar</button>
</div>
<script>
  //    The function evaluates the answer and displays result
  function displayAnswer5() {
    if (document.getElementById('option-51').checked) {
      document.getElementById('block-51').style.border = '3px solid red'
      document.getElementById('result-51').style.color = 'red'
      document.getElementById('result-51').innerHTML = 'Intenta otra vez &#128552;'
      document.getElementById('block-52').style.border = 'initial';
      document.getElementById('result-52').style.color = 'initial';
      document.getElementById('result-52').innerHTML = '';
      document.getElementById('block-53').style.border = 'initial';
      document.getElementById('result-53').style.color = 'initial';
      document.getElementById('result-53').innerHTML = '';
      document.getElementById('block-54').style.border = 'initial';
      document.getElementById('result-54').style.color = 'initial';
      document.getElementById('result-54').innerHTML = '';
      document.getElementById('block-55').style.border = 'initial';
      document.getElementById('result-55').style.color = 'initial';
      document.getElementById('result-55').innerHTML = '';
    }
    if (document.getElementById('option-52').checked) {
      document.getElementById('block-52').style.border = '3px solid red'
      document.getElementById('result-52').style.color = 'red'
      document.getElementById('result-52').innerHTML = 'Intenta otra vez &#128552;'
      document.getElementById('block-51').style.border = 'initial';
      document.getElementById('result-51').style.color = 'initial';
      document.getElementById('result-51').innerHTML = '';
      document.getElementById('block-53').style.border = 'initial';
      document.getElementById('result-53').style.color = 'initial';
      document.getElementById('result-53').innerHTML = '';
      document.getElementById('block-54').style.border = 'initial';
      document.getElementById('result-54').style.color = 'initial';
      document.getElementById('result-54').innerHTML = '';
      document.getElementById('block-55').style.border = 'initial';
      document.getElementById('result-55').style.color = 'initial';
      document.getElementById('result-55').innerHTML = '';
    }
    if (document.getElementById('option-53').checked) {
      document.getElementById('block-53').style.border = '3px solid red'
      document.getElementById('result-53').style.color = 'red'
      document.getElementById('result-53').innerHTML = 'Intenta otra vez &#128552;'
      document.getElementById('block-51').style.border = 'initial';
      document.getElementById('result-51').style.color = 'initial';
      document.getElementById('result-51').innerHTML = '';
      document.getElementById('block-52').style.border = 'initial';
      document.getElementById('result-52').style.color = 'initial';
      document.getElementById('result-52').innerHTML = '';
      document.getElementById('block-54').style.border = 'initial';
      document.getElementById('result-54').style.color = 'initial';
      document.getElementById('result-54').innerHTML = '';
      document.getElementById('block-55').style.border = 'initial';
      document.getElementById('result-55').style.color = 'initial';
      document.getElementById('result-55').innerHTML = '';
    }
    if (document.getElementById('option-54').checked) {
      document.getElementById('block-54').style.border = '3px solid limegreen'
      document.getElementById('result-54').style.color = 'limegreen'
      document.getElementById('result-54').innerHTML = '¡Correcto! &#128175; Se puede tomar PCR para confirmar dengue, chikungunya, zika o fiebre amarilla hasta 5 días después de la infección. Después de 5 días, la viremia disminuye y ya no se puede detectar por PCR. Por eso, desde los 5 días se usa pruebas para detectar anticuerpos. &#127775;'
      document.getElementById('block-51').style.border = 'initial';
      document.getElementById('result-51').style.color = 'initial';
      document.getElementById('result-51').innerHTML = '';
      document.getElementById('block-52').style.border = 'initial';
      document.getElementById('result-52').style.color = 'initial';
      document.getElementById('result-52').innerHTML = '';
      document.getElementById('block-53').style.border = 'initial';
      document.getElementById('result-53').style.color = 'initial';
      document.getElementById('result-53').innerHTML = '';
      document.getElementById('block-55').style.border = 'initial';
      document.getElementById('result-55').style.color = 'initial';
      document.getElementById('result-55').innerHTML = '';
    }
    if (document.getElementById('option-55').checked) {
      document.getElementById('block-55').style.border = '3px solid red'
      document.getElementById('result-55').style.color = 'red'
      document.getElementById('result-55').innerHTML = 'Intenta otra vez &#128552;'
      document.getElementById('block-51').style.border = 'initial';
      document.getElementById('result-51').style.color = 'initial';
      document.getElementById('result-51').innerHTML = '';
      document.getElementById('block-52').style.border = 'initial';
      document.getElementById('result-52').style.color = 'initial';
      document.getElementById('result-52').innerHTML = '';
      document.getElementById('block-53').style.border = 'initial';
      document.getElementById('result-53').style.color = 'initial';
      document.getElementById('result-53').innerHTML = '';
      document.getElementById('block-54').style.border = 'initial';
      document.getElementById('result-54').style.color = 'initial';
      document.getElementById('result-54').innerHTML = '';
    }
  }
</script>

<hr>

<div>
<h3>Según la normativa, ¿para qué arbovirosis sí podemos tomar una prueba de ELISA?</h3>
<p>Elige la respuesta correcta</p>
  <div id='block-61'>
    <label for='option-61'>
      <input type='radio' name='option' value='A' id='option-61'/>
      A. Dengue y zika</label>
    <span id='result-61'></span>
  </div>
   <div id='block-62'>
    <label for='option-62'>
      <input type='radio' name='option' value='B' id='option-62'/>
      B. Zika</label>
    <span id='result-62'></span>
  </div>
   <div id='block-63'>
    <label for='option-63'>
      <input type='radio' name='option' value='C' id='option-63'/>
      C. Fiebre amarilla</label>
    <span id='result-63'></span>
  </div>
  <div id='block-64'>
    <label for='option-64'>
      <input type='radio' name='option' value='D' id='option-64'/>
      D. Dengue y chikungunya</label>
    <span id='result-64'></span>
  </div>
  <div id='block-65'>
    <label for='option-65'>
      <input type='radio' name='option' value='E' id='option-65'/>
      E. Fiebre amarilla y chikungunya</label>
    <span id='result-65'></span>
  </div>
  <br>
  <button type='button' onclick='displayAnswer6()' style='width: 100px; height: 40px; border-radius: 3px; background-color: lightblue; font-weight: 700;'>Enviar</button>
</div>
<script>
  //    The function evaluates the answer and displays result
  function displayAnswer6() {
    if (document.getElementById('option-61').checked) {
      document.getElementById('block-61').style.border = '3px solid red'
      document.getElementById('result-61').style.color = 'red'
      document.getElementById('result-61').innerHTML = 'Intenta otra vez &#128552;'
      document.getElementById('block-62').style.border = 'initial';
      document.getElementById('result-62').style.color = 'initial';
      document.getElementById('result-62').innerHTML = '';
      document.getElementById('block-63').style.border = 'initial';
      document.getElementById('result-63').style.color = 'initial';
      document.getElementById('result-63').innerHTML = '';
      document.getElementById('block-64').style.border = 'initial';
      document.getElementById('result-64').style.color = 'initial';
      document.getElementById('result-64').innerHTML = '';
      document.getElementById('block-65').style.border = 'initial';
      document.getElementById('result-65').style.color = 'initial';
      document.getElementById('result-65').innerHTML = '';
    }
    if (document.getElementById('option-62').checked) {
      document.getElementById('block-62').style.border = '3px solid red'
      document.getElementById('result-62').style.color = 'red'
      document.getElementById('result-62').innerHTML = 'Intenta otra vez &#128552;'
      document.getElementById('block-61').style.border = 'initial';
      document.getElementById('result-61').style.color = 'initial';
      document.getElementById('result-61').innerHTML = '';
      document.getElementById('block-63').style.border = 'initial';
      document.getElementById('result-63').style.color = 'initial';
      document.getElementById('result-63').innerHTML = '';
      document.getElementById('block-64').style.border = 'initial';
      document.getElementById('result-64').style.color = 'initial';
      document.getElementById('result-64').innerHTML = '';
      document.getElementById('block-65').style.border = 'initial';
      document.getElementById('result-65').style.color = 'initial';
      document.getElementById('result-65').innerHTML = '';
    }
    if (document.getElementById('option-63').checked) {
      document.getElementById('block-63').style.border = '3px solid red'
      document.getElementById('result-63').style.color = 'red'
      document.getElementById('result-63').innerHTML = 'Intenta otra vez &#128552;'
      document.getElementById('block-61').style.border = 'initial';
      document.getElementById('result-61').style.color = 'initial';
      document.getElementById('result-61').innerHTML = '';
      document.getElementById('block-62').style.border = 'initial';
      document.getElementById('result-62').style.color = 'initial';
      document.getElementById('result-62').innerHTML = '';
      document.getElementById('block-64').style.border = 'initial';
      document.getElementById('result-64').style.color = 'initial';
      document.getElementById('result-64').innerHTML = '';
      document.getElementById('block-65').style.border = 'initial';
      document.getElementById('result-65').style.color = 'initial';
      document.getElementById('result-65').innerHTML = '';
    }
    if (document.getElementById('option-64').checked) {
      document.getElementById('block-64').style.border = '3px solid limegreen'
      document.getElementById('result-64').style.color = 'limegreen'
      document.getElementById('result-64').innerHTML = '¡Correcto! &#128175; La normativa vigente establece que se puede tomar una prueba de ELISA solamente para dengue y chikungunya. &#127775;'
      document.getElementById('block-61').style.border = 'initial';
      document.getElementById('result-61').style.color = 'initial';
      document.getElementById('result-61').innerHTML = '';
      document.getElementById('block-62').style.border = 'initial';
      document.getElementById('result-62').style.color = 'initial';
      document.getElementById('result-62').innerHTML = '';
      document.getElementById('block-63').style.border = 'initial';
      document.getElementById('result-63').style.color = 'initial';
      document.getElementById('result-63').innerHTML = '';
      document.getElementById('block-65').style.border = 'initial';
      document.getElementById('result-65').style.color = 'initial';
      document.getElementById('result-65').innerHTML = '';
    }
    if (document.getElementById('option-65').checked) {
      document.getElementById('block-65').style.border = '3px solid red'
      document.getElementById('result-65').style.color = 'red'
      document.getElementById('result-65').innerHTML = 'Intenta otra vez &#128552;'
      document.getElementById('block-61').style.border = 'initial';
      document.getElementById('result-61').style.color = 'initial';
      document.getElementById('result-61').innerHTML = '';
      document.getElementById('block-62').style.border = 'initial';
      document.getElementById('result-62').style.color = 'initial';
      document.getElementById('result-62').innerHTML = '';
      document.getElementById('block-63').style.border = 'initial';
      document.getElementById('result-63').style.color = 'initial';
      document.getElementById('result-63').innerHTML = '';
      document.getElementById('block-64').style.border = 'initial';
      document.getElementById('result-64').style.color = 'initial';
      document.getElementById('result-64').innerHTML = '';
    }
  }
</script>

<hr>

<div>
<h3>¿Cuál es la definición de paciente febril?</h3>
<p>Elige la respuesta correcta</p>
  <div id='block-71'>
    <label for='option-71'>
      <input type='radio' name='option' value='A' id='option-71'/>
      A. Paciente con temperatura corporal de 38°C o más, mayor de 15 años, con o sin foco de infección, que acude a un establecimiento de salud por atención</label>
    <span id='result-71'></span>
  </div>
   <div id='block-72'>
    <label for='option-72'>
      <input type='radio' name='option' value='B' id='option-72'/>
      B. Paciente con temperatura corporal de 37°C o más, de cualquier grupo etario, con o sin foco de infección, que acude a un establecimiento de salud por atención</label>
    <span id='result-72'></span>
  </div>
   <div id='block-73'>
    <label for='option-73'>
      <input type='radio' name='option' value='C' id='option-73'/>
      C. Paciente con temperatura corporal de 38°C o más, de cualquier grupo etario, con o sin foco de infección, que acude a un establecimiento de salud por atención</label>
    <span id='result-73'></span>
  </div>
  <div id='block-74'>
    <label for='option-74'>
      <input type='radio' name='option' value='D' id='option-74'/>
      D. Paciente con temperatura corporal de 38°C o más, de cualquier grupo etario, con foco de infección confirmado, que acude a un establecimiento de salud por atención</label>
    <span id='result-74'></span>
  </div>
  <div id='block-75'>
    <label for='option-75'>
      <input type='radio' name='option' value='E' id='option-75'/>
      E. Paciente con temperatura corporal de 37°C o más, de cualquier grupo etario, con foco de infección confirmado, que acude a un establecimiento de salud por atención</label>
    <span id='result-75'></span>
  </div>
  <br>
  <button type='button' onclick='displayAnswer7()' style='width: 100px; height: 40px; border-radius: 3px; background-color: lightblue; font-weight: 700;'>Enviar</button>
</div>
<script>
  //    The function evaluates the answer and displays result
  function displayAnswer7() {
    if (document.getElementById('option-71').checked) {
      document.getElementById('block-71').style.border = '3px solid red'
      document.getElementById('result-71').style.color = 'red'
      document.getElementById('result-71').innerHTML = 'Intenta otra vez &#128552;'
      document.getElementById('block-72').style.border = 'initial';
      document.getElementById('result-72').style.color = 'initial';
      document.getElementById('result-72').innerHTML = '';
      document.getElementById('block-73').style.border = 'initial';
      document.getElementById('result-73').style.color = 'initial';
      document.getElementById('result-73').innerHTML = '';
      document.getElementById('block-74').style.border = 'initial';
      document.getElementById('result-74').style.color = 'initial';
      document.getElementById('result-74').innerHTML = '';
      document.getElementById('block-75').style.border = 'initial';
      document.getElementById('result-75').style.color = 'initial';
      document.getElementById('result-75').innerHTML = '';
    }
    if (document.getElementById('option-72').checked) {
      document.getElementById('block-72').style.border = '3px solid red'
      document.getElementById('result-72').style.color = 'red'
      document.getElementById('result-72').innerHTML = 'Intenta otra vez &#128552;'
      document.getElementById('block-71').style.border = 'initial';
      document.getElementById('result-71').style.color = 'initial';
      document.getElementById('result-71').innerHTML = '';
      document.getElementById('block-73').style.border = 'initial';
      document.getElementById('result-73').style.color = 'initial';
      document.getElementById('result-73').innerHTML = '';
      document.getElementById('block-74').style.border = 'initial';
      document.getElementById('result-74').style.color = 'initial';
      document.getElementById('result-74').innerHTML = '';
      document.getElementById('block-75').style.border = 'initial';
      document.getElementById('result-75').style.color = 'initial';
      document.getElementById('result-75').innerHTML = '';
    }
    if (document.getElementById('option-73').checked) {
      document.getElementById('block-73').style.border = '3px solid limegreen'
      document.getElementById('result-73').style.color = 'limegreen'
      document.getElementById('result-73').innerHTML = '¡Correcto! &#128175; La definición de paciente febril es: "Paciente con temperatura corporal de 38°C o más, de cualquier grupo etario, con o sin foco de infección, que acude a un establecimiento de salud por atención". &#127775;'
      document.getElementById('block-71').style.border = 'initial';
      document.getElementById('result-71').style.color = 'initial';
      document.getElementById('result-71').innerHTML = '';
      document.getElementById('block-72').style.border = 'initial';
      document.getElementById('result-72').style.color = 'initial';
      document.getElementById('result-72').innerHTML = '';
      document.getElementById('block-74').style.border = 'initial';
      document.getElementById('result-74').style.color = 'initial';
      document.getElementById('result-74').innerHTML = '';
      document.getElementById('block-75').style.border = 'initial';
      document.getElementById('result-75').style.color = 'initial';
      document.getElementById('result-75').innerHTML = '';
    }
    if (document.getElementById('option-74').checked) {
      document.getElementById('block-74').style.border = '3px solid red'
      document.getElementById('result-74').style.color = 'red'
      document.getElementById('result-74').innerHTML = 'Intenta otra vez &#128552;'
      document.getElementById('block-71').style.border = 'initial';
      document.getElementById('result-71').style.color = 'initial';
      document.getElementById('result-71').innerHTML = '';
      document.getElementById('block-72').style.border = 'initial';
      document.getElementById('result-72').style.color = 'initial';
      document.getElementById('result-72').innerHTML = '';
      document.getElementById('block-73').style.border = 'initial';
      document.getElementById('result-73').style.color = 'initial';
      document.getElementById('result-73').innerHTML = '';
      document.getElementById('block-75').style.border = 'initial';
      document.getElementById('result-75').style.color = 'initial';
      document.getElementById('result-75').innerHTML = '';
    }
    if (document.getElementById('option-75').checked) {
      document.getElementById('block-75').style.border = '3px solid red'
      document.getElementById('result-75').style.color = 'red'
      document.getElementById('result-75').innerHTML = 'Intenta otra vez &#128552;'
      document.getElementById('block-71').style.border = 'initial';
      document.getElementById('result-71').style.color = 'initial';
      document.getElementById('result-71').innerHTML = '';
      document.getElementById('block-72').style.border = 'initial';
      document.getElementById('result-72').style.color = 'initial';
      document.getElementById('result-72').innerHTML = '';
      document.getElementById('block-73').style.border = 'initial';
      document.getElementById('result-73').style.color = 'initial';
      document.getElementById('result-73').innerHTML = '';
      document.getElementById('block-74').style.border = 'initial';
      document.getElementById('result-74').style.color = 'initial';
      document.getElementById('result-74').innerHTML = '';
    }
  }
</script>

<hr>

<div>
<h3>¿Quiénes tienen mayor riesgo de presentar dengue grave?</h3>
<p>Elige la respuesta correcta</p>
  <div id='block-81'>
    <label for='option-81'>
      <input type='radio' name='option' value='A' id='option-81'/>
      A. Adultos de 18 a 64 años</label>
    <span id='result-81'></span>
  </div>
   <div id='block-82'>
    <label for='option-82'>
      <input type='radio' name='option' value='B' id='option-82'/>
      B. Varones y niños</label>
    <span id='result-82'></span>
  </div>
   <div id='block-83'>
    <label for='option-83'>
      <input type='radio' name='option' value='C' id='option-83'/>
      C. Personas que viven a gran altitud y adultos mayores</label>
    <span id='result-83'></span>
  </div>
  <div id='block-84'>
    <label for='option-84'>
      <input type='radio' name='option' value='D' id='option-84'/>
      D. Las gestantes no tienen riesgo de dengue grave</label>
    <span id='result-84'></span>
  </div>
  <div id='block-85'>
    <label for='option-85'>
      <input type='radio' name='option' value='E' id='option-85'/>
      E. Reinfectados, bebés y gestantes</label>
    <span id='result-85'></span>
  </div>
  <br>
  <button type='button' onclick='displayAnswer8()' style='width: 100px; height: 40px; border-radius: 3px; background-color: lightblue; font-weight: 700;'>Enviar</button>
</div>
<script>
  //    The function evaluates the answer and displays result
  function displayAnswer8() {
    if (document.getElementById('option-81').checked) {
      document.getElementById('block-81').style.border = '3px solid red'
      document.getElementById('result-81').style.color = 'red'
      document.getElementById('result-81').innerHTML = 'Intenta otra vez &#128552;'
      document.getElementById('block-82').style.border = 'initial';
      document.getElementById('result-82').style.color = 'initial';
      document.getElementById('result-82').innerHTML = '';
      document.getElementById('block-83').style.border = 'initial';
      document.getElementById('result-83').style.color = 'initial';
      document.getElementById('result-83').innerHTML = '';
      document.getElementById('block-84').style.border = 'initial';
      document.getElementById('result-84').style.color = 'initial';
      document.getElementById('result-84').innerHTML = '';
      document.getElementById('block-85').style.border = 'initial';
      document.getElementById('result-85').style.color = 'initial';
      document.getElementById('result-85').innerHTML = '';
    }
    if (document.getElementById('option-82').checked) {
      document.getElementById('block-82').style.border = '3px solid red'
      document.getElementById('result-82').style.color = 'red'
      document.getElementById('result-82').innerHTML = 'Intenta otra vez &#128552;'
      document.getElementById('block-81').style.border = 'initial';
      document.getElementById('result-81').style.color = 'initial';
      document.getElementById('result-81').innerHTML = '';
      document.getElementById('block-83').style.border = 'initial';
      document.getElementById('result-83').style.color = 'initial';
      document.getElementById('result-83').innerHTML = '';
      document.getElementById('block-84').style.border = 'initial';
      document.getElementById('result-84').style.color = 'initial';
      document.getElementById('result-84').innerHTML = '';
      document.getElementById('block-85').style.border = 'initial';
      document.getElementById('result-85').style.color = 'initial';
      document.getElementById('result-85').innerHTML = '';
    }
    if (document.getElementById('option-83').checked) {
      document.getElementById('block-83').style.border = '3px solid red'
      document.getElementById('result-83').style.color = 'red'
      document.getElementById('result-83').innerHTML = 'Intenta otra vez &#128552;'
      document.getElementById('block-81').style.border = 'initial';
      document.getElementById('result-81').style.color = 'initial';
      document.getElementById('result-81').innerHTML = '';
      document.getElementById('block-82').style.border = 'initial';
      document.getElementById('result-82').style.color = 'initial';
      document.getElementById('result-82').innerHTML = '';
      document.getElementById('block-84').style.border = 'initial';
      document.getElementById('result-84').style.color = 'initial';
      document.getElementById('result-84').innerHTML = '';
      document.getElementById('block-85').style.border = 'initial';
      document.getElementById('result-85').style.color = 'initial';
      document.getElementById('result-85').innerHTML = '';
    }
    if (document.getElementById('option-84').checked) {
      document.getElementById('block-84').style.border = '3px solid red'
      document.getElementById('result-84').style.color = 'red'
      document.getElementById('result-84').innerHTML = 'Intenta otra vez &#128552;'
      document.getElementById('block-81').style.border = 'initial';
      document.getElementById('result-81').style.color = 'initial';
      document.getElementById('result-81').innerHTML = '';
      document.getElementById('block-82').style.border = 'initial';
      document.getElementById('result-82').style.color = 'initial';
      document.getElementById('result-82').innerHTML = '';
      document.getElementById('block-83').style.border = 'initial';
      document.getElementById('result-83').style.color = 'initial';
      document.getElementById('result-83').innerHTML = '';
      document.getElementById('block-85').style.border = 'initial';
      document.getElementById('result-85').style.color = 'initial';
      document.getElementById('result-85').innerHTML = '';
    }
    if (document.getElementById('option-85').checked) {
      document.getElementById('block-85').style.border = '3px solid limegreen'
      document.getElementById('result-85').style.color = 'limegreen'
      document.getElementById('result-85').innerHTML = '¡Correcto! &#128175; Las personas con mayor riesgo de presentar dengue grave son los reinfectados, bebés y gestantes. &#127775;'
      document.getElementById('block-81').style.border = 'initial';
      document.getElementById('result-81').style.color = 'initial';
      document.getElementById('result-81').innerHTML = '';
      document.getElementById('block-82').style.border = 'initial';
      document.getElementById('result-82').style.color = 'initial';
      document.getElementById('result-82').innerHTML = '';
      document.getElementById('block-83').style.border = 'initial';
      document.getElementById('result-83').style.color = 'initial';
      document.getElementById('result-83').innerHTML = '';
      document.getElementById('block-84').style.border = 'initial';
      document.getElementById('result-84').style.color = 'initial';
      document.getElementById('result-84').innerHTML = '';
    }
  }
</script>

<hr>

<div>
<h3>¿A los cuántos días se detecta IgM en dengue?</h3>
<p>Elige la respuesta correcta</p>
  <div id='block-91'>
    <label for='option-91'>
      <input type='radio' name='option' value='A' id='option-91'/>
      A. 5 días después de la infección</label>
    <span id='result-91'></span>
  </div>
   <div id='block-92'>
    <label for='option-92'>
      <input type='radio' name='option' value='B' id='option-92'/>
      B. Desde el momento de infección</label>
    <span id='result-92'></span>
  </div>
   <div id='block-93'>
    <label for='option-93'>
      <input type='radio' name='option' value='C' id='option-93'/>
      C. 10 días después de la infección</label>
    <span id='result-93'></span>
  </div>
  <div id='block-94'>
    <label for='option-94'>
      <input type='radio' name='option' value='D' id='option-94'/>
      D. La IgM no se eleva en dengue</label>
    <span id='result-94'></span>
  </div>
  <div id='block-95'>
    <label for='option-95'>
      <input type='radio' name='option' value='E' id='option-95'/>
      E. 2 días después de la infección</label>
    <span id='result-95'></span>
  </div>
  <br>
  <button type='button' onclick='displayAnswer9()' style='width: 100px; height: 40px; border-radius: 3px; background-color: lightblue; font-weight: 700;'>Enviar</button>
</div>
<script>
  //    The function evaluates the answer and displays result
  function displayAnswer9() {
    if (document.getElementById('option-91').checked) {
      document.getElementById('block-91').style.border = '3px solid limegreen'
      document.getElementById('result-91').style.color = 'limegreen'
      document.getElementById('result-91').innerHTML = '¡Correcto! &#128175; La IgM alcanza valores detectables 5 días después de la infección. &#127775;'
      document.getElementById('block-92').style.border = 'initial';
      document.getElementById('result-92').style.color = 'initial';
      document.getElementById('result-92').innerHTML = '';
      document.getElementById('block-93').style.border = 'initial';
      document.getElementById('result-93').style.color = 'initial';
      document.getElementById('result-93').innerHTML = '';
      document.getElementById('block-94').style.border = 'initial';
      document.getElementById('result-94').style.color = 'initial';
      document.getElementById('result-94').innerHTML = '';
      document.getElementById('block-95').style.border = 'initial';
      document.getElementById('result-95').style.color = 'initial';
      document.getElementById('result-95').innerHTML = '';
    }
    if (document.getElementById('option-92').checked) {
      document.getElementById('block-92').style.border = '3px solid red'
      document.getElementById('result-92').style.color = 'red'
      document.getElementById('result-92').innerHTML = 'Intenta otra vez &#128552;'
      document.getElementById('block-91').style.border = 'initial';
      document.getElementById('result-91').style.color = 'initial';
      document.getElementById('result-91').innerHTML = '';
      document.getElementById('block-93').style.border = 'initial';
      document.getElementById('result-93').style.color = 'initial';
      document.getElementById('result-93').innerHTML = '';
      document.getElementById('block-94').style.border = 'initial';
      document.getElementById('result-94').style.color = 'initial';
      document.getElementById('result-94').innerHTML = '';
      document.getElementById('block-95').style.border = 'initial';
      document.getElementById('result-95').style.color = 'initial';
      document.getElementById('result-95').innerHTML = '';
    }
    if (document.getElementById('option-93').checked) {
      document.getElementById('block-93').style.border = '3px solid red'
      document.getElementById('result-93').style.color = 'red'
      document.getElementById('result-93').innerHTML = 'Intenta otra vez &#128552;'
      document.getElementById('block-91').style.border = 'initial';
      document.getElementById('result-91').style.color = 'initial';
      document.getElementById('result-91').innerHTML = '';
      document.getElementById('block-92').style.border = 'initial';
      document.getElementById('result-92').style.color = 'initial';
      document.getElementById('result-92').innerHTML = '';
      document.getElementById('block-94').style.border = 'initial';
      document.getElementById('result-94').style.color = 'initial';
      document.getElementById('result-94').innerHTML = '';
      document.getElementById('block-95').style.border = 'initial';
      document.getElementById('result-95').style.color = 'initial';
      document.getElementById('result-95').innerHTML = '';
    }
    if (document.getElementById('option-94').checked) {
      document.getElementById('block-94').style.border = '3px solid red'
      document.getElementById('result-94').style.color = 'red'
      document.getElementById('result-94').innerHTML = 'Intenta otra vez &#128552;'
      document.getElementById('block-91').style.border = 'initial';
      document.getElementById('result-91').style.color = 'initial';
      document.getElementById('result-91').innerHTML = '';
      document.getElementById('block-92').style.border = 'initial';
      document.getElementById('result-92').style.color = 'initial';
      document.getElementById('result-92').innerHTML = '';
      document.getElementById('block-93').style.border = 'initial';
      document.getElementById('result-93').style.color = 'initial';
      document.getElementById('result-93').innerHTML = '';
      document.getElementById('block-95').style.border = 'initial';
      document.getElementById('result-95').style.color = 'initial';
      document.getElementById('result-95').innerHTML = '';
    }
    if (document.getElementById('option-95').checked) {
      document.getElementById('block-95').style.border = '3px solid red'
      document.getElementById('result-95').style.color = 'red'
      document.getElementById('result-95').innerHTML = 'Intenta otra vez &#128552;'
      document.getElementById('block-91').style.border = 'initial';
      document.getElementById('result-91').style.color = 'initial';
      document.getElementById('result-91').innerHTML = '';
      document.getElementById('block-92').style.border = 'initial';
      document.getElementById('result-92').style.color = 'initial';
      document.getElementById('result-92').innerHTML = '';
      document.getElementById('block-93').style.border = 'initial';
      document.getElementById('result-93').style.color = 'initial';
      document.getElementById('result-93').innerHTML = '';
      document.getElementById('block-94').style.border = 'initial';
      document.getElementById('result-94').style.color = 'initial';
      document.getElementById('result-94').innerHTML = '';
    }
  }
</script>

<hr>

<div>
<h3>¿Cada cuánto tiempo se debe evaluar a un paciente ambulatorio con dengue?</h3>
<p>Elige la respuesta correcta</p>
  <div id='block-101'>
    <label for='option-101'>
      <input type='radio' name='option' value='A' id='option-101'/>
      A. No se debe reevaluar a un paciente ambulatorio</label>
    <span id='result-101'></span>
  </div>
   <div id='block-102'>
    <label for='option-102'>
      <input type='radio' name='option' value='B' id='option-102'/>
      B. Una vez a la semana</label>
    <span id='result-102'></span>
  </div>
   <div id='block-103'>
    <label for='option-103'>
      <input type='radio' name='option' value='C' id='option-103'/>
      C. Todos los días hasta que cedan la fiebre y demás signos de alarma</label>
    <span id='result-103'></span>
  </div>
  <div id='block-104'>
    <label for='option-104'>
      <input type='radio' name='option' value='D' id='option-104'/>
      D. Una vez al mes</label>
    <span id='result-104'></span>
  </div>
  <div id='block-105'>
    <label for='option-105'>
      <input type='radio' name='option' value='E' id='option-105'/>
      E. Solo si el paciente lo solicita</label>
    <span id='result-105'></span>
  </div>
  <br>
  <button type='button' onclick='displayAnswer10()' style='width: 100px; height: 40px; border-radius: 3px; background-color: lightblue; font-weight: 700;'>Enviar</button>
</div>
<script>
  //    The function evaluates the answer and displays result
  function displayAnswer10() {
    if (document.getElementById('option-101').checked) {
      document.getElementById('block-101').style.border = '3px solid red'
      document.getElementById('result-101').style.color = 'red'
      document.getElementById('result-101').innerHTML = 'Intenta otra vez &#128552;'
      document.getElementById('block-102').style.border = 'initial';
      document.getElementById('result-102').style.color = 'initial';
      document.getElementById('result-102').innerHTML = '';
      document.getElementById('block-103').style.border = 'initial';
      document.getElementById('result-103').style.color = 'initial';
      document.getElementById('result-103').innerHTML = '';
      document.getElementById('block-104').style.border = 'initial';
      document.getElementById('result-104').style.color = 'initial';
      document.getElementById('result-104').innerHTML = '';
      document.getElementById('block-105').style.border = 'initial';
      document.getElementById('result-105').style.color = 'initial';
      document.getElementById('result-105').innerHTML = '';
    }
    if (document.getElementById('option-102').checked) {
      document.getElementById('block-102').style.border = '3px solid red'
      document.getElementById('result-102').style.color = 'red'
      document.getElementById('result-102').innerHTML = 'Intenta otra vez &#128552;'
      document.getElementById('block-101').style.border = 'initial';
      document.getElementById('result-101').style.color = 'initial';
      document.getElementById('result-101').innerHTML = '';
      document.getElementById('block-103').style.border = 'initial';
      document.getElementById('result-103').style.color = 'initial';
      document.getElementById('result-103').innerHTML = '';
      document.getElementById('block-104').style.border = 'initial';
      document.getElementById('result-104').style.color = 'initial';
      document.getElementById('result-104').innerHTML = '';
      document.getElementById('block-105').style.border = 'initial';
      document.getElementById('result-105').style.color = 'initial';
      document.getElementById('result-105').innerHTML = '';
    }
    if (document.getElementById('option-103').checked) {
      document.getElementById('block-103').style.border = '3px solid limegreen'
      document.getElementById('result-103').style.color = 'limegreen'
      document.getElementById('result-103').innerHTML = '¡Correcto! &#128175; Un paciente ambulatorio con dengue debe ser reevaluado una vez al día. &#127775;'
      document.getElementById('block-101').style.border = 'initial';
      document.getElementById('result-101').style.color = 'initial';
      document.getElementById('result-101').innerHTML = '';
      document.getElementById('block-102').style.border = 'initial';
      document.getElementById('result-102').style.color = 'initial';
      document.getElementById('result-102').innerHTML = '';
      document.getElementById('block-104').style.border = 'initial';
      document.getElementById('result-104').style.color = 'initial';
      document.getElementById('result-104').innerHTML = '';
      document.getElementById('block-105').style.border = 'initial';
      document.getElementById('result-105').style.color = 'initial';
      document.getElementById('result-105').innerHTML = '';
    }
    if (document.getElementById('option-104').checked) {
      document.getElementById('block-104').style.border = '3px solid red'
      document.getElementById('result-104').style.color = 'red'
      document.getElementById('result-104').innerHTML = 'Intenta otra vez &#128552;'
      document.getElementById('block-101').style.border = 'initial';
      document.getElementById('result-101').style.color = 'initial';
      document.getElementById('result-101').innerHTML = '';
      document.getElementById('block-102').style.border = 'initial';
      document.getElementById('result-102').style.color = 'initial';
      document.getElementById('result-102').innerHTML = '';
      document.getElementById('block-103').style.border = 'initial';
      document.getElementById('result-103').style.color = 'initial';
      document.getElementById('result-103').innerHTML = '';
      document.getElementById('block-105').style.border = 'initial';
      document.getElementById('result-105').style.color = 'initial';
      document.getElementById('result-105').innerHTML = '';
    }
    if (document.getElementById('option-105').checked) {
      document.getElementById('block-105').style.border = '3px solid red'
      document.getElementById('result-105').style.color = 'red'
      document.getElementById('result-105').innerHTML = 'Intenta otra vez &#128552;'
      document.getElementById('block-101').style.border = 'initial';
      document.getElementById('result-101').style.color = 'initial';
      document.getElementById('result-101').innerHTML = '';
      document.getElementById('block-102').style.border = 'initial';
      document.getElementById('result-102').style.color = 'initial';
      document.getElementById('result-102').innerHTML = '';
      document.getElementById('block-103').style.border = 'initial';
      document.getElementById('result-103').style.color = 'initial';
      document.getElementById('result-103').innerHTML = '';
      document.getElementById('block-104').style.border = 'initial';
      document.getElementById('result-104').style.color = 'initial';
      document.getElementById('result-104').innerHTML = '';
    }
  }
</script>

<hr>

<div>
<h3>¿Cuál es la definición de caso sospechoso de fiebre chikungunya?</h3>
<p>Elige la respuesta correcta</p>
  <div id='block-111'>
    <label for='option-111'>
      <input type='radio' name='option' value='A' id='option-111'/>
      A. Toda persona con fiebre menor o igual a 7 días de evolución, que reside o ha visitado áreas de transmisión de la enfermedad o con infestación del vector Aedes aegypti, 14 días antes del inicio de los síntomas, y que presenta al menos 2 de estos síntomas: dolor ocular o retrocular, mialgias, cefalea, artralgia, dolor lumbar, rash / exantema (erupción cutánea), náuseas / vómitos</label>
    <span id='result-111'></span>
  </div>
   <div id='block-112'>
    <label for='option-112'>
      <input type='radio' name='option' value='B' id='option-112'/>
      B. Toda persona con fiebre de inicio brusco que presenta artralgia severa, poliartralgia bilateral o artritis no explicada clínicamente por otra condición médica, con un tiempo de evolución menor o igual a 7 días, que reside o ha visitado áreas con transmisión de la enfermedad o con infestación del vector Aedes aegypti, 14 días antes del inicio de los síntomas y que presente alguna de las siguientes manifestaciones: mialgias, cefalea, rash / exantema (erupción cutánea)</label>
    <span id='result-112'></span>
  </div>
   <div id='block-113'>
    <label for='option-113'>
      <input type='radio' name='option' value='C' id='option-113'/>
      C. Toda persona con rash / exantema (erupción cutánea), con un tiempo de enfermedad menor o igual a 7 días de evolución, que reside o ha visitado áreas con transmisión de enfermedad, 14 días antes del inicio de síntomas y que presenta alguno de estos síntomas: fiebre < 38.5°C, conjuntivitis no purulenta o hiperemia conjuntival, mialgia, cefalea o malestar general, artralgia, edema periarticular</label>
    <span id='result-113'></span>
  </div>
  <div id='block-114'>
    <label for='option-114'>
      <input type='radio' name='option' value='D' id='option-114'/>
      D. Todo caso de fiebre al cual se detectó anticuerpos IgM específicos contra virus chikungunya en una sola muestra durante la fase aguda o convaleciente</label>
    <span id='result-114'></span>
  </div>
  <div id='block-115'>
    <label for='option-115'>
      <input type='radio' name='option' value='E' id='option-115'/>
      E. Persona de cualquier edad que presenta un cuadro de diarrea de aparición brusca que lleva rápidamente a la deshidratación</label>
    <span id='result-115'></span>
  </div>
  <br>
  <button type='button' onclick='displayAnswer11()' style='width: 100px; height: 40px; border-radius: 3px; background-color: lightblue; font-weight: 700;'>Enviar</button>
</div>
<script>
  //    The function evaluates the answer and displays result
  function displayAnswer11() {
    if (document.getElementById('option-111').checked) {
      document.getElementById('block-111').style.border = '3px solid red'
      document.getElementById('result-111').style.color = 'red'
      document.getElementById('result-111').innerHTML = 'Intenta otra vez &#128552;'
      document.getElementById('block-112').style.border = 'initial';
      document.getElementById('result-112').style.color = 'initial';
      document.getElementById('result-112').innerHTML = '';
      document.getElementById('block-113').style.border = 'initial';
      document.getElementById('result-113').style.color = 'initial';
      document.getElementById('result-113').innerHTML = '';
      document.getElementById('block-114').style.border = 'initial';
      document.getElementById('result-114').style.color = 'initial';
      document.getElementById('result-114').innerHTML = '';
      document.getElementById('block-115').style.border = 'initial';
      document.getElementById('result-115').style.color = 'initial';
      document.getElementById('result-115').innerHTML = '';
    }
    if (document.getElementById('option-112').checked) {
      document.getElementById('block-112').style.border = '3px solid limegreen'
      document.getElementById('result-112').style.color = 'limegreen'
      document.getElementById('result-112').innerHTML = '¡Correcto! &#127775;'
      document.getElementById('block-111').style.border = 'initial';
      document.getElementById('result-111').style.color = 'initial';
      document.getElementById('result-111').innerHTML = '';
      document.getElementById('block-113').style.border = 'initial';
      document.getElementById('result-113').style.color = 'initial';
      document.getElementById('result-113').innerHTML = '';
      document.getElementById('block-114').style.border = 'initial';
      document.getElementById('result-114').style.color = 'initial';
      document.getElementById('result-114').innerHTML = '';
      document.getElementById('block-115').style.border = 'initial';
      document.getElementById('result-115').style.color = 'initial';
      document.getElementById('result-115').innerHTML = '';
    }
    if (document.getElementById('option-113').checked) {
      document.getElementById('block-113').style.border = '3px solid red'
      document.getElementById('result-113').style.color = 'red'
      document.getElementById('result-113').innerHTML = 'Intenta otra vez &#128552;'
      document.getElementById('block-111').style.border = 'initial';
      document.getElementById('result-111').style.color = 'initial';
      document.getElementById('result-111').innerHTML = '';
      document.getElementById('block-112').style.border = 'initial';
      document.getElementById('result-112').style.color = 'initial';
      document.getElementById('result-112').innerHTML = '';
      document.getElementById('block-114').style.border = 'initial';
      document.getElementById('result-114').style.color = 'initial';
      document.getElementById('result-114').innerHTML = '';
      document.getElementById('block-115').style.border = 'initial';
      document.getElementById('result-115').style.color = 'initial';
      document.getElementById('result-115').innerHTML = '';
    }
    if (document.getElementById('option-114').checked) {
      document.getElementById('block-114').style.border = '3px solid red'
      document.getElementById('result-114').style.color = 'red'
      document.getElementById('result-114').innerHTML = 'Intenta otra vez &#128552;'
      document.getElementById('block-111').style.border = 'initial';
      document.getElementById('result-111').style.color = 'initial';
      document.getElementById('result-111').innerHTML = '';
      document.getElementById('block-112').style.border = 'initial';
      document.getElementById('result-112').style.color = 'initial';
      document.getElementById('result-112').innerHTML = '';
      document.getElementById('block-113').style.border = 'initial';
      document.getElementById('result-113').style.color = 'initial';
      document.getElementById('result-113').innerHTML = '';
      document.getElementById('block-115').style.border = 'initial';
      document.getElementById('result-115').style.color = 'initial';
      document.getElementById('result-115').innerHTML = '';
    }
    if (document.getElementById('option-115').checked) {
      document.getElementById('block-115').style.border = '3px solid red'
      document.getElementById('result-115').style.color = 'red'
      document.getElementById('result-115').innerHTML = 'Intenta otra vez &#128552;'
      document.getElementById('block-111').style.border = 'initial';
      document.getElementById('result-111').style.color = 'initial';
      document.getElementById('result-111').innerHTML = '';
      document.getElementById('block-112').style.border = 'initial';
      document.getElementById('result-112').style.color = 'initial';
      document.getElementById('result-112').innerHTML = '';
      document.getElementById('block-113').style.border = 'initial';
      document.getElementById('result-113').style.color = 'initial';
      document.getElementById('result-113').innerHTML = '';
      document.getElementById('block-14').style.border = 'initial';
      document.getElementById('result-114').style.color = 'initial';
      document.getElementById('result-114').innerHTML = '';
    }
  }
</script>

<hr>

<div>
<h3>¿Cómo se diagnostica malaria?</h3>
<p> Marque las 2 alternativas correctas.</p>
  <div id='block-121'>
    <label for='option-121'>
      <input type='checkbox' name='option' value='A' id='option-121'/>
      A. El gold standard es inmunofluorescencia indirecta IFI</label>
    <span id='result-121'></span>
  </div>
   <div id='block-122'>
    <label for='option-122'>
      <input type='checkbox' name='option' value='B' id='option-122'/>
      B. El diagnóstico es solo clínico</label>
    <span id='result-122'></span>
  </div>
   <div id='block-123'>
    <label for='option-123'>
      <input type='checkbox' name='option' value='C' id='option-123'/>
      C. Pruebas inmunocromatográficas o moleculares confirman el diagnóstico</label>
    <span id='result-123'></span>
  </div>
  <div id='block-124'>
    <label for='option-124'>
      <input type='checkbox' name='option' value='D' id='option-124'/>
      D. El gold standard es inmunohistoquímica</label>
    <span id='result-124'></span>
  </div>
  <div id='block-125'>
    <label for='option-125'>
      <input type='checkbox' name='option' value='E' id='option-125'/>
      E. El método fundamental y rutinario es la gota gruesa</label>
    <span id='result-125'></span>
  </div>
  <br>
  <button type='button' onclick='displayAnswer12()' style='width: 100px; height: 40px; border-radius: 3px; background-color: lightblue; font-weight: 700;'>Enviar</button>
</div>
<script>
  //    The function evaluates the answer and displays result
  function displayAnswer12() {
    if (document.getElementById('option-121').checked) {
      document.getElementById('block-121').style.border = '3px solid red'
      document.getElementById('result-121').style.color = 'red'
      document.getElementById('result-121').innerHTML = 'Incorrecto &#128552;'
    } else {
      document.getElementById('block-121').style.border = 'initial';
      document.getElementById('result-121').style.color = 'initial';
      document.getElementById('result-121').innerHTML = '';
    }
    if (document.getElementById('option-122').checked) {
      document.getElementById('block-122').style.border = '3px solid red'
      document.getElementById('result-122').style.color = 'red'
      document.getElementById('result-122').innerHTML = 'Incorrecto &#128552;'
    } else {
      document.getElementById('block-122').style.border = 'initial';
      document.getElementById('result-122').style.color = 'initial';
      document.getElementById('result-122').innerHTML = '';
    }
    if (document.getElementById('option-123').checked) {
      document.getElementById('block-123').style.border = '3px solid limegreen'
      document.getElementById('result-123').style.color = 'limegreen'
      document.getElementById('result-123').innerHTML = '¡Correcto! &#127775;'
    } else {
      document.getElementById('block-123').style.border = 'initial';
      document.getElementById('result-123').style.color = 'initial';
      document.getElementById('result-123').innerHTML = '';
    }
    if (document.getElementById('option-124').checked) {
      document.getElementById('block-124').style.border = '3px solid red'
      document.getElementById('result-124').style.color = 'red'
      document.getElementById('result-124').innerHTML = 'Incorrecto &#128552;'
    } else {
      document.getElementById('block-124').style.border = 'initial';
      document.getElementById('result-124').style.color = 'initial';
      document.getElementById('result-124').innerHTML = '';
    }
    if (document.getElementById('option-125').checked) {
      document.getElementById('block-125').style.border = '3px solid limegreen'
      document.getElementById('result-125').style.color = 'limegreen'
      document.getElementById('result-125').innerHTML = '¡Correcto! &#127775;'
    } else {
      document.getElementById('block-125').style.border = 'initial';
      document.getElementById('result-125').style.color = 'initial';
      document.getElementById('result-125').innerHTML = '';
    }
  }
</script>

<hr>

<div>
<h3>¿Cómo se diagnostica leishmaniasis?</h3>
<p> Marque las 2 alternativas correctas.</p>
  <div id='block-131'>
    <label for='option-131'>
      <input type='checkbox' name='option' value='A' id='option-131'/>
      A. El test de Montenegro es el gold standard</label>
    <span id='result-131'></span>
  </div>
   <div id='block-132'>
    <label for='option-132'>
      <input type='checkbox' name='option' value='B' id='option-132'/>
      B. Demostrando amastigotes en muestras clínicas al microscopio</label>
    <span id='result-132'></span>
  </div>
   <div id='block-133'>
    <label for='option-133'>
      <input type='checkbox' name='option' value='C' id='option-133'/>
      C. Test de aglutinación directa</label>
    <span id='result-133'></span>
  </div>
  <div id='block-134'>
    <label for='option-134'>
      <input type='checkbox' name='option' value='D' id='option-134'/>
      D. Mediante técnicas moleculares de amplificación de ADN nuclear o del cinetoplasto</label>
    <span id='result-134'></span>
  </div>
  <div id='block-135'>
    <label for='option-135'>
      <input type='checkbox' name='option' value='E' id='option-135'/>
      E. Prueba de antígenos</label>
    <span id='result-135'></span>
  </div>
  <br>
  <button type='button' onclick='displayAnswer13()' style='width: 100px; height: 40px; border-radius: 3px; background-color: lightblue; font-weight: 700;'>Enviar</button>
</div>
<script>
  //    The function evaluates the answer and displays result
  function displayAnswer13() {
    if (document.getElementById('option-131').checked) {
      document.getElementById('block-131').style.border = '3px solid red'
      document.getElementById('result-131').style.color = 'red'
      document.getElementById('result-131').innerHTML = 'Incorrecto &#128552;'
    } else {
      document.getElementById('block-131').style.border = 'initial';
      document.getElementById('result-131').style.color = 'initial';
      document.getElementById('result-131').innerHTML = '';
    }
    if (document.getElementById('option-132').checked) {
      document.getElementById('block-132').style.border = '3px solid limegreen'
      document.getElementById('result-132').style.color = 'limegreen'
      document.getElementById('result-132').innerHTML = '¡Correcto! &#127775;'
    } else {
      document.getElementById('block-132').style.border = 'initial';
      document.getElementById('result-132').style.color = 'initial';
      document.getElementById('result-132').innerHTML = '';
    }
    if (document.getElementById('option-133').checked) {
      document.getElementById('block-133').style.border = '3px solid red'
      document.getElementById('result-133').style.color = 'red'
      document.getElementById('result-133').innerHTML = 'Incorrecto &#128552;'
    } else {
      document.getElementById('block-133').style.border = 'initial';
      document.getElementById('result-133').style.color = 'initial';
      document.getElementById('result-133').innerHTML = '';
    }
    if (document.getElementById('option-134').checked) {
      document.getElementById('block-134').style.border = '3px solid limegreen'
      document.getElementById('result-134').style.color = 'limegreen'
      document.getElementById('result-134').innerHTML = '¡Correcto! &#127775;'
    } else {
      document.getElementById('block-134').style.border = 'initial';
      document.getElementById('result-134').style.color = 'initial';
      document.getElementById('result-134').innerHTML = '';
    }
    if (document.getElementById('option-135').checked) {
      document.getElementById('block-135').style.border = '3px solid red'
      document.getElementById('result-135').style.color = 'red'
      document.getElementById('result-135').innerHTML = 'Incorrecto &#128552;'
    } else {
      document.getElementById('block-135').style.border = 'initial';
      document.getElementById('result-135').style.color = 'initial';
      document.getElementById('result-135').innerHTML = '';
    }
  }
</script>

<hr>

<div>
<h3>Marque los enunciados verdaderos sobre la enfermedad por arañazo de gato:</h3>
  <div id='block-141'>
    <label for='option-141'>
      <input type='checkbox' name='option' value='A' id='option-141'/>
      A. El contacto frecuente con gatos es un antecedente importante</label>
    <span id='result-141'></span>
  </div>
   <div id='block-142'>
    <label for='option-142'>
      <input type='checkbox' name='option' value='B' id='option-142'/>
      B. Se recomienda usar azitromicina o claritromicina como primera elección</label>
    <span id='result-142'></span>
  </div>
   <div id='block-143'>
    <label for='option-143'>
      <input type='checkbox' name='option' value='C' id='option-143'/>
      C. El tratamiento antibiótico dura 5 semanas</label>
    <span id='result-143'></span>
  </div>
  <div id='block-144'>
    <label for='option-144'>
      <input type='checkbox' name='option' value='D' id='option-144'/>
      D. Puede cursar con linfadenopatías supurativas</label>
    <span id='result-144'></span>
  </div>
  <div id='block-145'>
    <label for='option-145'>
      <input type='checkbox' name='option' value='E' id='option-145'/>
      E. No se trata con antibióticos</label>
    <span id='result-145'></span>
  </div>
  <br>
  <button type='button' onclick='displayAnswer14()' style='width: 100px; height: 40px; border-radius: 3px; background-color: lightblue; font-weight: 700;'>Enviar</button>
</div>
<script>
  //    The function evaluates the answer and displays result
  function displayAnswer14() {
    if (document.getElementById('option-141').checked) {
      document.getElementById('block-141').style.border = '3px solid limegreen'
      document.getElementById('result-141').style.color = 'limegreen'
      document.getElementById('result-141').innerHTML = '¡Correcto! &#127775;'
    } else {
      document.getElementById('block-141').style.border = 'initial';
      document.getElementById('result-141').style.color = 'initial';
      document.getElementById('result-141').innerHTML = '';
    }
    if (document.getElementById('option-142').checked) {
      document.getElementById('block-142').style.border = '3px solid limegreen'
      document.getElementById('result-142').style.color = 'limegreen'
      document.getElementById('result-142').innerHTML = '¡Correcto! &#127775;'
    } else {
      document.getElementById('block-142').style.border = 'initial';
      document.getElementById('result-142').style.color = 'initial';
      document.getElementById('result-142').innerHTML = '';
    }
    if (document.getElementById('option-143').checked) {
      document.getElementById('block-143').style.border = '3px solid limegreen'
      document.getElementById('result-143').style.color = 'limegreen'
      document.getElementById('result-143').innerHTML = '¡Correcto! &#127775;'
    } else {
      document.getElementById('block-143').style.border = 'initial';
      document.getElementById('result-143').style.color = 'initial';
      document.getElementById('result-143').innerHTML = '';
    }
    if (document.getElementById('option-144').checked) {
      document.getElementById('block-144').style.border = '3px solid limegreen'
      document.getElementById('result-144').style.color = 'limegreen'
      document.getElementById('result-144').innerHTML = '¡Correcto! &#127775;'
    } else {
      document.getElementById('block-144').style.border = 'initial';
      document.getElementById('result-144').style.color = 'initial';
      document.getElementById('result-144').innerHTML = '';
    }
    if (document.getElementById('option-145').checked) {
      document.getElementById('block-145').style.border = '3px solid red'
      document.getElementById('result-145').style.color = 'red'
      document.getElementById('result-145').innerHTML = 'Incorrecto &#128552;'
    } else {
      document.getElementById('block-145').style.border = 'initial';
      document.getElementById('result-145').style.color = 'initial';
      document.getElementById('result-145').innerHTML = '';
    }
  }
</script>

<hr>

<p><a href="index.html">&#127968; Inicio</a> | <a href="u2.html">&#9194; Unidad anterior</a> | <a href="u3.html">&#9193; Siguiente unidad</a></p>

<p>Oficina de Inteligencia e Información Sanitaria OIIS, EsSalud, Perú - 2024</p>
