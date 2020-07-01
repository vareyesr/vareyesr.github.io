---
permalink: /research/
title: "Áreas de Investigación"
author_profile: true
redirect_from: 
  - /md/
  - /research.html
---

## Problemas de Satisfacción y Optimización con restricciones

Los solvers branch & bound basados en intervalos son comunmente utilizados para resolver problemas continuos de satisfacción y optimización con restricciones de una manera _rigurosa_, es decir, toman en cuenta los errores de redondeo por las operaciones de punto flotante. Dos características diferencian a este tipo de solvers de otros:

* Toman en cuenta las incertidumbres en los valores de los parámetros y errores de cómputo sobre números de punto flotante
* Son capaces de trabajar en todo el espacio de búsqueda, dando pruebas de infeasibilidad y certificación de soluciones.

Para poder resolver problemas de satisfacción o de optimización con dominios continuos, los solvers basados en intervalos primero definen una caja n-dimensional, la cual representa el espacio de búsqueda inicial, utilizando para esto los dominios iniciales de las variables. Luego, a partir de esta caja inicial un árbol de búsqueda es generado alternando técnicas de bisección y de filtrado. La bisección consiste en seleccionar una de las variables y dividir su domino en la mitad, generando así dos nuevas sub-cajas. El método de filtrado consiste en remover valores de los bordes de los dominios de las variables que no son consistentes con alguna de las restricciones.

Algunos tópicos interesantes para estudiar son: 

## Sistemas dinámicos con incertidumbre

## Proyectos:

### Activos

### Finalizados

* Julio 2019 - Junio 202 -- "Contredo": Contracteurs pour les systèmes dynamiques Postdoc en el Laboratorio de Informatica, Robótica y de Microelectrónica de Montpellier (LIRMM), Montpellier, Francia. 
* Marzo 2016 - Abril 2019 Proyecto Fondecyt 11121366 “Symbolic Computation Techniques for Improving Interval-based Solvers.” como alumno de Doctorado.
* July 2013 - August 2014 - Proyecto Fondecyt 1160224 “New Methods for Improving Interval Branch & Bound Algorithms by Adapting Classical Techniques from Discrete to Continuous Domains.” como asistente de investigación.
