# Variabilidad de la Frecuencia Cardiaca usando la Transformada Wavelet 

## Descripción

## Desarrollo
### a) Fundamento Teórico
1. Actividad simpática y parasimpática del sistema nervioso autónomo 
El sistema nervioso autónomo (SNA) regula funciones involuntarias como la frecuencia cardíaca, la digestión y la respiración. Se divide en:   
- Sistema simpático:   
  - Activado en situaciones de estrés o alerta ("lucha o huida").   
  - Aumenta la frecuencia cardíaca, dilata las pupilas y reduce la digestión.   
  - Libera noradrenalina y adrenalina.   
- Sistema parasimpático:   
  - Dominante en estados de reposo ("descanso y digestión").   
  - Disminuye la frecuencia cardíaca, estimula la digestión y contrae las pupilas.   
  - Libera acetilcolina.   

El balance entre ambos sistemas influye en la variabilidad de la frecuencia cardíaca (HRV), medida a través de los intervalos R-R en el ECG.   

2. Efecto de la actividad simpática y parasimpática en la frecuencia cardíaca 
- Activación simpática:   
  - Aumenta la frecuencia cardíaca (taquicardia).   
  - Reduce la HRV (los latidos son más regulares bajo estrés).   
- Activación parasimpática:   
  - Disminuye la frecuencia cardíaca (bradicardia).   
  - Aumenta la HRV (mayor variabilidad en reposo).   
Ejemplo:   
- Durante el ejercicio → Predomina el sistema simpático → ↑ Frecuencia cardíaca. 
- En reposo → Predomina el parasimpático → ↓ Frecuencia cardíaca pero ↑ HRV.   

3. Variabilidad de la Frecuencia Cardíaca (HRV) y análisis del intervalo R-R 
La HRV es una medida de las variaciones en los intervalos de tiempo entre latidos consecutivos (R-R en el ECG),es un indicador no invasivo del estado del sistema nervioso autónomo. 
Frecuencias de interés: 
Baja frecuencia (0.04–0.15 Hz): mezcla de actividad simpática y parasimpática. 
Alta frecuencia (0.15–0.4 Hz): refleja principalmente actividad parasimpática. 
Métodos de análisis:   
- Dominio del tiempo: Desviación estándar de los intervalos R-R (SDNN).   
- Dominio de la frecuencia: Transformada de Fourier o Wavelet para descomponer la señal.   
4. Transformada Wavelet: Definición y aplicación en señales biológicas**   
La transformada wavelet es una herramienta matemática para analizar señales no estacionarias (como el ECG).   
- Ventajas sobre la transformada de Fourier:   
  - Proporciona resolución temporal y frecuencial simultánea.   
  - Ideal para analizar HRV, donde la frecuencia varía con el tiempo.   
- Wavelets comunes en biofisica:   
  - Morlet: Buena resolución en frecuencia.   
  - Daubechies (db4/db6): Usada en procesamiento de ECG.   
  - Haar: Simple, útil para detección de picos R.   
Aplicación en HRV:   
- Permite analizar cómo cambian las componentes de baja frecuencia y alta frecuencia a lo largo del tiempo.   
- Detecta transiciones entre estados simpático/parasimpático.   
5. Diagrama de Flujo del Experimento**   
![alt]()


### b) Adquisición de la señal ECG  
### c) Pre-procesamiento de la señal 
### d) Análisis de la HRV en el dominio del tiempo 
### e) Aplicación de transformada Wavelet

## Instrucciones

## Requerimientos

## Referencias

## AUTORES
- Juan Diego Clavijo Fuentes
  est.juan.dclavijjo@unimilitar.edu.co
- Sofia Olivella Moreno
  est.sofia.olivella@unimilitar.edu.co
