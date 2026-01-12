# Transición de los sistemas de calefacción en Suiza

Este proyecto analiza la **evolución de los sistemas de calefacción residencial en Suiza**, con especial atención al papel de las **bombas de calor**, la influencia del **clima** y la **eficiencia energética** del parque residencial en las últimas dos décadas.

El trabajo combina análisis de datos, visualización interactiva y una narrativa orientada a entender la transición energética desde una perspectiva territorial.

---

##  Objetivos del proyecto

### 1. Evolución de los sistemas de calefacción
- Analizar cómo ha cambiado el uso de los distintos sistemas de calefacción en Suiza en los últimos años.
- Evaluar el papel de las **bombas de calor** dentro de la transición energética.

### 2. Distribución territorial
- Identificar qué cantones presentan mayor adopción de bombas de calor.
- Analizar las diferencias regionales en función del territorio, el clima y la estructura urbana.

### 3. Clima y demanda energética
- Estudiar la variabilidad de los **Heating Degree Days (HDD)** entre regiones.
- Analizar la relación entre clima y consumo energético residencial para calefacción.

### 4. Eficiencia energética
- Evaluar si el consumo de calefacción ajustado por clima ha mejorado en el tiempo.
- Analizar si los cantones con mayor uso de bombas de calor presentan mejores indicadores de eficiencia.
- Explorar si la adopción de bombas de calor contribuye a reducir el uso de energías fósiles.

---

## Visualización interactiva (resultado final)

El resultado principal del proyecto es una **historia interactiva** creada con Flourish, que integra todas las visualizaciones desarrolladas:

**Accede a la historia aquí:**  
[Visualización en Flourish](https://public.flourish.studio/story/3546453/)

La historia incluye:
- Evolución temporal de los sistemas de calefacción
- Comparaciones cantonales
- Mapas de distribución territorial
- Relación entre clima (HDD) y consumo energético
- Indicadores de eficiencia energética

---

## Datos utilizados

Los datos provienen principalmente de fuentes oficiales suizas:

- **Federal Statistical Office (FSO / BFS)**  
  - Sistemas de calefacción en edificios residenciales
- **MeteoSwiss (SMN)**  
  - Heating Degree Days (HDD) y Cooling Degree Days (CDD)

Los datos han sido procesados y normalizados para permitir comparaciones temporales y territoriales.

---

## Metodología

1. Limpieza y transformación de datos originales
2. Agregación por cantón y año
3. Cálculo de proporciones y métricas normalizadas por clima
4. Preparación de datasets específicos para visualización en Flourish
5. Construcción de una narrativa basada en evidencia empírica

---

## Estructura del proyecto

```text
visualizaciones-practica/
├── data/
│   ├── data_info/              
│   ├── energy/
│   │   └── processed/
│   ├── heating_systems/
│   │   ├── raw/
│   │   └── processed/
│   └── meteo/
│       ├── raw/
│       ├── processed/
│       ├── smn_daily_by_station/
│       └── smn_daily_historical_by_station/
├── practica.ipynb
├── requirements.txt
├── README.md
└── .gitignore
```

## Requisitos técnicos

El análisis se ha realizado en Python.

Para reproducir el entorno:

```bash
pip install -r requirements.txt
```

## Principales conclusiones

Las bombas de calor muestran una clara tendencia de crecimiento en la mayoría de cantones.

Existen diferencias territoriales importantes asociadas al clima, la topografía y el contexto urbano.

El consumo de calefacción ajustado por clima sugiere mejoras progresivas en eficiencia energética.

La sustitución de sistemas fósiles no es homogénea y presenta ritmos distintos según el cantón.

## Licencia

Este proyecto se distribuye bajo la licencia MIT y ha sido desarrollado como
parte de una Práctica de Evaluación Continua (PEC).  
Consulta el archivo `LICENSE` para más información.

## Autor

Proyecto realizado por Francisco Castro García
