[![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=ChaparroAlain/Practica-5_AnalisisDeSistemasBiologicos_Chaparro21212147&project=https://drive.mathworks.com/sharing/f9f549bd-f45b-4fcb-9adf-844232dfc488)

# Gemelos Digitales. Proyecto final [Chaparro21212147]

## Autor
Chaparro Zamora Alain Yahir

Ingeniería Biomédica, Departamento de Ingeniería Eléctrica y Electrónica, Tecnológico Nacional de México/IT Tijuana. Blvd. Alberto Limón Padilla s/n, Tijuana, C.P. 22454, B.C., México. Email: l21212147@tectijuana.edu.mx

## Resumen de la práctica
Este proyecto presenta el desarrollo y análisis de un modelo dinámico que representa la interacción de tres variables fisiológicas a lo largo del tiempo, utilizando un enfoque basado en datos experimentales. El modelo se construyó mediante un sistema de ecuaciones diferenciales no lineales con seis parámetros, denotados como rho_1 a rho_6, cada uno correspondiente a una tasa específica de interacción o cambio interno entre las variables. Se utilizaron datos experimentales recolectados durante un cierto periodo para ajustar el modelo mediante regresión no lineal. Las variables, representadas como x(t), y(t) y z(t), evolucionan en función de términos como xy, xyz y yz, los cuales modelan procesos como activación, supresión o crecimiento. El proceso de ajuste del modelo arrojó resultados altamente satisfactorios, con un coeficiente de determinación de R^2 = 0.9998, lo que indica una excelente concordancia con los datos observados. Todos los parámetros estimados fueron estadísticamente significativos, con intervalos de confianza estrechos y valores p muy bajos. Además, el análisis de la matriz Jacobiana y los puntos de equilibrio reveló la existencia de dos soluciones estacionarias, proporcionando información relevante sobre el comportamiento a largo plazo del sistema. Se implementó también una simulación extendida al doble del tiempo original (modelo 2T), la cual demostró que el modelo es estable y capaz de realizar predicciones confiables más allá del rango de datos inicial. Finalmente, se representó el sistema mediante un esquema de gemelo digital, el cual permite simular su comportamiento dinámico bajo distintas condiciones iniciales o variaciones en los parámetros.
Este trabajo evidencia el potencial del modelado matemático como herramienta para representar y analizar sistemas fisiológicos complejos, incluso sin conocimiento previo del contexto biológico, y sienta las bases para futuras aplicaciones en simulación biomédica y desarrollo de gemelos digitales más avanzados.


## Objetivos específicos
1.-Importar y organizar datos experimentales recolectados durante un periodo de 63 días para su posterior análisis computacional.
2.-Aplicar técnicas de suavizado de datos para reducir el ruido experimental y facilitar el ajuste preciso del modelo.
3.-Formular un sistema de ecuaciones diferenciales no lineales que represente la dinámica temporal de tres variables fisiológicas interdependientes.
4.-Estimar los parámetros del modelo mediante regresión no lineal basada en datos experimentales suavizados.
5.-Evaluar la calidad del ajuste del modelo utilizando métricas estadísticas como el coeficiente de determinación y el AIC corregido.
6.-Analizar la sensibilidad del sistema mediante el cálculo de la matriz Jacobiana, para identificar la influencia de cada variable sobre las demás.
7.-Determinar los puntos de equilibrio del sistema, tanto triviales como no triviales, a partir del análisis algebraico de las ecuaciones del modelo.
8.-Realizar simulaciones extendidas (modelo 2T) para comprobar la estabilidad y comportamiento predictivo del sistema más allá del intervalo original de datos.
9.-Representar gráficamente los resultados del modelo, incluyendo comparaciones entre los datos observados, suavizados y simulados.
10.-Diseñar un esquema conceptual tipo gemelo digital, que ilustra la estructura del modelo y las relaciones entre variables mediante ecuaciones generales con parámetros simbólicos.



## Docente
Dr. Paul A. Valle

Posgrado en Ciencias de la Ingeniería [PCI] y Departamento de Ingeniería Eléctrica y Electrónica [DIEE], Tecnológico Nacional de México/IT Tijuana. Blvd. Alberto Limón Padilla s/n, Tijuana, C.P. 22454, B.C., México. Email: paul.valle@tectijuana.edu.mx

## Lecturas
[1] Paul. A. Valle, Syllabus de Biomatemáticas para la asignatura de Gemelos Digitales, Tecnológico Nacional de México/IT Tijuana, Tijuana, B.C., México, 2025. Permalink: https://www.dropbox.com/s/6yf9afxzih9y458/Biomatematicas.pdf



