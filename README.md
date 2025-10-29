
<p style="text-align:center">
    <a href="https://skills.network" target="_blank">
    <img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/assets/logos/SN_web_lightmode.png" width="200" alt="Skills Network Logo">
    </a>
</p>

# Ejercicios-de-regresion-IBM

Repositorio que recoge una serie de notebooks y datos prácticos sobre regresión (lineal, múltiple, polinómica, no lineal) basados en los materiales de la formación de IBM.

## Contenido

| Carpeta/archivo                                     | Descripción                                                                                                                  |
| --------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------- |
| `ML0101EN-Reg-Simple-Linear-Regression-Co2.ipynb`   | Notebook donde se aborda la regresión **simple** (una variable independiente) aplicada al CO₂.                               |
| `ML0101EN-Reg-Multiple-Linear-Regression-Co2.ipynb` | Notebook de regresión **múltiple** (varias variables independientes) aplicada al CO₂.                                        |
| `ML0101EN-Reg-Polynomial-Regression-Co2.ipynb`      | Notebook que muestra la regresión **polinómica** sobre los mismos datos de CO₂.                                              |
| `ML0101EN-Reg-NoneLinearRegression.ipynb`           | Notebook dedicado a un ejemplo de regresión **no lineal** (distinto del enfoque lineal/polinómico) para ampliar el análisis. |

## Objetivo

El objetivo de este repositorio es servir como recurso didáctico para entender, experimentar y comparar diferentes técnicas de regresión: simple, múltiple, polinómica y no lineal. Cada notebook está estructurado para que puedas:

* Cargar y explorar los datos.
* Realizar limpieza básica y análisis exploratorio.
* Ajustar diferentes modelos de regresión.
* Evaluar los modelos con métricas como R², RMSE, etc.
* Visualizar resultados y comparar enfoques.

## Requisitos

Para trabajar con estos notebooks necesitarás tener instalado:

* Python 3.x
* Librerías comunes de ciencia de datos: `numpy`, `pandas`, `matplotlib`, `seaborn`, `scikit-learn`, etc.
* Un entorno Jupyter Notebook o JupyterLab.
* (Opcional) Docker + VSCode para reproducir el entorno exacto usando `.devcontainer`.

## Instrucciones de uso

1. Clona el repositorio:

   ```bash
   git clone https://github.com/carlostessier/Ejercicios-de-regresion-IBM.git
   cd Ejercicios-de-regresion-IBM
   ```

2. Abre el entorno (por ejemplo, con Jupyter Notebook):

   ```bash
   jupyter notebook
   ```

3. Selecciona uno de los notebooks para empezar (por ejemplo `ML0101EN-Reg-Simple-Linear-Regression-Co2.ipynb`) y sigue el flujo del análisis.

4. Puedes modificar los notebooks para experimentar con otras variables, otros datasets o ajustar parámetros diferentes de los modelos.

## Buenas prácticas

* Guarda tus propios cambios en una rama separada si haces experimentos.
* Documenta tus hallazgos al final de cada notebook.
* Compara los resultados de diferentes modelos para entender cuál funciona mejor y por qué.
* No olvides dividir los datos en conjunto de entrenamiento y test para evitar sobreajuste.

## Autor

Saeed Aghabozorgi

### Otros Contribuidores

<a href="https://www.linkedin.com/in/joseph-s-50398b136/" target="_blank">Joseph Santarcangelo</a>

### Traducción

<a href="https://www.linkedin.com/in/carlostessier/" target="_blank">Carlos Tessier</a>
 

## <h3 align="center"> © Corporación IBM 2025. Todos los derechos reservados. <h3/>
