# MLTutorial
1.	Del script de forest fires:
a.	¿Se desea resolver el problema utilizando aprendizaje supervisado o no supervisado? ¿Es un problema de clasificación o de regresión?
RTA: Para este caso el aprendizaje es supervisado pues tenemos un modelo para determinar un dato, y para la solucion de este problema,
se utiliza la regresion pues lo que busca la solucion es predecir X y Y, de nuestro conjunto de datos.
b.	¿Qué interpretación le puede dar a los resultados obtenidos?
RTA:  Las posibilidades de tener un incendio, de acuerdo a los datos de nuestro modelo.
2.	Del script de recursos humanos (rrhh):
a.	¿Cuál es la clase para la que el modelo más se equivoca? ¿Por qué?
RTA: Siento que es la clase de 'left', pues solo tiene dos variables 1/0, y al momento de sacar el modelo visual no es claro.
b.	¿Cuál cree que es el propósito del parámetro max_depth usado al momento de instanciar el modelo de árbol de decisión?
RTA: Con este parametro su busca la profundidad maxima del arbol, en este caso 5, con este parametro se puede desarrollar un buen modelo utilizando el algoritmo de arbol de desicion.
c.	Para este caso particular, ¿por qué cree que es difícil obtener un buen clasificador?
RTA: Nuestro modelo de datos contiene varias alternancias para clasificar, y muchos de los datos van de la mano con lo que se quiere llegar, es por lo que hace dificil tener un solo dato que nos ayude a tener un prediccion mas clara.
3.	Identificación de géneros musicales: Tenga en cuenta que hay dos scripts: music.ipynb y music-multiclass.ipynb. En el primero se intenta crear un modelo clasificador solo para dos clases (caso binario) y en el segundo se entrena uno para todas las clases (géneros musicales) del dataset.
a.	Para el caso binario (jazz and blues vs. soul and reggae) ¿Es posible obtener mejores métricas entrenando un modelo basado en Random Forest?
RTA:   Considero que si, pues con este modelo de arboles predictorios, se tienen valores de un vector aleatorio probado independientemente y con la misma distribución para cada uno de estos, con esto teniendo un modelo mas simple de entrenar y ajustar.
b.	Escoja otro par de géneros, entrene un conjunto de modelos y documente los resultados del mejor que se haya obtenido.
RTA: PARA ESTE CASO ENTRENE: FOLK Y DANCE AND ELECTRONICA.

c.	Para el caso multi-clase, ¿cuál es la clase para la que el modelo más se equivoca? ¿Por qué?
RTA:
d.	Para el caso multi-clase, el modelo basado en red neuronal parece estar mayoritariamente sesgado hacia un género particular. ¿Cuál género cree que es?
RTA:
4.	Segmentación de cajas de compensación familiar (subsidio):
a.	¿Qué cajas de compensación parecen ser mayoritariamente diferentes a las demás?
RTA:caja de Compensación Familiar de Antioquia COM, por la cantidad de empresas afiliadas.
Caja de Compensacion Familiar del Amazonas CAF, por la minima cantidad de empresas afiliadas.
b.	¿A partir de qué características utilizadas para el entrenamiento del modelo se podría explicar la razón por la que las cajas anteriores fueron agrupadas en clusters tan pequeños?
RTA:La razón para que el clustering sea agrupada en grupos pequeños, es para que sea mas efectivo el uso de los atributos mas relevantes y poner los datos en una escala similar.
c.	¿Se pueden obtener resultados más homogéneos utilizando cantidades diferentes de clusters para el entrenamiento? Entienda homogeneidad como clusters con cantidades similares de instancias de datos.
RTA:Por supuesto, el análisis de clustering no nos da ninguna de estas explicaciones, solo nos da el numero de grupos, y no tiene nada que ver el resultado de los datos con un grupo homogeneo.