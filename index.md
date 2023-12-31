<div align="center"> 

<style>
        body {
            background-color: white;
            color: black;
            transition: background-color 0.5s, color 0.5s; /* Esto añade una suave transición al cambiar los colores */
        }

        body.dark-mode {
            background-color: #1E2021;
            color: white;
            
        }
      body.dark-mode strong ,body.dark-mode h1, body.dark-mode h2, body.dark-mode h3, body.dark-mode h4, body.dark-mode h5, body.dark-mode h6{
            color: white;
        }
      body.dark-mode blockquote{
         filter: invert(1);
      }
        button{
         font-family: 'Roboto', sans-serif;
         font-size: 14px;
         font-weight: bolt;
         background: #1e90FF;
         width: 100px;
         padding: 7px;
         text-align: center;
         text-decoration: none;
         text-transform: uppercase;
         color: #fff;
         border-radius: 6px;
         cursor: pointer;
         box-shadow: 0 0 20px rgba(0, 0, 0, 0.5);
        }
    </style>



<script>
    function toggleDarkMode() {
        const body = document.body;
        if (body.classList.contains('dark-mode')) {
            body.classList.remove('dark-mode');
        } else {
            body.classList.add('dark-mode');
        }
    }
</script>

<img src='https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat'><img src='https://img.shields.io/github/stars/Fabian-Martinez-Rincon/Computabilidad-y-Complejidad'><img src='https://img.shields.io/github/repo-size/Fabian-Martinez-Rincon/Computabilidad-y-Complejidad'>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=30&duration=1200&pause=1000&color=F78E23&center=true&width=635&lines=Deep Learning"/>



<a title="" href="https://cafecito.app/ei-materias"><img src="/Documentos/Cafecito.png" alt="" /></a>

</div>

