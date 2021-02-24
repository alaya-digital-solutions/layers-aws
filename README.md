# tires-optimizer
[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

## setup del proyecto 
Este trabajo se desarrollará en dos ramas
-  main: rama de cara al cliente 
-  develop: rama de desarrollo en las cuales se comenzarán los desarrollos

Por lo tanto, todas las personas que contribuyan en el desarrollo del repo, deben hacer chechout a la rama de develop y trabjar única y exclusivamente en esta rama.
La rama main, no se tocará y solo se harán las transferencias vía Pull Request (PR), en el cual los owners del repo deberán aprobar. La idea es a corto plazo tener una instancia de CI/CD a través de github actions para hacer el deploy de los stacks, en donde el proceso de deploy esta totalmente automatizado y separado por ambientes de desarrollo.

Pasos a seguir para hacer ambiente de trabajo del producto
```sh
$ echo Es estrictamente necesario usar python 3.7 para hacer los deploys de stacks
git clone git@github.com:alaya-digital-solutions/tires-optimizer
$ cd tires-optimizer
$ echo instalar los requirements
$ pip install -r requirements.txt
```

## Introducción
Este será un software mantenimiento predictivo de neumaticos aplicados a camiones mineros, los objetivos son:
 - “Impacto según estudio de negocio… ahorro por camión en un año“
 - Mejora en planificación de mantenimiento 
 - Mejora en continuidad operacional asegurando control en condiciones límite
 - Aporte en excelencia operacional contribuyendo con seguimiento de conducción de operadores

## Modulos
 - Modulo Base: Tabla de mantenimiento de neumáticos, ordenados por vida remanente del activo y por caex
 - Modulo Alertas: Alertas personalizadas vía e-mail, con recomendaciones de futuras entradas a mantenimiento de los neumáticos. Alertas a tiempo real (baja de presión, aumento
   excesivo de temperatura, desbalance de carga, recorrido del neumático mayor al permitido u otra que pueda impactar el rendimiento o seguridad de los activos mina    
   involucrados)
 - Modulo Seguimiento de KPI’s: Curvas de evolución de uso del neumático en función de la actividad minera (distancia recorrida, inclinación de caminos, desgaste por fricción, tonelaje de mineral transportado, etc)
 - Modulo Control Operacional de Desgaste: Cuantificación del desgaste en neumáticos por conducción de operadores, seguimiento de mejora operacional (ejemplo: control de
   frenado)
   
 ## ¿Qué se necesita para trabajar? 
 
 -  Consola unix o emulador de consola unix, para windows (Ej: Cmder instalando el path de anaconda)
 
 
 
 
