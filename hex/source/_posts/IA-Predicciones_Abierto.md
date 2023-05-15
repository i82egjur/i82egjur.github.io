---
title: Desglose del estado de algunos sistemas
cover_image: images/IAprediccionesAbierto.jpg
---


Es de relativa facilidad conocer el estado de los sistemas en el momento actual. Sin embargo, en una gran cantidad de escenarios, lo que nos interesa, no es saber como estamos ahora, sino conocer como estaremos luego. De esta forma, se busca una solución que permita tomar decisiones basandonos en predicciones sobre estados futuros de nuestros vehículos.

Estas predicciones se basan en 2 estrategias fundamentadas en el uso de machine learning y deep learning.

## Predicciones de las series temporales.

Mediante el uso de redes neuronales LSTM, y GRU, buscamos estimar los valores futuros de las series de datos de los vehículos basandonos en comportamientos pasados del mismo u otros vehículos. De esta forma, entre las predicciones y unas reglas que marcan los comportamientos más peligrosos, somos capaces de estimar con un error cuadrático medio bastante reducido.

## Estimación de la vida restante remanente.  
La otra estrategia afrontada, es la de la estimación de la vida restante remanente. Mediante la detección de anomalías, se han construido las curvas de degradación de la vida útil de los sistemas. En base a los datos de los distintos sensores, se construyen modelos de aprendizaje profundo que predigan cuanto queda para que se lleguen a valores cercanos a un fallo.