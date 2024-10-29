# Matplotlib

![images](https://github.com/user-attachments/assets/2915f211-22b7-40ab-adbc-8e8c2cc47850)

Matplotlib es una biblioteca de visualización de datos en Python que permite crear gráficos de alta calidad de manera sencilla y flexible. Es especialmente útil para representar datos numéricos y explorar información de forma visual.

# 1. Tipos de Gráficos
   

Matplotlib ofrece una amplia variedad de tipos de gráficos, entre los que se incluyen:

    Gráficos de líneas: Utilizados para mostrar tendencias a lo largo del tiempo.
    Gráficos de dispersión: Ideales para visualizar la relación entre dos variables.
    Gráficos de barras: Útiles para comparar cantidades entre diferentes categorías.
    Gráficos de pastel: Para mostrar proporciones en un todo.
    Histogramas: Para representar la distribución de un conjunto de datos.
    Gráficos de caja: Útiles para mostrar la variabilidad y los valores atípicos en los datos.
    Gráficos de superficie: Para visualizar datos tridimensionales.

# 2. Estilos para una Presentación Más Profesional

Matplotlib permite personalizar los gráficos para hacerlos más atractivos y claros. Algunas recomendaciones incluyen:

    Colores y paletas: Utilizar paletas de colores coherentes y accesibles para mejorar la legibilidad.
    Etiquetas y títulos: Incluir títulos descriptivos y etiquetas en los ejes para aclarar el contenido del gráfico.
    Líneas de cuadrícula: Agregar líneas de cuadrícula puede ayudar a guiar la vista y facilitar la lectura de los datos.
    Fuentes: Elegir fuentes adecuadas y mantener una tipografía consistente.
    Leyendas: Incluir leyendas para identificar diferentes series de datos.
    Tamaño de figura: Ajustar el tamaño del gráfico para que se adapte al medio de presentación (pantalla, papel, etc.).

    Diferentes gráficos representan distintos tipos de información y son útiles para diversas situaciones, lo que permite una mejor comprensión y comunicación de los datos. imagen


    ![Mpl_screenshot_figures_and_code](https://github.com/user-attachments/assets/78cb34cc-be19-4e2f-a5ea-a5ec5a9ba590)


    1- import matplotlib: 

    import matplotlib.pyplot as plt.
    
    Descripción: Importa la biblioteca pyplot, que es el módulo más utilizado para crear gráficos.

    2-Gráfico de Líneas: 

    x = [1, 2, 3, 4, 5]
y = [2, 3, 5, 7, 11]

plt.plot(x, y)
plt.title('Gráfico de Líneas')
plt.xlabel('Eje X')
plt.ylabel('Eje Y')
plt.show() 
Descripción: Crea un gráfico de líneas que muestra la relación entre x y y.

3- Gráfico de Dispersión: 

x = [1, 2, 3, 4, 5]
y = [2, 3, 5, 7, 11]

plt.scatter(x, y)
plt.title('Gráfico de Dispersión')
plt.xlabel('Eje X')
plt.ylabel('Eje Y')
plt.show() 
Descripción: Genera un gráfico de dispersión para visualizar la relación entre dos variables.

4-  Gráfico de Barras: 
categorías = ['A', 'B', 'C', 'D']
valores = [3, 7, 5, 2]

plt.bar(categorías, valores)
plt.title('Gráfico de Barras')
plt.xlabel('Categorías')
plt.ylabel('Valores')
plt.show() 
Descripción: Crea un gráfico de barras que compara diferentes categorías.

5- Histograma: 

datos = [1, 2, 2, 3, 3, 3, 4, 4, 5]

plt.hist(datos, bins=5)
plt.title('Histograma')
plt.xlabel('Valores')
plt.ylabel('Frecuencia')
plt.show() 
Descripción: Muestra la distribución de un conjunto de datos en intervalos.

6- Gráfico de Pastel: 

tamaño = [30, 15, 45, 10]
etiquetas = ['A', 'B', 'C', 'D']

plt.pie(tamaño, labels=etiquetas, autopct='%1.1f%%')
plt.title('Gráfico de Pastel')
plt.show() 
Descripción: Crea un gráfico de pastel que muestra proporciones de un total.

7-  Gráfico de Caja: 

import numpy as np

datos = np.random.normal(0, 1, 100)

plt.boxplot(datos)
plt.title('Gráfico de Caja')
plt.ylabel('Valores')
plt.show() 
Descripción: Representa la distribución de datos a través de cuartiles, mostrando la mediana y los valores atípicos.

8- Personalización de Estilo: 

plt.style.use('ggplot')

# Gráfico de líneas
plt.plot(x, y)
plt.title('Gráfico Estilizado')
plt.xlabel('Eje X')
plt.ylabel('Eje Y')
plt.show() 
Descripción: Cambia el estilo del gráfico para hacerlo más atractivo. En este caso, se usa el estilo ggplot.

    


    
