<h1 align="center"> TEMA 5 </h1>

<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Tema 5: Aproximación Continua por Mínimos Cuadrados</title>
  <style>
    body {
      font-family: Arial, sans-serif;
    }
    .math {
      font-style: italic;
    }
    .subscript {
      vertical-align: sub;
      font-size: smaller;
    }
  </style>
</head>
<body>
  <h2>Análisis Numérico</h2>
  <h3>Aproximación Continua por Mínimos Cuadrados</h3>
  <p>Dado un conjunto de datos <span class="math">(</span><span class="subscript">x<sub>i</sub>, y<sub>i</sub></span><span class="math">)</span> donde <span class="math">i = 1, 2, ..., n</span>, la aproximación continua por mínimos cuadrados busca encontrar una función <span class="math">f(x)</span> que minimiza la suma de los cuadrados de las diferencias entre los valores reales <span class="math">y<sub>i</sub></span> y los valores predichos <span class="math">f(x<sub>i</sub>)</span>, es decir, buscamos minimizar la función de error cuadrático medio (MSE):</p>
  <p class="math">MSE = ∑<sub>i=1</sub><sup>n</sup> (y<sub>i</sub> - f(x<sub>i</sub>))<sup>2</sup></p>
  <p>Dependiendo del contexto y de la naturaleza de los datos, la función <span class="math">f(x)</span> puede ser una línea recta (regresión lineal), una curva de grado superior (regresión polinómica), una función exponencial, logarítmica, entre otras. La función <span class="math">f(x)</span> se encuentra ajustando los coeficientes de los términos de la función de acuerdo con los datos observados, utilizando métodos de optimización como el método de los mínimos cuadrados. Una vez que se determinan los coeficientes, la función <span class="math">f(x)</span> puede utilizarse para predecir valores de <span class="math">y</span> para nuevos valores de <span class="math">x</span> dentro del rango observado.</p>
</body>
</html>


  <style>
    body {
      font-family: Arial, sans-serif;
    }
    .header {
      font-weight: bold;
      font-size: 20px;
      margin-bottom: 10px;
    }
    .details {
      font-size: 16px;
      margin-bottom: 20px;
    }
    .emphasis {
      font-style: italic;
    }
  </style>
</head>
<body>
  <div class="header">Estudiante</div>
  <div class="details">
    <p>Universidad De Mendoza</p>
    <p>Análisis Numérico '2030'</p>
    <p>Juan Manuel Aidar <span class="emphasis">"62005"</span></p>
    <p>2024</p>
  </div>
</body>
</html>

## Current Status

| _*Codeclimate*_ | *_Coverage_* | *_Maintainability_* |
| :---:   | :---:   | :---: |
| Status |[![Test Coverage](https://api.codeclimate.com/v1/badges/42d5837a844f641bb24f/test_coverage)](https://codeclimate.com/github/jaidar2003/analisis_numerico_2024/test_coverage) |[![Maintainability](https://api.codeclimate.com/v1/badges/42d5837a844f641bb24f/maintainability)](https://codeclimate.com/github/jaidar2003/analisis_numerico_2024/maintainability)

#Aidar