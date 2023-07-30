# documentgit


<h1>Day 3</h1>

<h3>✔Pregunta:   ¿Que es Ananconda? </h3>
<h5>Es una plataforma de distribución que engloba muchas de las herramientas y bibliotecas que los científicos de datos y desarrolladores necesitan para trabajar en proyectos de análisis de datos y aprendizaje automático. Su gestor de paquetes conda facilita la instalación y gestión de paquetes y dependencias, lo que evita problemas de compatibilidad y asegura que los proyectos funcionen de manera coherente en diferentes sistemas.</h5>

  

<img src=https://miro.medium.com/v2/resize:fit:1244/1*84jnb98dXUPMF81nAk6tmg.png

alt="Descripción de la imagen">

  
  

<h3>✔¿Que es Jupyter? </h3>

<h5>Es una plataforma de distribución que engloba muchas de las herramientas y bibliotecas que los científicos de datos y desarrolladores necesitan para trabajar en proyectos de análisis de datos y aprendizaje automático. Su gestor de paquetes conda facilita la instalación y gestión de paquetes y dependencias, lo que evita problemas de compatibilidad y asegura que los proyectos funcionen de manera coherente en diferentes sistemas, gracias a Anaconda podemos trabajar dentro del mismo ya que funciona de manera directa sin la necesidad de instalaciones adicionales de paquetes.</h5>

<img src=https://seeklogo.com/images/J/jupyter-logo-A91705F539-seeklogo.com.png

alt="Descripción de la imagen">

  

<h3>✔Teachable Machine</h3>

<h5>Es una herramienta desarrollada por Google que permite entrenar modelos de aprendizaje automático sin necesidad de escribir código. Funciona mediante el uso de aprendizaje automático en el navegador, lo que facilita su acceso y uso por parte de usuarios sin experiencia en programación. Los modelos entrenados en Teachable Machine pueden utilizarse para diversas aplicaciones, incluyendo el control de videojuegos con movimientos, por ejemplo un juego de movimientos y esta detecta movimientos.</h5>

<img src=https://storage.googleapis.com/gd-prod/images/07a7eaca-a829-42bb-9214-a600de6d247b.60c498c559810aa0.gif

alt="Descripción de la imagen">

  

<h3>✔THE SPECTRUM OF ARTIFICIAL INTELLIGENCE</h3>

<h5>Es la capacidad computarizada para realizar tareas comúnmente asociadas con la inteligencia humana, incluyendo razonamiento, descubrimiento de patrones y significados, generalización, aplicación de conocimientos en diferentes ámbitos y aprendizaje a partir de la experiencia. Existen distintos tipos de IA</h5>

<ul>

<li>1.   IA basada en símbolos: Se refiere a problemas de lógica legibles por humanos</li>

<li> 2.  Búsqueda: Involucra encontrar los pasos desde un estado inicial hasta un objetivo.</li>

<li>3.   Basada en Reglas (RB): Sistemas de IA que operan aplicando reglas predefinidas y deducciones.</li>

<li>4.   Planificación y Programación (P&S): Estrategias multidimensionales y secuencias de acciones para lograr objetivos.</li>

<li> 5.   Robótica (R): Involucra sistemas de IA con múltiples sensores y/o movilidad para realizar tareas físicas y autónomas.</li>

<li>6.    Aprendizaje Profundo (DL): Utiliza múltiples capas de redes neuronales para aprender patrones y características complejas.</li>

<li>7.    Aprendizaje Automático (ML): Algoritmos que mejoran su rendimiento a través de la experiencia y los datos.</li>

<li>8.   Ingeniería del Conocimiento (KE): Basada en reglas creadas por la experiencia humana y la experticia.</li>

<li>9.   Redes Generativas Adversariales (GAN): Dos redes neuronales compiten para mejorar el rendimiento y la creatividad.</li>

<li>10.  AProcesamiento del Lenguaje Natural (NLP): Permite entender, interpretar y manipular el lenguaje humano.</li>

<li>11.  Aprendizaje por Reforzamiento (RL): Los sistemas aprenden a realizar tareas a través de recompensas y retroalimentación.</li>

</ul>

<img src=https://fpf.org/wp-content/uploads/2020/12/AI-inforgraphic.jpg

alt="Descripción de la imagen">

  

<h3>✔Python For Data Science:  Pandas Basics Cheat Sheet</h3>

<h5>Es una de las herramientas más populares y ampliamente utilizadas para el manejo y análisis de datos en la comunidad de ciencia de datos y análisis de datos en Python.</h5>

  

