# 📊 Análisis de Eficacia Operativa de los Operadores de CallMeBaby
Este proyecto evalúa la eficacia operativa de los operadores de un servicio de telefonía virtual mediante el análisis de métricas clave de desempeño (KPIs). A partir de datos históricos de llamadas, se identifican patrones de ineficiencia, se clasifican operadores según su rendimiento y se validan diferencias estadísticas entre grupos, con el objetivo de generar insights accionables para la mejora de la operación y la calidad del servicio.

## 🎯 Objetivos

* Evaluar la eficacia de los operadores a partir de métricas operativas relevantes.
* Identificar operadores ineficaces y cuantificar su impacto en la atención de llamadas.
* Comparar estadísticamente el desempeño entre operadores eficaces e ineficaces.
* Generar recomendaciones estratégicas para la gestión operativa.

## 📈 Hallazgos Clave

* Durante el periodo del 2 de octubre al 28 de noviembre de 2029, se analizaron 806,484 llamadas, predominando las llamadas salientes.
* Menos del 2% de las llamadas fueron internas y casi el 50% de las llamadas entrantes no fueron contestadas.
* La velocidad media de respuesta (ASA) se situó alrededor de 12 segundos, por encima del umbral deseable.
* La tasa diaria promedio fue de 1,600 llamadas entrantes y 5,159 llamadas salientes.
* Aplicando los criterios de ineficacia, se identificaron:
  * 961 operadores ineficaces
  * 131 operadores eficaces
* Solo 12% de los operadores cumplen con los criterios de eficacia definidos.

## 🔍 Conclusiones Estratégicas
El alto porcentaje de llamadas perdidas y los tiempos de espera prolongados indican oportunidades claras de mejora en la gestión operativa. Los criterios de ineficacia definidos pueden funcionar para establecer KPI's de eficacia de los operadores.

Existe una posible circularidad analítica, ya que las métricas utilizadas para definir la eficacia también se emplean en las pruebas de hipótesis; este punto debe considerarse en la interpretación de resultados.

Para fortalecer futuros análisis, se recomienda incorporar métricas independientes o validaciones temporales. Por ejemplo, enriquecer la base de datos incorporando:
  * Identificador del cliente para medir recontacto y resolución en primera llamada.
  * Motivo de la llamada para análisis de demanda y calidad.
  * Indicadores de transferencia para evaluar autonomía del operador.

## 🧪 Herramientas y Tecnología
* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* SciPy
* Statsmodels (Mann–Whitney, ajuste Holm de FWER)
* Jupyter
