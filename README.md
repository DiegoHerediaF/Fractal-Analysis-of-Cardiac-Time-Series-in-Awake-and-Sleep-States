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

De todas las series de tiempo se obtuvo un promedio $\mu$ y desviación estándar $\sigma$ como medidas para cuantificar cambios globales en la frecuencia cardiaca y su amplitud, tanto en el sueño como en la vigilia. los resultados del promedio de estas medidas dentro de la población, para cada altitud y estado se muestra en la **figura 1** para $\mu$, y en la **figura 2** para $\sigma$.

![image](https://github.com/DiegoHerediaF/Fractal-Analysis-of-Cardiac-Time-Series-in-Awake-and-Sleep-States/blob/1b915575f7ced2f3dbd7c8d9eadd121a690ca513/figuras/series/promedios_intervalos_RR.png)

**Figure 1.** Promedio de los intervalos RR extraidos de las series de tiempo cardiacas.

![image](https://github.com/DiegoHerediaF/Fractal-Analysis-of-Cardiac-Time-Series-in-Awake-and-Sleep-States/blob/1b915575f7ced2f3dbd7c8d9eadd121a690ca513/figuras/series/variaciones_intervalos_RR.png)

**Figure 2.** Desviacion estandar promedio de los intervalos RR extraidos de las series de tiempo cardiacas.

## Relative Dispersion

Para el calculo de la dispersión relativa, se sigue la metodología de dividir las series en intervalos iguales, calculando la desviación estándar y el promedio de los datos de acuerdo a la partición dada por el número de agregación $n$. Las curvas de dispersión relativa se ven afectadas naturalmente por la longitud de los datos que se consideran, pues al aumentar el número de agregación, las particiones con las que se cuenta disminuyen, y llega un punto donde la curva pierde su comportamiento regular a causa del número reducido de muestras que se pueden extraer de las series.

### Experimental Time Series

Para cada persona, se realizó una gráfica por altitud de las tres series de tiempo asociadas al sueño y la vigilia, donde se muestra, en escala log-log, la curva de dispersión relativa, de la cual se extrae la dimensión fractal y el exponente de Hurst; las figuras se pueden consultar en la carpeta de 'figuras/dispersion_relativa'. El promedio y desviaciones estándar del exponente de Hurst dentro de la población, para cada altitud y estado se muestra en la **figura 3**.

![image](https://github.com/DiegoHerediaF/Fractal-Analysis-of-Cardiac-Time-Series-in-Awake-and-Sleep-States/blob/a96d97b0eda71c559e32ab0c0477deb7c41e721a/figuras/hurst/hurst_RD.png)

**Figure 3.** Exponentes de Hurst promedio de las series de tiempo experimentales.

### Randomized Time Series (Surrogate Data)

Para cada persona, se realizó una gráfica por altitud de las tres series de tiempo asociadas al sueño y la vigilia aleatorizadas, donde se muestra, en escala log-log, la curva de dispersión relativa, de la cual se extrae la dimensión fractal y el exponente de Hurst; las figuras se pueden consultar en la carpeta de 'figuras/surrogate_data'. El promedio y desviaciones estándar del exponente de Hurst dentro de los datos aleatorizados, para cada altitud y estado se muestra en la figura \ref{fig:randomhursts}.

![image](https://github.com/DiegoHerediaF/Fractal-Analysis-of-Cardiac-Time-Series-in-Awake-and-Sleep-States/blob/a96d97b0eda71c559e32ab0c0477deb7c41e721a/figuras/hurst/surrogate_hurst_RD.png)

**Figure 4.** Exponentes de Hurst promedio de las series de tiempo aleatorizadas.

## Conclusions

- El sueño-N2 y la post-siesta se caracterizaron por ser los estados con menor y mayor frecuencia cardiaca respectivamente.

- Las series de tiempo, tanto para los estados de vigilia, así como para el sueño-N2 corresponden a un proceso aleatorio fractal de carácter no lineal. 

- De acuerdo a los exponentes de Hurst y la dimensión fractal calculadas, el estado de Sueño-N2 se caracteriza por tener las series de tiempo con mayor variabilidad de la frecuencia cardiaca.

- La frecuencia cardiaca parece aumentar conforme la altitud aumenta, conservando el orden sueño-N2, pre-siesta y post-siesta; sin embargo, es necesario profundizar en la relación e influencia de la altitud con la frecuencia cardiaca.

- Según los exponentes de Hurst y la dimensión fractal calculadas, el estado de Pre-Siesta se caracteriza por tener, en dos de las tres altitudes, excepto para $4000m$ snm, la menor variabilidad de la frecuencia cardiaca.

- La variabilidad de la frecuencia cardiaca, para una misma población de sujetos, disminuye para los estados de sueño y vigilia conforme la altitud aumenta.