<h5>Pandas Data Structures: Pandas ofrece dos estructuras de datos principales: Series y DataFrame.</h5>

  

 ```javascript

>>> s = pd.Series([3, -5, 7, 4], index=[ , , , ])

```

  

<h5>Dropping: Eliminar filas o columnas de un DataFrame.</h5>

 ```javascript

>>> data = { : [ , , ], : [ , , ], : [11190846, 1303171035, 207847528]} >>>

>>> df = pd.DataFrame(data, columns=[ , , ])

```

<h5>Asking For Help: Pandas proporciona funciones para obtener ayuda e información sobre sus métodos.</h5>

 ```javascript

>>> help(pd.Series.loc)

```

<h5> Sort & Rank: Clasificar y asignar rangos a los datos en un DataFrame.</h5>

 ```javascript

>>> df.sort_index() #Sort by labels along an axis

>>> df.sort_values(by='Country' ) #Sort by the values along an axis

>>> df.rank() #Assign ranks to entries

```

  

<h5>I/O: Lectura y escritura de datos desde/hacia archivos usando pandas, se puede leer y escribir CSV ,Leer y escribir Excel  y Leer y escribir SQL o tabla de base de datos:</h5>

 ```javascript

//Read and Write to CSV

>>> pd.read_csvv( , header=None, nrows=5)

>>> df.to_csv ) ('myDataFrame.csv')

//Read and Write to Excel

>>> pd.read_excel (‘file.xlsx’)

>>> df.to_excel ('dir/myDataFrame.xlsx', sheet name= 'Sheet1')

  

//Read multiple sheets from the same file

>>> xlsx = pd.ExcelFile('file.xls' )

>>> df = pd.read_excel(xlsx, 'sheet1')

  

//Read and Write to SQL Query or Database Table

import pandas as pd

from sqlalchemy import create_engine

  

# Leer desde una tabla SQL

engine = create_engine('sqlite:///database.db')

query = 'SELECT * FROM nombre_tabla'

df_sql = pd.read_sql_query(query, engine)

  

# Escribir en una tabla SQL

df_sql.to_sql('nuevo_nombre_tabla', engine, if_exists='replace', index=False)

  
  

```

<h5>Selection: Selecting, Boolean Indexing & Setting: Seleccionar datos en un DataFrame usando diferentes métodos.</h5>

 ```javascript

import pandas as pd

  

data = {'Name': ['John', 'Alice', 'Bob'],

        'Age': [25, 30, 22]}

df = pd.DataFrame(data)

  

# Selección por etiqueta de columna

names = df['Name']

print(names)

  

# Selección basada en una condición booleana

young_people = df[df['Age'] < 30]

print(young_people)

  

# Configuración de valores basados en una condición

df.loc[df['Age'] < 30, 'Status'] = 'Young'

print(df)

```

  

<h5>Retrieving Series/DataFrame Information: Obtener información sobre el DataFrame y sus características.</h5>

 ```javascript

import pandas as pd

  

data = {'Name': ['John', 'Alice', 'Bob'],

        'Age': [25, 30, 22]}

df = pd.DataFrame(data)

  

# Información general sobre el DataFrame

print(df.info())

  

# Resumen estadístico

print(df.describe())

```

  

<h5>Applying Functions: Aplicar funciones a los datos en el DataFrame.</h5>

 ```javascript

import pandas as pd

  

data = {'Name': ['John', 'Alice', 'Bob'],

        'Age': [25, 30, 22]}

df = pd.DataFrame(data)

  

# Aplicar una función a la columna de edades

def increase_age(age):

    return age + 5

  

df['Age'] = df['Age'].apply(increase_age)

print(df)

  

```

  

<h5>Data Alignment: Alinear datos en múltiples Series o DataFrames basados en etiquetas de índice.</h5>

 ```javascript

import pandas as pd

  

s1 = pd.Series([1, 2, 3], index=['A', 'B', 'C'])

s2 = pd.Series([10, 20, 30], index=['B', 'C', 'D'])

  

# Alineación de datos en Series

result = s1 + s2

print(result)

  

data1 = {'A': [1, 2, 3],

         'B': [4, 5, 6]}

df1 = pd.DataFrame(data1)

  

data2 = {'B': [10, 20, 30],

         'C': [40, 50, 60]}

df2 = pd.DataFrame(data2)

  

# Alineación de datos en DataFrames

result_df = df1 + df2

print(result_df)

```
 



































































