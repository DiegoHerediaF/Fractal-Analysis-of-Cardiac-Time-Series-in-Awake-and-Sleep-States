# Fractal-Analysis-of-Cardiac-Time-Series-in-Awake-and-Sleep-States

This project was realized by

Diego A Heredia F

Using hurst exponent and its relationship with fractal dimension H=2-D, cardiac time series at 3 different altitudes of 14 subjects, without any cardiopathy, are characterized in sleep and awake states. Using surrogate data method, it is also shown that these time series are temporally fractal.

## Description

Se estudian y caracterizan series de tiempo cardiacas a través del exponente de Hurst y la dimensión fractal, analizando mediante el método de la dispersión relativa, series de tiempo ECG de 14 sujetos despiertos y dormidos sin ninguna cardiopatía y a diferentes altitudes, evidenciando que el comportamiento de las fluctuaciones de los intervalos RR entre latidos en el corazón humano, se asocian con un proceso aleatorio fractal de carácter no lineal. Se caracterizan las series mediante herramientas de análisis no lineal relacionadas con la fractalidad del sistema, ya sea durante el sueño o la vigilia, a través de comparar las series de tiempo entre si y respecto al método de surrogate data.

En este trabajo se busca utilizar el exponente de Hurst y la dimensión Fractal, derivadas del método de la dispersión relativa, como medidas de la HRV para sueño y la vigilia, cuantificando para sujetos sanos y en un rango de edad especifico variaciones normales en la frecuencia cardiaca.

## Data 

Se utilizará una base de datos de 14 pacientes de los que se obtuvieron, a partir de ECGs, series de tiempo cardiacas $RR$ para estados de sueño y vigilia en tres locaciones diferentes: a $0m$ (A), $2600m$ (B) y $4000m$ (C) sobre el nivel del mar (snm). Por cada sujeto y altitud se tienen tres series con una duración aproximada de $5min$ (y una media de $200$ datos): pre-siesta (PRE), sueño-N2 (N2) y post-siesta (POS). Estos datos fueron proporcionados por el doctor [Alain Riveros Rivera](mailto:riveros-a@javeriana.edu.co), docente e investigador del departamento de ciencias fisiológicas, en la facultad de medicina de la pontificia universidad Javeriana.

## Characterization of Cardiac Time Series 

Se obtuvieron un total de $9$ series de tiempo por sujeto, resultando en un total de $126$ series teniendo en cuenta los $14$ participantes, $7$ de ellos hombres (M) y $7$ mujeres (F). Para cada persona, se realizó una gráfica por altitud de las tres series de tiempo asociadas al sueño y la vigilia, donde se muestra la longitud temporal de los intervalos $RR$ en función del número de latidos, con una linea horizontal que representa el promedio temporal de las series de tiempo asociadas a cada estado; las figuras se pueden consultar en la carpeta de 'figuras/series'.

De todas las series de tiempo se obtuvo un promedio $\mu$ y desviación estándar $\sigma$ como medidas para cuantificar cambios globales en la frecuencia cardiaca y su amplitud, tanto en el sueño como en la vigilia. los resultados del promedio de estas medidas dentro de la población, para cada altitud y estado se muestra en la figura \ref{fig:promedios} para $\mu$, y en \ref{fig:variaciones} para $\sigma$.

![image](https://github.com/DiegoHerediaF/Fractal-Analysis-of-Cardiac-Time-Series-in-Awake-and-Sleep-States/blob/1b915575f7ced2f3dbd7c8d9eadd121a690ca513/figuras/series/promedios_intervalos_RR.png)

**Figure 1.** Promedio de los intervalos RR extraidos de las series de tiempo cardiacas.

![image](https://github.com/DiegoHerediaF/Fractal-Analysis-of-Cardiac-Time-Series-in-Awake-and-Sleep-States/blob/1b915575f7ced2f3dbd7c8d9eadd121a690ca513/figuras/series/variaciones_intervalos_RR.png)

**Figure 2.** Desviacion estandar promedio de los intervalos RR extraidos de las series de tiempo cardiacas.




## Conclusions