> pip install pandas
> Extensión para ver todo clean [Dark Reader](https://darkreader.org/)
> pip install openpyxl

<div align='center'>
<button onclick="toggleDarkMode()">Oscuro</button>
<a href='https://github.com/Fabian-Martinez-Rincon/Deep-Learning/tree/main'><button style='background: #ecec00'> ⭐ </button></a>
<a href='https://github.com/Fabian-Martinez-Rincon'><button style='background: #000000'>Github</button></a>

<img src= 'https://github.com/Fabian-Martinez-Rincon/Fabian-Martinez-Rincon/assets/55964635/7eebf649-e558-43e2-ad5f-9977dc5ff3e5' height="10" width="100%"></div>


- Parcial 06/11/2023
- [Parte Teorica](/Documentos/Teoria.html)
- [Practica 1 Introducción a Python](#practica-1-introducción-a-python)
- [Practica 2 Perceptron](#practica-2-perceptron)


<img src= 'https://github.com/Fabian-Martinez-Rincon/Fabian-Martinez-Rincon/assets/55964635/7eebf649-e558-43e2-ad5f-9977dc5ff3e5
' height="10" width="100%">

# Practica 1 Introducción a Python

---

## Jupyter Notebooks y Google Colab

### Ejercicio 1

**¿Qué es un cuaderno (notebook) Jupyter?**

Un cuaderno Jupyter es una herramienta de código abierto que permite crear y compartir documentos interactivos que contienen código, ecuaciones, visualizaciones y texto narrativo. Los cuadernos Jupyter son ideales para crear un ambiente donde se pueden combinar la ejecución de código y la documentación en un solo lugar.

**¿Qué es una celda?**
Una celda es la unidad básica de contenido en un cuaderno Jupyter. Es un espacio donde se puede escribir código para ser ejecutado o se puede introducir texto para explicación y documentación.

**¿Qué tipos de celdas existen?**

Existen tres tipos principales de celdas en un cuaderno Jupyter:
1. **Celda de código:** Contiene código que puede ser ejecutado. Al correr esta celda, los resultados se muestran debajo de ella.
2. **Celda de texto/Markdown:** Esta celda contiene texto formateado utilizando el lenguaje Markdown. Permite incluir explicaciones, imágenes, enlaces y más.
3. **Celda Raw:** Es una celda que no se renderiza. Se utiliza para introducir contenido que no se desea ejecutar o transformar.

**¿Qué es un entorno de ejecución?**
Un entorno de ejecución se refiere al contexto o espacio donde se ejecuta un código o programa. Proporciona todas las herramientas, bibliotecas, variables y recursos necesarios para que el código funcione correctamente. En el ámbito de Jupyter, el entorno de ejecución es gestionado por un "kernel", que es el encargado de interpretar y ejecutar el código escrito en las celdas.

**¿Cuánto tiempo dura una sesión de un entorno?**
La duración de una sesión de entorno de ejecución varía según dónde se esté ejecutando el cuaderno:
- **Localmente:** En un Jupyter Notebook ejecutado en una máquina local, el entorno de ejecución (o kernel) continúa funcionando hasta que el usuario lo detiene o cierra el cuaderno.
- **En plataformas en la nube:** En plataformas como Google Colab, la duración de una sesión puede ser limitada. Por ejemplo, las sesiones gratuitas en Google Colab suelen tener una duración máxima de 12 horas. Es recomendable revisar la documentación específica de la plataforma que se esté utilizando para detalles precisos.

<img src= 'https://github.com/Fabian-Martinez-Rincon/Fabian-Martinez-Rincon/assets/55964635/7eebf649-e558-43e2-ad5f-9977dc5ff3e5
' height="10" width="100%">

### Ejercicio 2

Las celdas de código de un cuaderno no solo permiten ejecutar instrucciones de Python. Utilizando el símbolo ! (signo de admiración) es posible ejecutar los comandos disponibles desde la línea de comandos de su sistema operativo. De esta manera `!ls` o `!dir` (dependiendo el sistema operativo) listan los archivos de la carpeta actual y `!pip` o `!conda` permiten administrar los paquetes python.

Experimente la ejecución de varios comandos del sistema operativo a través de celdas de código. Entre las
pruebas incluya la invocación de:
- python para determinar la versión instalada.
- pip show nombre (pandas, numpy, tensorflow, etc.) de paquete para saber la versión instalada.
- comandos que permitan crear y eliminar carpetas.


El ejercicio que has mencionado se refiere a la ejecución de comandos del sistema operativo directamente desde un cuaderno Jupyter (o IPython). A continuación, te mostraré cómo hacerlo:

[Resolución en el jupyter Notebook](https://github.com/Fabian-Martinez-Rincon/Deep-Learning/blob/main/Practica/Practica0/ejercicio2.ipynb)

<img src= 'https://github.com/Fabian-Martinez-Rincon/Fabian-Martinez-Rincon/assets/55964635/7eebf649-e558-43e2-ad5f-9977dc5ff3e5
' height="10" width="100%">

### Ejercicio 3
Dado que el entorno de ejecución de un cuaderno Colab tiene un límite de duración, es importante descargar o salvar fuera del mismo los archivos que se generan.

Conecte su cuenta de Google Drive con Google Colab:

- Acceda a la url https://colab.research.google.com/ y autentíquese con su usuario Google. Cree un nuevo cuaderno (notebook).
- Asocie Drive con Colab. Compruebe que Drive queda montado como una carpeta.
- Suba un pequeño archivo de texto a Drive (NO a Colab) y ábralo desde una celda de código Colab utilizando el siguiente código:
  ```python
  ruta_arch = '....' # ruta y nombre a archivo a LEER desde su drive
  f = open(ruta_arch, 'r') # abre archivo para leer
  print(f.readlines()) # imprime contenido en pantalla
  f.close() # cierra archivo
  ```
- Genere el siguiente archivo y guárdelo en su carpeta Drive, comprobando que efectivamente se ha creado con el contenido esperado:
  ```python
  ruta_arch = '....' # ruta y nombre a archivo a ESCRIBIR en su drive
  f = open(ruta_arch, 'w') # abre archivo para escribir
  texto = 'Esta es una linea de texto\nEsta es otra línea de text'
  f.writelines(texto) # escribe contenido en archivo
  f.close() # cierra archivo
  ```

<img src= 'https://github.com/Fabian-Martinez-Rincon/Fabian-Martinez-Rincon/assets/55964635/7eebf649-e558-43e2-ad5f-9977dc5ff3e5
' height="10" width="100%">

## Repaso de Python

### Ejercicio 1
Investigue/repase que son las listas, tuplas, conjuntos y diccionarios nativos de Python (puede consultar https://www.youtube.com/watch?v=CCUNuqqn7PQ) . Utilizando los constructores para cada tipo de dato genere códigos de ejemplo y recórralos imprimiendo sus valores.

<table>
<tr><td>Listas</td><td>Tuplas</td></tr>
<tr><td>

- Son colecciones ordenadas y mutables.
- Pueden contener cualquier tipo de dato: números, cadenas, otras listas, etc.
- Se definen usando corchetes `[]`.
</td><td>

- Son colecciones ordenadas e inmutables.
- Se definen usando paréntesis `()`.
</td></tr>
<tr><td>Conjuntos (sets)</td><td>Diccionarios</td></tr>
<tr><td>

- Son colecciones no ordenadas y no tienen elementos duplicados.
- Se definen usando llaves `{}` o con el constructor `set()`.

</td><td>

- Son colecciones no ordenadas de pares clave-valor.
- Las claves son únicas y pueden ser de cualquier tipo inmutable.
- Se definen usando llaves `{}` con pares clave-valor separados por `:`.
</td></tr></table>

*Ejemplo Practico*

```python
lista = [1, 2, 3, 4, 5]
print(lista) # [1, 2, 3, 4, 5]

tupla = (1, 2, 3, 4, 5)
print(tupla) # (1, 2, 3, 4, 5)

conjunto = {1, 2, 3, 4, 5}
print(conjunto) # {1, 2, 3, 4, 5}

diccionario = {"a": 1, "b": 2, "c": 3}
for clave, valor in diccionario.items():
    print(f"Clave: {clave}, Valor: {valor}")

# Clave: a, Valor: 1
# Clave: b, Valor: 2
# Clave: c, Valor: 3

print(diccionario["a"]) # 1
```

<img src= 'https://github.com/Fabian-Martinez-Rincon/Fabian-Martinez-Rincon/assets/55964635/7eebf649-e558-43e2-ad5f-9977dc5ff3e5
' height="10" width="100%">

### Ejercicio 2
Genere el código necesario para recorrer simultáneamente 2 listas con la misma cantidad de elementos e imprima los mismos utilizando un único for (tip: función zip).

<table >
    <thead>
        <tr>
            <th>Código</th>
            <th>Salida</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>

```python
lista1 = [1, 2, 3, 4, 5]
lista2 = ['a', 'b', 'c', 'd', 'e']

for elemento1, elemento2 in zip(lista1, lista2):
    print(elemento1, elemento2)
```

</td>
<td>
  1 a<br>
  2 b<br>
  3 c<br>
  4 d<br>
  5 e
</td>
</tr>
</tbody>
</table>


<img src= 'https://github.com/Fabian-Martinez-Rincon/Fabian-Martinez-Rincon/assets/55964635/7eebf649-e558-43e2-ad5f-9977dc5ff3e5
' height="10" width="100%">

### Ejercicio 3
Implemente una función que a partir de la lista que recibe cómo parámetro, retorne una nueva lista sin elementos repetidos. Compruebe su correcto funcionamiento.

```python
def eliminar_duplicados(lista):
    return list(dict.fromkeys(lista))
```

*Ejemplos para probar la función*

```python
ejemplo1 = [1, 2, 3, 1, 2, 4, 5]
ejemplo2 = ["a", "b", "a", "c", "d", "b"]
ejemplo3 = [True, False, True, True]

resultado1 = eliminar_duplicados(ejemplo1)
resultado2 = eliminar_duplicados(ejemplo2)
resultado3 = eliminar_duplicados(ejemplo3)

print(resultado1, resultado2, resultado3)
# [1, 2, 3, 4, 5] ['a', 'b', 'c', 'd'] [True, False]
```

<img src= 'https://github.com/Fabian-Martinez-Rincon/Fabian-Martinez-Rincon/assets/55964635/7eebf649-e558-43e2-ad5f-9977dc5ff3e5
' height="10" width="100%">

### Ejercicio 4
Implemente una función que calcule la distancia entre 2 puntos (2D). Utilice la función sqrt del paquete math para implementarla y compruebe el correcto funcionamiento de la misma.

La distancia entre dos puntos en un plano 2D se calcula mediante la fórmula de la distancia euclidiana:

\[
\text{distancia} = \sqrt{(x_2 - x_1)^2 + (y_2 - y_1)^2}
\]

Donde \( (x_1, y_1) \) son las coordenadas del primer punto y \( (x_2, y_2) \) son las coordenadas del segundo punto.

Vamos a implementar la función y luego la probaremos con algunos ejemplos:

<table><td>


```python
import math

def distancia(punto1, punto2):
    x1, y1 = punto1
    x2, y2 = punto2
    return math.sqrt((x2 - x1)**2 + (y2 - y1)**2)

# Ejemplos para probar la función
puntoA = (0, 0)
puntoB = (3, 4)

resultado_AB = distancia(puntoA, puntoB)

print(resultado_AB)
# 5.0
```

</td><td> <img src='https://github.com/Fabian-Martinez-Rincon/Fabian-Martinez-Rincon/assets/55964635/4aa4ccb4-2f8d-424d-9018-7d9340c05b86'></td>


</table>



**Como puedes observar**

La distancia entre los puntos \( (0, 0) \) y \( (3, 4) \) es 5.0. Esto es porque forma un triángulo rectángulo con catetos de longitud 3 y 4, y la hipotenusa (que es la distancia entre los dos puntos) tiene longitud 5 (por el teorema de Pitágoras).

Por lo tanto, la función calcula correctamente la distancia entre dos puntos en un plano 2D.

<img src= 'https://github.com/Fabian-Martinez-Rincon/Fabian-Martinez-Rincon/assets/55964635/7eebf649-e558-43e2-ad5f-9977dc5ff3e5
' height="10" width="100%">

### Ejercicio 5
Los arrays de numpy (así como las listas) proveen de un mecanismo versátil para hacer o referenciar una sección de los mismos. Practique este mecanismo de acceso con vectores, matrices y tensores imprimiendo y modificando distintas regiones de los mismos



<table><tr><td>Vectores Uni</td><td>Matrices Bi</td><td>Tensores Tri</td></tr>

<tr><td>

- Acceso a elementos individuales
- Acceso a segmentos (slices)
- Modificación de segmentos

</td><td>

- Acceso a elementos individuales
- Acceso a filas/columnas
- Acceso a submatrices
- Modificación de submatrices

</td><td>

- Acceso a elementos individuales
- Acceso a matrices 2D individuales
- Acceso a subtensores
- Modificación de subtensores
</td></tr>
</table>

**Vectores (Arrays Unidimensionales)**

```python
import numpy as np

vector = np.array([0, 1, 2, 3, 4, 5, 6, 7, 8, 9])
print(vector[2]) # 2
print(vector[2:7]) # [2 3 4 5 6]

vector[5:8] = -1
print(vector) # [ 0  1  2  3  4 -1 -1 -1  8  9]
```

**Matrices (Arrays Bidimensionales)**:

```python
# Matrices (Arrays Bidimensionales)
matriz = np.array([[1, 2, 3], [4, 5, 6], [7, 8, 9], [10, 11, 12]])

print(matriz[1, 2]) # 6
print(matriz[1, :]) # [4 5 6]
print(matriz[:, 2]) # [ 3  6  9 12]

print(matriz[1:3, 1:3]) # Acceso a submatrices

matriz[2:4, 1:3] = 0 # Modificación de submatrices 
```

<details><summary>Explicación</summary>

- El elemento en la segunda fila y tercera columna (índices 1 y 2) es `6`.
- La segunda fila completa es `[4, 5, 6]`.
- La tercera columna completa es `[3, 6, 9, 12]`.
- La submatriz que va desde la segunda fila hasta la tercera fila (exclusiva) y de la segunda columna a la tercera columna (exclusiva) es:

    \[
    \begin{pmatrix}
    5 & 6 \\
    8 & 9 \\
    \end{pmatrix}
    \]
    
- Después de modificar la matriz, cambiando los valores de las filas 3 y 4 y las columnas 2 y 3 a `0`, la matriz se convierte en:

    \[
    \begin{pmatrix}
    1 & 2 & 3 \\
    4 & 5 & 6 \\
    7 & 0 & 0 \\
    10 & 0 & 0 \\
    \end{pmatrix}
    \]

</details>

**Tensores (Arrays Tridimensionales)**

```python
# Creación de un tensor
tensor = np.array([
    [[1, 2], [3, 4], [5, 6]],
    [[7, 8], [9, 10], [11, 12]],
    [[13, 14], [15, 16], [17, 18]]
])
```

<details><summary>Explicación</summary>

**Acceder a elementos individuales**
Vamos a acceder al elemento en la segunda matriz, segunda fila y primera columna (índices 1, 1 y 0).

```python
elemento_2_2_1 = tensor[1, 1, 0]
```

El elemento en la segunda matriz, segunda fila y primera columna (índices 1, 1 y 0) es \(9\).

**Acceder a matrices 2D individuales dentro del tensor**
Vamos a acceder a la segunda matriz 2D del tensor (índice 1).

```python
matriz_2 = tensor[1, :, :]
```

La segunda matriz 2D del tensor es:

\[
\begin{bmatrix}
7 & 8 \\
9 & 10 \\
11 & 12 \\
\end{bmatrix}
\]


**Acceder a subtensores**:

Vamos a acceder a un subtensor que incluye la primera y segunda matrices, las primeras dos filas de cada matriz y todas las columnas.

```python
subtensor = tensor[0:2, 0:2, :]
```

El subtensor seleccionado es:

\[
\begin{bmatrix}
[1, 2] & [3, 4] \\
[7, 8] & [9, 10] \\
\end{bmatrix}
\]

**Modificar subtensores**:

Vamos a modificar el tensor, cambiando los valores de las primeras dos matrices, las primeras dos filas de cada matriz y la primera columna a `-1`.

```python
tensor[0:2, 0:2, 0] = -1
```

Después de la modificación, el tensor se convierte en:

\[
\begin{bmatrix}
[-1, 2] & [-1, 4] & [5, 6] \\
[-1, 8] & [-1, 10] & [11, 12] \\
[13, 14] & [15, 16] & [17, 18] \\
\end{bmatrix}
\]

</details>

<img src= 'https://github.com/Fabian-Martinez-Rincon/Fabian-Martinez-Rincon/assets/55964635/7eebf649-e558-43e2-ad5f-9977dc5ff3e5
' height="10" width="100%">


## Biblioteca Pandas

Una de las estructuras de datos principales de Pandas es el `DataFrame`, que es esencialmente una tabla bidimensional que puede contener datos de diferentes tipos, similar a una hoja de cálculo o una tabla SQL.

> [Stack Overflow](https://stackoverflow.com/questions/76126686/appending-a-single-row-to-a-dataframe-in-pandas-2-0) con Pandas 2.0.3 (No existe el append)

<table><td>

```python
import pandas as pd
data = {
    'Nombre': ['Juan', 'María', 'Pedro', 'José'],
    'Edad': [20, 26, 18, 22],
    'Pais': ['Argentina', 'Peru', 'Brasil', 'Chile']
}

# Convertir el diccionario en un DataFrame
df = pd.DataFrame(data)

nuevo_registro = {'Nombre': 'Pablo', 'Edad': 30, 'Pais': 'Colombia'}
df2 = pd.DataFrame(nuevo_registro, df.index[-1:]+1)

df = pd.concat([df, df2])

columnas = df.columns.tolist()

df['Pais'] = df['Pais'].replace('Peru', 'Watemala')

print(columnas)
print(df)
```
</td><td>

| Nombre | Edad | País      |
|--------|------|-----------|
| Juan   | 20   | Argentina |
| María  | 26   | Perú      |
| Pedro  | 18   | Brasil    |
| José   | 22   | Chile     |
</td>
</table>

<img src= 'https://github.com/Fabian-Martinez-Rincon/Fabian-Martinez-Rincon/assets/55964635/7eebf649-e558-43e2-ad5f-9977dc5ff3e5' height="10" width="100%">

### Ejercicio 2

Guarde en disco el dataframe del ejercicio anterior en los siguientes formatos:
- archivo con separación por delimitadores (tabulador como separador).
- archivo con separación por delimitadores (punto y coma como separador).
- archivo excel.
- archivo json.

```python
import os
import pandas as pd

DATA = {
    'Nombre': ['Juan', 'María', 'Pedro', 'José'],
    'Edad': [20, 26, 18, 22],
    'Pais': ['Argentina', 'Peru', 'Brasil', 'Chile']
}
PATH_BASE = os.path.dirname(os.path.abspath(__file__))

PATH_PROSSED = os.path.join(PATH_BASE, "PandasEjercicio2")

PATH_SOURCE_TAB = os.path.join(PATH_PROSSED, "Ej2Tap.csv")
PATH_SOURCE_SPOT = os.path.join(PATH_PROSSED, "Ej2Spot.csv")
PATH_SOURCE_EXCEL = os.path.join(PATH_PROSSED, "Ej2Ex.xlsx")
PATH_SOURCE_JSON = os.path.join(PATH_PROSSED, "Ej2Json.json")

if not os.path.exists(PATH_PROSSED):
    os.makedirs(PATH_PROSSED, exist_ok=True)

DF = pd.DataFrame(DATA)

DF.to_csv(PATH_SOURCE_TAB,index=False,sep='\t')
DF.to_csv(PATH_SOURCE_SPOT,index=False,sep=';')
#DF.to_excel(pd.ExcelWriter(PATH_SOURCE_EXCEL),index=False)
DF.to_json(PATH_SOURCE_JSON,orient='records',lines=True) 
```

> No me funciona para crear excels

Realice las siguientes operaciones:
- Imprimir los nombres de las columnas.
- Agregar a la tabla a Pablo que tiene 30 años y es originario de Colombia. Agregarlo de 2 formas diferentes.
- Eliminar de la tabla al Pedro repetido.
- Modificar los atributos de países que dicen “Peru” (sin acento) y reemplazarlos por “Perú” (con acento).


<img src= 'https://github.com/Fabian-Martinez-Rincon/Fabian-Martinez-Rincon/assets/55964635/7eebf649-e558-43e2-ad5f-9977dc5ff3e5' height="10" width="100%">

# Practica 2 Perceptron

- [Video sobre diagrama de cajas](https://www.youtube.com/watch?v=24Uz1mBksL4)

>El objetivo principal de esta práctica es comprender el funcionamiento del perceptrón como bloque de construcción elemental de las redes neuronales. Adicionalmente se realiza un repaso sobre el análisis y preprocesamiento de los datos.

### Ejercicio 1

La Tabla 1 muestra información correspondiente a la resistencia adquirida por piezas de cierto material luego de haber sido sometidas a distintas temperaturas 



<table><td>


```markdown
| TEMPERATURA | DUREZA | RESISTENCIA |
|-------------|--------|-------------|
| -12         | ALTA   | SUPERIOR    |
| 20          | MEDIA  | SUPERIOR    |
| 0           | ALTA   | SUPERIOR    |
| 7           | MEDIA  | SUPERIOR    |
| 11          | BAJA   | NORMAL      |
| -30         | ALTA   | SUPERIOR    |
| 63          | BAJA   | NORMAL      |
| 94          | BAJA   | NORMAL      |
| 45          | MEDIA  | NORMAL      |
```

</td><td>

► **TEMPERATURA** es un atributo numérico que indica la temperatura en grados Celsius a la que fue sometido el material. 
► **DUREZA** es el grado de dureza que presenta al finalizar el proceso. 
► **RESISTENCIA** es el nivel de resistencia alcanzado por la pieza. 


</td>
</table>

Se numerizó el atributo DUREZA de la siguiente forma: BAJA ➔ 0, MEDIA ➔ 30, ALTA ➔ 60

- **a)** Luego de la numerización se calculó el coeficiente de correlación lineal entre los atributos TEMPERATURA y DUREZA y se obtuvo como resultado -0.78. ¿Cómo debe interpretarse este valor?
- **b)** Luego de numerizar el atributo DUREZA, los ejemplos fueron utilizados para entrenar un perceptrón capaz de predecir correctamente el atributo RESISTENCIA. Los pesos obtenidos fueron los siguientes:

w(TEMPERATURA) = 2.386; w(DUREZA) = -2.196; b = -0.023

¿Cuál será la respuesta del perceptrón para un material sometido a una TEMPERATURA de 9 grados Celsius que presenta una DUREZA =BAJA?

<img src= 'https://github.com/Fabian-Martinez-Rincon/Fabian-Martinez-Rincon/assets/55964635/7eebf649-e558-43e2-ad5f-9977dc5ff3e5' height="10" width="100%">


## Ejercicio 2 
Se  desea  construir  una  Red  Neuronal,  formada  por  un  único  Perceptrón,  para  clasificar  fotos  de  hojas diferenciando  las  que  corresponden  a  helechos  de  las  que  no.  A continuación,  se  muestran  algunas  de  las imágenes que se utilizarán en el entrenamiento

![image](https://github.com/Fabian-Martinez-Rincon/Fabian-Martinez-Rincon/assets/55964635/e45a1f5d-4862-4b28-9ffc-86899e209ba0)

Se analizaron las imágenes y se extrajeron características geométricas representativas. El archivo hojas.csv contiene la cantidad de pixeles correspondientes al perímetro y el área de cada hoja.

#### Parte a)



Utilice los ejemplos del archivo hojas.csv para entrenar un perceptrón que permita reconocer cuando se trata de una hoja de helecho. Utilice una velocidad de aprendizaje (parámetro alfa) de 0.01 y una máxima cantidad de iteraciones MAX_ITE=300.

[Codigo del perceptron](/02%20-%20Perceptrón/perceptron.py)

```python
import os
import pandas as pd
from sklearn.preprocessing import StandardScaler
import perceptron as p  # Asegúrate de que este módulo esté en el mismo directorio o en tu PYTHONPATH

def load_and_preprocess_data(file_path):
    """
    Carga y preprocesa los datos desde un archivo CSV.

    Parámetros:
    - file_path: Ruta al archivo CSV.

    Retorna:
    - X_scaled: Características escaladas.
    - y: Etiquetas.
    """
    with open(file_path, mode='r', encoding="UTF-8") as file:
        df = pd.read_csv(file)
    X = df[['Perimetro', 'Area']].values
    y = df['Clase'].apply(lambda x: 1 if x == 'Helecho' else 0).values
    scaler = StandardScaler()
    X_scaled = scaler.fit_transform(X)
    return X_scaled, y

def train_perceptron(X, y):
    """
    Entrena un Perceptrón y lo devuelve.

    Parámetros:
    - X: Características.
    - y: Etiquetas.

    Retorna:
    - Un objeto Perceptrón entrenado.
    """
    perceptron = p.Perceptron(input_size=2, lr=0.01, epochs=300)
    perceptron.fit(X, y)
    return perceptron

def main():
    """Función principal."""
    # Configurar rutas de archivos
    PATH_BASE = os.path.dirname(os.path.dirname(__file__))
    PATH_SOURCE = os.path.join(PATH_BASE, "Datos")
    FILE_NAME = 'hojas.csv'
    FILE_PATH = os.path.join(PATH_SOURCE, FILE_NAME)

    try:
        X_scaled, y = load_and_preprocess_data(FILE_PATH)
    except FileNotFoundError:
        print(f'No existe el archivo {FILE_PATH}')
        return
    except NotADirectoryError:
        print(f'La ruta no es un directorio {PATH_SOURCE}')
        return
    else:
        trained_perceptron = train_perceptron(X_scaled, y)
        print(trained_perceptron.__str__())

if __name__ == "__main__":
    main()

```

<div align='center'><img src='https://github.com/Fabian-Martinez-Rincon/Fabian-Martinez-Rincon/assets/55964635/8df959a9-d4bb-4e5c-b780-a15beacd855f' width='500px'></div>

<img src= 'https://github.com/Fabian-Martinez-Rincon/Fabian-Martinez-Rincon/assets/55964635/7eebf649-e558-43e2-ad5f-9977dc5ff3e5' height="10" width="100%">

#### Parte b)
A partir de los pesos del perceptrón entrenado, indique cuál es la función discriminante obtenida.

La función discriminante del perceptrón es:

\[
f(\mathbf{x}) = W_0 + W_1 \times \text{{Perimetro\_normalizado}} + W_2 \times \text{{Area\_normalizada}}
\]

Con los pesos \( W = [0, 0.0219, -0.0222] \), la función discriminante para este caso específico sería:

\[
f(\mathbf{x}) = 0 + 0.0219 \times \text{{Perimetro\_normalizado}} - 0.0222 \times \text{{Area\_normalizada}}
\]

Si \( f(\mathbf{x}) \geq 0 \), la clase predicha será "Helecho"; de lo contrario, será "Hoja".

<img src= 'https://github.com/Fabian-Martinez-Rincon/Fabian-Martinez-Rincon/assets/55964635/7eebf649-e558-43e2-ad5f-9977dc5ff3e5' height="10" width="100%">

#### Parte c) 
Calcule manualmente la respuesta del perceptrón si se ingresa una hoja con un perímetro de 770 pixeles 
y un área de 5000 pixeles. 

Para calcular manualmente la respuesta del perceptrón para una nueva entrada, necesitamos realizar los siguientes pasos:

1. **Normalizar la nueva entrada**: Utilizamos la media y la desviación estándar calculadas durante el entrenamiento para normalizar la nueva entrada.

\[
\text{Normalizado}(x_i) = \frac{x_i - \text{media}}{\text{desviación estándar}}
\]

2. **Agregar el término de sesgo**: Una vez que tenemos las características normalizadas, agregamos el término de sesgo (un "1" al principio del vector).

3. **Calcular la suma ponderada \( z \)**: Utilizamos los pesos finales \( W \) obtenidos después del entrenamiento para calcular la suma ponderada.

\[
z = W_0 + W_1 \times x_1 + W_2 \times x_2
\]

4. **Aplicar la función de activación**: Finalmente, aplicamos la función de activación para obtener la salida \( y \).

\[
y = 
\begin{cases} 
1 & \text{si } z \geq 0 \\
0 & \text{si } z < 0
\end{cases}
\]


```python
# main.py

import os
import pandas as pd
import numpy as np
from sklearn.preprocessing import StandardScaler
import perceptron as p

def load_and_preprocess_data(file_path):
    """Carga y preprocesa los datos desde un archivo CSV."""
    try:
        with open(file_path, mode='r', encoding="UTF-8") as file:
            df = pd.read_csv(file)
    except FileNotFoundError as e:
        raise Exception(f"El archivo {file_path} no se encuentra.") from e
    except Exception as e:
        raise Exception("Error desconocido al abrir el archivo.") from e

    X = df[['Perimetro', 'Area']].values
    y = df['Clase'].apply(lambda x: 1 if x == 'Helecho' else 0).values
    scaler = StandardScaler()
    X_scaled = scaler.fit_transform(X)
    return X_scaled, y, scaler

def predict_new_leaf(perceptron, scaler, perimetro, area):
    entrada_nueva = np.array([[perimetro, area]])
    entrada_nueva_norm = scaler.transform(entrada_nueva)
    entrada_nueva_norm = np.insert(entrada_nueva_norm, 0, 1)
    z_nuevo = np.dot(perceptron.W, entrada_nueva_norm)
    y_nuevo = 1 if z_nuevo >= 0 else 0
    return z_nuevo, y_nuevo

def main():
    """Función principal."""
    # Define constantes para las rutas de archivos
    PATH_BASE = os.path.dirname(os.path.dirname(__file__))
    PATH_SOURCE = os.path.join(PATH_BASE, "Datos")
    FILE_NAME = 'hojas.csv'
    FILE_PATH = os.path.join(PATH_SOURCE, FILE_NAME)

    try:
        X_scaled, y, scaler = load_and_preprocess_data(FILE_PATH)
        perceptron = p.Perceptron(input_size=2, lr=0.01, epochs=300)
        perceptron.fit(X_scaled, y)
        print(perceptron)

        perimetro_nuevo = 770
        area_nueva = 5000
        z_nuevo, y_nuevo = predict_new_leaf(perceptron, scaler, perimetro_nuevo, area_nueva)
        
        print(f"La suma ponderada (z) es: {z_nuevo}")
        print(f"La salida del perceptrón (y) es: {y_nuevo}")

    except Exception as e:
        print(str(e))

if __name__ == "__main__":
    main()
```


Este código calculará la suma ponderada \( z \) y la salida \( y \) del perceptrón para una hoja con un perímetro de 770 píxeles y un área de 5000 píxeles.

<img src= 'https://github.com/Fabian-Martinez-Rincon/Fabian-Martinez-Rincon/assets/55964635/7eebf649-e558-43e2-ad5f-9977dc5ff3e5' height="10" width="100%">

#### Parte d)

Realice  50  ejecuciones  independientes  del  entrenamiento  de  a)  utilizando  una  máxima  cantidad  de iteraciones  MAX_ITE=100.  Luego  complete el  siguiente  cuadro  considerando  sólo los  casos  exitosos en los que se logró obtener un perceptrón capaz de clasificar correctamente todos los ejemplos. Registre el porcentaje de ejecuciones con un accuracy del 100% y la cantidad de iteraciones promedio empleadas en estas ejecuciones exitosas

![image](https://github.com/Fabian-Martinez-Rincon/Fabian-Martinez-Rincon/assets/55964635/9b5c2a65-8da3-42d6-b5e1-cae00eeb2e86)

```python
import os
import pandas as pd
from sklearn.preprocessing import StandardScaler
from sklearn.metrics import accuracy_score
import perceptron as p

def load_data(file_path):
    """Carga los datos desde un archivo CSV."""
    with open(file_path, mode='r', encoding="UTF-8") as file:
        df = pd.read_csv(file)
    return df

def preprocess_data(df):
    """Preprocesa los datos y devuelve características y etiquetas."""
    X = df[['Perimetro', 'Area']].values
    y = df['Clase'].apply(lambda x: 1 if x == 'Helecho' else 0).values
    scaler = StandardScaler()
    X_scaled = scaler.fit_transform(X)
    return X_scaled, y

def run_multiple_trainings(X, y, num_executions=50, max_iterations=100):
    """Ejecuta múltiples entrenamientos y devuelve estadísticas."""
    successful_executions = 0
    total_iterations = 0
    
    for _ in range(num_executions):
        perceptron = p.Perceptron(input_size=2, lr=0.01, epochs=max_iterations)
        perceptron.fit(X, y)
        
        y_pred = [perceptron.predict(x) for x in X]
        if accuracy_score(y, y_pred) == 1.0:
            successful_executions += 1
            total_iterations += max_iterations

    percentage_successful = (successful_executions / num_executions) * 100
    average_iterations = total_iterations / successful_executions if successful_executions > 0 else 0
    
    return percentage_successful, average_iterations

if __name__ == "__main__":
    PATH_BASE = os.path.dirname(os.path.dirname(__file__))
    PATH_SOURCE = os.path.join(PATH_BASE, "Datos")
    FILE_NAME = 'hojas.csv'
    FILE_PATH = os.path.join(PATH_SOURCE, FILE_NAME)
    
    try:
        df = load_data(FILE_PATH)
        X_scaled, y = preprocess_data(df)
        percentage_successful, average_iterations = run_multiple_trainings(X_scaled, y)
        
        print(f"Porcentaje de ejecuciones exitosas: {percentage_successful}")
        print(f"Promedio de iteraciones en ejecuciones exitosas: {average_iterations}")

    except FileNotFoundError:
        print(f'No existe el archivo {FILE_PATH}')
    except NotADirectoryError:
        print(f'La ruta no es un directorio {PATH_SOURCE}')
```

<img src= 'https://github.com/Fabian-Martinez-Rincon/Fabian-Martinez-Rincon/assets/55964635/7eebf649-e558-43e2-ad5f-9977dc5ff3e5' height="10" width="100%">
