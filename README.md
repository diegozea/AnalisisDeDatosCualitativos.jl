# AnalisisDeDatosCualitativos

[![Build Status](https://travis-ci.org/diegozea/AnalisisDeDatosCualitativos.jl.svg?branch=master)](https://travis-ci.org/diegozea/AnalisisDeDatosCualitativos.jl)

### Material

Las *notebooks* se encuentran en la carpeta `material`

- **Unidad I.** *Variables, distribuciones y pruebas de hipótesis.*
 - [Variables aleatorias y funciones de distribución.](http://nbviewer.jupyter.org/github/diegozea/AnalisisDeDatosCualitativos.jl/blob/master/material/I.1.VariablesAleatoriasyFuncionesDeDistribucion.ipynb)  
 - [Análisis descriptivo de datos.](http://nbviewer.jupyter.org/github/diegozea/AnalisisDeDatosCualitativos.jl/blob/96630dec6d6b0583e3793acf0fbda8413b03c210/material/I.2.AnalisisDescriptivoDeDatos.ipynb)  
 - [Prueba de Hipótesis. Verificación estadística de hipótesis estadística.](http://nbviewer.jupyter.org/github/diegozea/AnalisisDeDatosCualitativos.jl/blob/master/material/I.3.PruebaDeHipotesis.ipynb)  
 - [Independencia de variables y medidas de asociación.](http://nbviewer.jupyter.org/github/diegozea/AnalisisDeDatosCualitativos.jl/blob/master/material/I.4.IndependenciaDeVariablesyMedidasDeAsociacion.ipynb)  
- **Unidad II.** Regresiones y reducción de dimensionalidad.  
 - [Planteamiento del problema de regresión en forma general.](http://nbviewer.jupyter.org/github/diegozea/AnalisisDeDatosCualitativos.jl/blob/master/material/II.1.Regresion.ipynb)  
 - [Regresión Lineal Múltiple por el método de los Mínimos Cuadrados.](http://nbviewer.jupyter.org/github/diegozea/AnalisisDeDatosCualitativos.jl/blob/master/material/II.2.RegresionLinealMultiple.ipynb)  
 - [Análisis de Regresión Logística.](http://nbviewer.jupyter.org/github/diegozea/AnalisisDeDatosCualitativos.jl/blob/master/material/II.3.RegresionLogistica.ipynb)  
 - [Análisis de la varianza.](http://nbviewer.jupyter.org/github/diegozea/AnalisisDeDatosCualitativos.jl/blob/master/material/II.4.ANOVA.ipynb)  
 - [Reducción de datos.](http://nbviewer.jupyter.org/github/diegozea/AnalisisDeDatosCualitativos.jl/blob/master/material/II.5.ReduccionDeDatos.ipynb)  
 - [El análisis de varianza multivariado.](http://nbviewer.jupyter.org/github/diegozea/AnalisisDeDatosCualitativos.jl/blob/master/material/II.6.ANOVAMultivariado.ipynb)  
- **Unidad III.** Agrupamiento y clasificación.  
 - [El análisis discriminante y modelos Log-lineales.](http://nbviewer.jupyter.org/github/diegozea/AnalisisDeDatosCualitativos.jl/blob/master/material/III.1.AnalisisDiscriminante.ipynb)  
 - [Clustering](http://nbviewer.jupyter.org/github/diegozea/AnalisisDeDatosCualitativos.jl/blob/master/material/III.2.Clustering.ipynb)  
 - [Árboles de decisión.](http://nbviewer.jupyter.org/github/diegozea/AnalisisDeDatosCualitativos.jl/blob/master/material/III.3.ArbolesDeDecision.ipynb)  

### Trabajos prácticos

Las *notebooks* se encuentran en la carpeta `trabajo`

- [TPI](http://nbviewer.jupyter.org/github/diegozea/AnalisisDeDatosCualitativos.jl/blob/fc9f5ed5f984672e17150f5ebd32e29ad3f85220/trabajos/TPI.ipynb)

### Material Extra

#### Julia

- [Introducción al lenguaje](http://nbviewer.jupyter.org/format/slides/github/diegozea/ADayWithJulia/blob/master/EstudiantesBioinfo2016/Introduccion_a_Julia.ipynb#/)
- [Paneo general de JuliaStats](http://nbviewer.jupyter.org/format/slides/github/diegozea/ADayWithJulia/blob/master/EstudiantesBioinfo2016/Analisis_de_datos.ipynb#/)

Video tutoriales del lenguaje Julia

- SciPy 2014: David Sanders - Introduction to Julia
 - [Parte I](https://youtu.be/vWkgEddb4-A)
 - [Parte II](https://youtu.be/I3JH5Bg46yU)
- [Workshop 2015: David Sanders - Introduction to Julia for scientific Computing](https://youtu.be/gQ1y5NUD_RI)


### Errata

[Errata](http://nbviewer.jupyter.org/github/diegozea/AnalisisDeDatosCualitativos.jl/blob/96630dec6d6b0583e3793acf0fbda8413b03c210/material/Errata.ipynb) contiene aclaraciones a errores o dudas surgidas durante las clases

### Nota: Plots & PyPlot

Si al usar Plots observan dos plots por cada comando en las *Jupyter notebooks* , pueden momentáneamente solucionar el problema haciendo:

```julia
Pkg.rm("PyPlot")
Pkg.clone("https://github.com/tbreloff/PyPlot.jl.git")
Pkg.checkout("PyPlot", "tb_dispfix")
Pkg.update()
```

### [XKCD](http://xkcd.com/)

- [Heatmap](https://www.explainxkcd.com/wiki/index.php/1138:_Heatmap)
- [Significant](https://www.explainxkcd.com/wiki/index.php/882:_Significant)
- [P-Values](https://www.explainxkcd.com/wiki/index.php/1478:_P-Values)
- [Null Hypothesis](https://www.explainxkcd.com/wiki/index.php/892:_Null_Hypothesis)
- [Extrapolating](Extrapolating)
- [Correlation](https://www.explainxkcd.com/wiki/index.php/552:_Correlation)
- [Conditional Risk](https://www.explainxkcd.com/wiki/index.php/795:_Conditional_Risk)
- [Cell Phones](https://www.explainxkcd.com/wiki/index.php/925:_Cell_Phones)
- [Frequentists vs. Bayesians](https://www.explainxkcd.com/wiki/index.php/1132:_Frequentists_vs._Bayesians)
