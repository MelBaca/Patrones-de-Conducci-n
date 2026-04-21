# Análisis de Patrones de Conducción y Optimización de Perfiles de Velocidad

Este repositorio contiene el código, los datos y la documentación para el análisis de los patrones de conducción de la flota de la Empresa Pública Metropolitana de Transporte de Pasajeros de Quito (sistemas Trolebús y Ecovía). 

El proyecto aborda el problema en dos fases: la identificación de comportamientos mediante aprendizaje no supervisado y el ajuste temporal de los perfiles mediante optimización matemática.

## 📂 Estructura del Repositorio

* **/codigo:** Scripts desarrollados en **R** para el procesamiento de los datos GPS y la aplicación de métodos no supervisados (clustering) para clasificar los patrones de conducción según los datos de velocidad.
* **/código_python_gurobi:** Modelos de programación entera desarrollados en **Python** utilizando el solver **Gurobi**. Estos scripts calculan el desplazamiento óptimo de los perfiles de velocidad cuando es necesario ajustarlos.
* **/datos:** Archivos en formato Excel.
* **/documentos:** Documentos necesarios, reporte del proyecto.
* **/Duracion_de_viajes:** Archivos de Excel con el registro y análisis de los tiempos de trayecto.
* **/resultados_puntos_en_paradas:** Resultados tabulados y métricas calculadas específicamente en las zonas de parada.

## 🛠️ Herramientas y Metodología

1.  **Clustering (R):** Agrupamiento de comportamientos de conducción basándose en las series de tiempo de velocidad de las unidades.
2.  **Optimización (Python + Gurobi):** Formulación y resolución de un modelo de programación entera para el ajuste y desplazamiento de los perfiles de velocidad.

## 📋 Requisitos Previos

Para reproducir los análisis de este repositorio, es necesario contar con:
* Entorno R con librerías estándar de análisis de datos.
* Python 3.x.
* Licencia válida de **Gurobi Optimizer** para la ejecución de los modelos de programación entera.
