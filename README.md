# Trabajo Fin de Máster

## Información
- **Alumno:** López Corbalán, Alberto
- **Curso:** 2025/2026


## Descripción

Este repositorio contiene la implementación y experimentación del TFM. El objetivo principal es analizar el comportamiento de distintas estrategias de Active Learning y modelos LLMs aplicados a entornos basados en juegos.

## Estructura del Repositorio

```text
TFM-MIA/
├── dataset/
│   └──complete_report_features_and_text_replay.csv      # 0. Datos del juego Shadowspect desarrollado por el MIT.  
│
├── TFM_completed_level.ipynb      						 # 1. Active Learning y LLMs en entornos tabulares.
├── TFM_textReplay_key_events.ipynb     	 		 	 # 2. XAI (Explainable AI) aplicado a los LLMs del juego Shadowspect.
├── TFM_help_assistant.ipynb       						 # 3. LLMs en diversos puntos de la traza de texto (textReplay).
└── TFM_help_assistant_segmented_by_puzzle.ipynb      	 # 4. LLMs segmentado por cada puzzle del juego Shadowspect.
           
```

## Instalación y Uso

El proyecto ha sido desarrollado para ejecutarse íntegramente en **Google Colab**, por lo que no es necesario realizar una instalación local de dependencias. No obstante, es necesario ejecutar el notebook en un entorno con GPU para los experimentos con LLMs.


