# 🐄 Análisis de Producción Lechera en Granjas Españolas
Hecho por: @migueldiazpdj y @DanteSc03

Este repositorio contiene un Jupyter Notebook que analiza la producción de leche en granjas españolas, con el objetivo de identificar los factores clave que afectan la eficiencia y productividad de las granjas lecheras. El análisis utiliza datos históricos de granjas españolas para explorar las relaciones entre varios factores de entrada, como el número de vacas, la superficie de tierra, las horas de trabajo y la cantidad de alimento.


## 🚀 Como Empezar

### Requisitos Previos

Para ejecutar el notebook, necesitas tener lo siguiente instalado en tu sistema:

- Python (3.7 o posterior)
- Jupyter Notebook
- Stata (para los comandos `%stata` utilizados en el análisis)

También necesitarás los siguientes paquetes de Python:

- `stata_kernel`: Para ejecutar comandos de Stata dentro de Jupyter.

Puedes instalar los paquetes necesarios usando:

```sh
pip install stata_kernel
```

### Ejecutar el Notebook

1. Clona este repositorio en tu máquina local:

   ```sh
   git clone https://github.com/DanteSc03/stata
   ```

2. Abre el notebook en Jupyter:

   ```sh
   jupyter notebook script.ipynb
   ```

3. Asegúrate de que Stata esté correctamente instalado y configurado con Jupyter. Sigue la [documentación de Stata Kernel](https://kylebarron.github.io/stata_kernel/install/) para las instrucciones de configuración.

4. Ejecuta las celdas secuencialmente para realizar el análisis.

## 🔍 Flujo de Trabajo del Análisis

### Pasos Clave en el Análisis

1. **Análisis Exploratorio de Datos**: Exploración inicial del conjunto de datos, incluyendo descripciones de las variables y estadísticas resumidas.
2. **Etiquetado de Variables**: Uso de comandos de Stata para etiquetar las variables y facilitar su comprensión.
3. **Modelo Econométrico**: Desarrollo de un modelo para determinar cómo los insumos de las granjas afectan la producción de leche.
4. **Interpretación**: Interpretación de los resultados y aportación de conocimientos sobre los factores clave de la productividad.

## 📊 Resultados y Conclusiones

- El modelo econométrico revela relaciones significativas entre el número de vacas, la superficie de tierra, las horas de trabajo, el alimento y la producción de leche.
- Las variables ficticias para diferentes años ayudan a capturar los cambios temporales en la eficiencia de producción.

## 📝 Notas de Uso

- El análisis está escrito en español y está dirigido a aquellos con cierto conocimiento sobre la producción lechera y econometría.
- Se recomienda familiaridad con los comandos de Stata, ya que el notebook utiliza extensamente Stata para el análisis estadístico.

## 📄 Licencia

Este proyecto está bajo la licencia MIT - consulta el archivo [LICENSE](LICENSE) para más detalles.

