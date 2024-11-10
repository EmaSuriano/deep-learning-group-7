## Resultados Comparativos: Entrenamiento desde Cero vs Redes Pre-entrenadas

1. **Precisión**: Los modelos pre-entrenados alcanzaron una mayor precisión en la clasificación de posturas de yoga en comparación con el modelo entrenado desde cero. Esto se debe a que las redes pre-entrenadas, al estar inicializadas con características generales de grandes conjuntos de datos, lograron capturar detalles importantes sin necesidad de tantos datos específicos.
2. **Generalización**: Los modelos pre-entrenados también mostraron una mejor capacidad de generalización en el conjunto de validación, mientras que el modelo entrenado desde cero fue más propenso al _overfitting_, siendo más sensible a las variaciones en los datos de entrenamiento.
3. **Eficiencia Computacional**: Los modelos pre-entrenados permitieron un entrenamiento más rápido, ya que su punto de partida incluyó patrones previamente aprendidos, mientras que el modelo desde cero requirió más tiempo para alcanzar un rendimiento aceptable.
4. **Tamaño del Modelo**: El modelo entrenado desde cero resultó ser significativamente más pequeño en tamaño que los modelos pre-entrenados. Esto representa una ventaja en aplicaciones con limitaciones de almacenamiento, aunque el menor tamaño viene acompañado de una disminución en precisión y capacidad de generalización.

## Conclusión

En este proyecto de clasificación de posturas de yoga, los modelos pre-entrenados mostraron claras ventajas en precisión, generalización y tiempo de entrenamiento. Sin embargo, el modelo desde cero destacó por su tamaño reducido, lo que puede ser beneficioso en entornos con restricciones de almacenamiento, aunque con una leve disminución en el rendimiento global.
