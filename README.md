# Déjame escuchar la música

Este es un proyecto donde se ponen a prueba los conocimientos de la librería Pandas :panda_face:. Cabe aclarar que este es un proyecto educativo dado por el bootcamp en línea TripleTen.

Se va a usar un dataset que contiene datos de transmisión de música online para comparar el comportamiento de los usuarios y las usuarias en Springfield y Shelbyville.El proyecto se divide en tres etapas:

1. Se tiene que proporcionar una descripción general de los datos y anotan las observaciones realizadas
2. Se preprocesarán los datos para limpiarlos.
3. Se pondrán a prueba unas hipótesis para deducir el comportamiento de los usuarios de la plataforma de música online

## Etapa 1
En este proyecto se realiza por primera vez la importación de un dataset usando la función `pandas.read_csv()`.

Una vez creado el DataFrame se hace una revisión de los datos contenidos. Esto significa que se buscan valores ausentes, valores duplicados, si los títulos del encabezado siguen el estilo snake_case, etc. 

## Etapa 2
Si hay valores ausentes, se determinan las acciones a seguir para poder procesar estos valores. De igual manera se hace con los valores duplicados.

También se busca si hay valores duplicados implícitos, es decir, valores en las columnas que están escritos de diferente manera pero significan lo mismo, por ejemplo: la palabra `'hiphop'` y `'hip-hop'`. Ambas se refieren al género músical pero están escritas de diferente forma.

## Etapa 3

Se prueban las hipótesis:
* La actividad de los usuarios y las usuarias difiere según el día de la semana y dependiendo de la ciudad.
* Los lunes por la mañana, los habitantes de Springfield y Shelbyville escuchan géneros distintos. Lo mismo ocurre los viernes por la noche.
* Los oyentes de Springfield y Shelbyville tienen preferencias distintas. En Springfield prefieren el pop, mientras que en Shelbyville hay más personas a las que les gusta el rap.

Para poder encontrar la respuesta a estas hipótesis debes entrar al proyecto.