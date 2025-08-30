# "Taller1_BigData_MachineLearning": Predicción de Ingresos (GEIH 2018 - Bogotá)
Taller1_BigData_MachineLearning: Predicción de Ingresos (GEIH 2018 - Bogotá)

## 📌 Descripción
Este repositorio contiene el trabajo del **Taller1_BigData_MachineLearning** de Econometría Aplicada (Maestría en Economía Aplicada).  
El objetivo es **estimar y predecir salarios horarios** en Bogotá usando la **GEIH 2018**.  
El análisis incluye:
- Perfil edad–salario.  
- Brecha salarial de género (incondicional y condicional, FWL y bootstrap).  
- Modelos de predicción y validación (RMSE y LOOCV).  
---
## 📂 Estructura del repositorio

El repositorio sigue la plantilla solicitada en el enunciado:
- data_equipo_XX/  ---->    # Carpeta con los scripts y limpieza de datos
- age_equipo_XX/   ---->    # Carpeta con los resultados del perfil edad-salario
- gap_equipo_XX/   ---->    # Carpeta con los resultados de la brecha de género
- pred_equipo_XX/  ---->    # Carpeta con los resultados de predicción
- slides/ ---->              # Carpeta con las presentaciones en PDF
- output/      ---->        # Carpeta donde se guardan tablas y gráficos finales
- scripts/          ---->   # Carpeta con el código en R


## 🔄 Cómo correr el proyecto
1. Clonar el repositorio:
   ```bash
   git clone https://github.com/LauraDaniela17/Taller1_BigData_MachineLearning.git
   cd Taller1_BigData_MachineLearning
  
## 📊 Resultados principales
- El salario crece con la edad hasta un pico cercano a los 50 años.
- Existe brecha salarial de género, que se reduce al controlar por educación y ocupación, pero no desaparece.
- Los modelos más complejos (polinomios, LASSO, Random Forest) predicen mejor que los modelos lineales simples.

## 👥 Equipo
- Cristian Felipe Muñoz Guerrero 
- Zeneth Olivero Tapia
- Laura Daniela Torres Diaz
- Vivian Cabanzo Fernandez

Cada miembro aportó al menos cinco contribuciones al repositorio.

## 📚 Referencias
- DANE – Gran Encuesta Integrada de Hogares (GEIH) 2018.
- Wooldridge, J. M. Econometric Analysis of Cross Section and Panel Data. MIT Press.
