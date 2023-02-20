# w5-Visualization-project

![pokemon](https://github.com/Edupastore/w5-Visualization-project/blob/main/images/portada.png)


## ⛓️ Índice de contenidos

1.[✍️ Descripción del proyecto](#descripción)\
2.[👀 Visualización de datos](#visualización)\
3.[👄💭 Historia](#historia)

## ✍️ Descripción

Siguiendo con la temática de Pokémon del proyecto anterior (ETL), hemos elaborado un dashboard con Power BI, con varios gráficos, que plasman de manera descriptiva los datos que transformamos previamente.

Para esta visualización, hemos ampliado nuestro conjunto de datos añadiendo cinco variables (columnas) que son una transformación de otras variables que configuran nuestra tabla maestra (combinación de las stats: ataque, defensa, ataque especial, defensa especial, velocidad y puntos de salud).

Las nuevas variables de las que hablamos se han calculado de la siguiente forma:

    - Physical sweeper (phy_sweeper): se calcula sumando el ataque y la velocidad.
    - Special sweeper (sp_sweeper): se calcula sumando el ataque especial y la velocidad.
    - Wall (wall): se calcula sumando el hp, la defensa y la defensa especial.
    - Physical tank (phy_tank): se calcula sumando el ataque y la defensa.
    - Special tank (sp_tank): se calcula sumando el ataque especial y la defensa especial.

## 👀 Visualización de datos

A continuación, se muestran capturas de los gráficos que hemos generado en Power BI (el archivo con el dashboard se encuentra en el interior de este repositorio, en la carpeta denominada "dashboard). Nuestro dashboard consta de seis hojas donde se describen diferentes aspectos relacionados con los Pokémon conocidos hasta la fecha. Vamos a ver ahora, de manera sucinta, qué muestran estos gráficos:

<details>
<summary>Número de Pokémon</summary>
<br>

![uno](https://github.com/Edupastore/w5-Visualization-project/blob/main/images/captura_uno.jpg)
<br>
<br>
En este primer gráfico se presenta la distribución de los Pokémon que tenemos en cada generación.
<br>
<br>

</details>

<details>
<summary>Tipo principal de Pokémon</summary>
<br>

![dos](https://github.com/Edupastore/w5-Visualization-project/blob/main/images/captura_dos.jpg)
<br>
<br>
Aquí podemos ver la distribución del tipo principal de cada Pokémon (tipo 1) por generación.
<br>
<br>

</details>

<details>
<summary>Tipo secundario de Pokémon</summary>
<br>

![tres](https://github.com/Edupastore/w5-Visualization-project/blob/main/images/captura_tres.jpg)
<br>
<br>
Aquí, tenemos lo mismo que antes, pero para el tipo secundario de cada Pokémon (tipo 2).
<br>
<br>

</details>

<details>
<summary>Pokémon legendarios versus Pokémon no legendarios</summary>
<br>

![cuatro](https://github.com/Edupastore/w5-Visualization-project/blob/main/images/captura_cuatro.jpg)
<br>
<br>
En este gráfico, el foco se ha puesto sobre la cantidad de Pokémon legendarios y no legendarios existentes y su distribución por generaciones.
<br>
<br>

</details>

<details>
<summary>Stats Pokémon</summary>
<br>

![cuatro](https://github.com/Edupastore/w5-Visualization-project/blob/main/images/captura_cuatro.jpg)
<br>
<br>
En este gráfico, el foco se ha puesto sobre la cantidad de Pokémon legendarios y no legendarios existentes y su distribución por generaciones.
<br>
<br>

</details>

<details>
<summary>Competitivo Pokémon</summary>
<br>

![cinco](https://github.com/Edupastore/w5-Visualization-project/blob/main/images/captura_cinco.jpg)
<br>
<br>
Aquí, podemos visualizar los valores promedio, máximo y mínimo de cada stat (ataque, defensa, ataque especial, defensa especial, velocidad y puntos de salud) en cada generación.
<br>
<br>

</details>

<details>
<summary>Número de Pokémon por generación</summary>
<br>

![seis](https://github.com/Edupastore/w5-Visualization-project/blob/main/images/captura_seis.jpg)
<br>
<br>
Por último, podemos visualizar los valores promedio, máximo y mínimo de cada parámetro competitivo (physical sweeper, special sweeper, wall, physical tank y special tank) en cada generación.
<br>
<br>

</details>

## 👄💭 Historia

El leit motiv de este estudio, ha sido elaborar una visualización en la que se han presentado distintos aspectos de nuestro conjunto de datos a modo de resumen, donde el enfásis ha sido la comparativa de dichos aspectos entre generaciones.

Todos los gráficos que hemos elaborado, tienen incorporado un filtro con el que podemos hacer comparaciones entre todas las generaciones, entre varias de ellas o incluso ver una "foto" de la generación que más nos interese sobre ese aspecto en concreto.




