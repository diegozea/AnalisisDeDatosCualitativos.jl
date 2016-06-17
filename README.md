# AnalisisDeDatosCualitativos

[![Build Status](https://travis-ci.org/diegozea/AnalisisDeDatosCualitativos.jl.svg?branch=master)](https://travis-ci.org/diegozea/AnalisisDeDatosCualitativos.jl)

- **Unidad I.** *Variables, distribuciones y pruebas de hipótesis.*
 - [Variables aleatorias y funciones de distribución.](http://nbviewer.jupyter.org/github/diegozea/AnalisisDeDatosCualitativos.jl/blob/master/material/I.1.VariablesAleatoriasyFuncionesDeDistribucion.ipynb)
 - [Análisis descriptivo de datos.](http://nbviewer.jupyter.org/github/diegozea/AnalisisDeDatosCualitativos.jl/blob/96630dec6d6b0583e3793acf0fbda8413b03c210/material/I.2.AnalisisDescriptivoDeDatos.ipynb)

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
