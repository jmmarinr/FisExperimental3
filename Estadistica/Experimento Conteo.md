# Experimento de conteo y distribuciones discretas

Usando los conceptos aprendidos en clase y usando como referencia el artículo adjunto “ArticuloContandoCarros” desarrolle lo siguiente:

## Toma de datos

Ingresando en el horario de clase a la página : [Contador Geiger](https://luiferg59.firstcloudit.com/arduinogeiger/), tome datos de la radiación usando el set-up remoto durante 30 minutos. Este envia muestras cada 10 s.

> Recuerde que la página debe estar en **todo momento abierta** durante la toma de datos, de lo contrario se reiniciará el conteo de datos.
> Los datos $n$ mostrados en la página hacen referencia al total de cuentas hasta el momento, para saber cuantas llegaron en el intervalo $i$ es necesario hacer la diferencia entre $n_{i+1}-n_i$.

## Análisis
1. Haciendo un análisis preliminar de los datos, determine si encuentra datos atípicos, para esto haga un ``boxplot`` y remueva aquellos que no cumplan con el criterio de los cuartiles.
2. Obtenga el valor medio $\lambda$ y la desviación estándar de los datos. Luego, usando dicho $\lambda$ cree un conjunto de datos simulados que sigan una distribución de Poisson (*ayuda: se recomienda usar ``scipy.stats.poisson.rmv``*).
3. Grafique los datos reales y los datos simulados conjuntamente. ¿Qué diferencias o similitudes encuentra entre los datos experimentales y simulados?
4. Realice un gráfico de los residuos de ambos conjuntos de datos y grafique conjuntamente, ¿puede decir que los datos están distribuidos aleatoriamente?.
5. Graficar los histogramas de cada conjunto de datos y superponga la distribución teórica. Analizar y concluir sobre los resultados obtenidos.
6. Calcule la probabilidad para los datos experimentales y simulados de que se detecten entre 2 a 5 partículas en 10 s. ¿Cuántos eventos esperaría ver en 3 minutos?

## Entrega

Entregue en el Classroom de la clase, un notebook detallando los resultados encontrados y sus conclusiones. También debe entregar el cuaderno de laboratorio con los datos tomados y la franja horaria que fueron tomados.


