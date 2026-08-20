# Fundamentos de mecánica de suelos

Notas y herramientas para el curso de pregrado **Fundamentos de Mecánica de Suelos** de la Universidad EAFIT, organizadas como un Jupyter Book.

[![Jupyter Book](https://img.shields.io/badge/Jupyter_Book-ver_sitio-F37726?style=for-the-badge&logo=jupyter&logoColor=white)](https://appliedmechanics-eafit.github.io/soil_mechanics/)

## Uso local

Con el entorno ubicado en `/home/eamontoyaa/.venvs/EAFIT-uv/`:

```bash
source /home/eamontoyaa/.venvs/EAFIT-uv/bin/activate
pip install -r requirements.txt
jupyter book build --html --strict
```

El sitio se genera en `_build/html`. Los notebooks también pueden abrirse individualmente desde el contenido siguiente.

## Contenido

**El suelo como un medio poroso multifásico**

1. [Superficie específica](https://nbviewer.org/github/AppliedMechanics-EAFIT/soil_mechanics/blob/main/notebooks/specific_surface.ipynb) 
1. [Distribución de tamaños de partícula](https://nbviewer.org/github/AppliedMechanics-EAFIT/soil_mechanics/blob/main/notebooks/particle_size_distrib.ipynb)
1. [Sistema de clasificación unificada de suelos - USCS](https://nbviewer.org/github/AppliedMechanics-EAFIT/soil_mechanics/blob/main/notebooks/uscs_classification.ipynb)

**Conceptos de la Mecánica Aplicada en Medios Porosos**

1. [Esfuerzos verticales totales y efectivos en suelos estratificados](https://nbviewer.org/github/AppliedMechanics-EAFIT/soil_mechanics/blob/main/notebooks/stress_vs_depth.ipynb)
1. [Círculo de Mohr y círculo de tracciones](https://nbviewer.org/github/AppliedMechanics-EAFIT/soil_mechanics/blob/main/notebooks/mohr_circles.ipynb)  
1. [Círculo de Mohr vs trayectorias de esfuerzos](https://nbviewer.org/github/AppliedMechanics-EAFIT/soil_mechanics/blob/main/notebooks/mohr_circles_and_stress_paths.ipynb)

**Flujo de Agua a Través del Suelo**

1. [Infiltración unidimensional de lluvia](https://nbviewer.org/github/AppliedMechanics-EAFIT/soil_mechanics/blob/main/notebooks/rainfall_infiltration_1D.ipynb)
1. [Redes de flujo bidimensionales](https://nbviewer.org/github/AppliedMechanics-EAFIT/soil_mechanics/blob/main/notebooks/steady_flow_2D.ipynb)

**Respuesta Hidro-Mecánica de Geomateriales**

1. [Consolidación unidimensional](https://nbviewer.org/github/AppliedMechanics-EAFIT/soil_mechanics/blob/main/notebooks/consolidation_1D.ipynb)
1. [Esfuerzo de preconsolidación o de fluencia](https://nbviewer.org/github/AppliedMechanics-EAFIT/soil_mechanics/blob/main/notebooks/preconsol_pressure.ipynb)

## Licencia

El contenido de este repositorio está licenciado bajo una licencia
[Creative Commons Attribution 4.0](http://choosealicense.com/licenses/cc-by-4.0/),
y el código fuente que le acompaña bajo una
[licencia MIT](https://opensource.org/licenses/mit-license.php).

© 2023 Daniel F. Ruiz, Exneyder A. Montoya-Araque & Universidad EAFIT.
