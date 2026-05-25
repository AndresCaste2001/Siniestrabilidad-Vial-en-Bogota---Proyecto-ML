<p align="center">
  <img src="Banner IA.png" alt="Banner Proyecto IA" width="100%"/>
</p>

# Caracterización de la Siniestralidad Vial en Bogotá

Proyecto de Machine Learning orientado al análisis y predicción de la severidad de accidentes de tránsito en la ciudad de Bogotá.


## Link del video de Youtube

https://youtu.be/oEqzdAQaxLA


## Participantes

| Nombre | Código |
|--------|--------|
| Laura Natalia Ballesteros Gualdron | 2221650 |
| Juan David Neira Meza | 2235605 |
| Eder Andres Castellanos Jerez | 2210051 |

---

## Objetivo

El objetivo de este análisis es caracterizar las variables del dataset de siniestralidad vial en Bogotá para construir un modelo de clasificación que permita predecir la **severidad** de un accidente de tránsito, clasificándolo en una de tres categorías:

- **Solo daños materiales**
- **Accidente con heridos**
- **Accidente con fallecidos**

---

## Dataset

El dataset está compuesto por variables categóricas codificadas numéricamente, relacionadas con actores viales, condiciones del entorno y características temporales del accidente.

- **Registros:** 35.693 accidentes
- **Variables:** 22
- **Fuente:** [Mendeley Data — Road Accident Bogotá](https://data.mendeley.com/datasets/rm9m7ycp3r/1)

A partir del análisis descriptivo, se evidencia que la mayoría de los accidentes corresponden a eventos con heridos, mientras que los accidentes fatales representan una proporción menor, lo cual sugiere un posible desbalance en las clases. Asimismo, gran parte de los accidentes involucran un solo vehículo, lo que indica que factores individuales pueden tener un papel relevante en la ocurrencia de siniestros.

### Variables del Dataset

**Actores Viales**
| Variable | Descripción |
|----------|-------------|
| Number of cars and buses | Número de carros y buses involucrados |
| Number of motorcyclists | Número de motociclistas involucrados |
| Number of cyclists | Número de ciclistas involucrados |
| Number of pedestrians | Número de peatones involucrados |
| Number of road actors | Total de actores viales involucrados |
| Relationship of road actors | Interacción entre actores (moto vs carro, moto vs peatón, etc.) |

**Motociclista / Individuos**
| Variable | Descripción |
|----------|-------------|
| Gender involved | Género de las personas involucradas |
| Number of men | Número de hombres involucrados |
| Number of women | Número de mujeres involucradas |
| Motorcyclist age (years) | Edad del motociclista involucrado |
| Other driver age (years) | Edad del otro conductor involucrado |

**Clima / Tiempo**
| Variable | Descripción |
|----------|-------------|
| Time (hours) | Hora del accidente |
| Day | Día del mes del accidente |
| Type of day | Tipo de día (laboral, fin de semana, festivo) |
| Month | Mes del año del accidente |
| Weather conditions (mm) | Precipitación registrada en milímetros |

**Vía / Localización**
| Variable | Descripción |
|----------|-------------|
| Road type | Tipo de vía (avenida, calle, autopista) |
| Location | Ubicación del accidente dentro de la ciudad |
| State of main road | Estado de la vía principal |
| State of intermediate road | Estado de vías intermedias cercanas |
| State of local road | Estado de vías locales o secundarias |

**Característica del Accidente**
| Variable | Descripción |
|----------|-------------|
| Accident class | Clase de accidente (choque, atropello, colisión) |
| Severity | Nivel de gravedad del accidente *(variable objetivo)* |

---

## Estructura del Proyecto

```
├── Proyecto.ipynb       # Notebook principal con análisis y modelos
├── DataSet.xlsx         # Dataset de accidentes viales en Bogotá
├── Banner IA.png        # Banner del proyecto
└── IA - PROYECTO.pdf    # Documento del proyecto
```

