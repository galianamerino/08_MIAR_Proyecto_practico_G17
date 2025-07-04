# 08_MIAR_Proyecto_práctico_G17

En este carpeta se muestran los resultados de diferentes experimentos llevados a cabo con el fin de estimar la parametrización más adecuada para nuestro proyecto y los objetivos deseados.

Debido al tamaño de los archivos de pesos de entrenamiento, éstos no se han podido subir directamente a GitHub, pero se pueden descargar de Google Drive desde los enlaces que se proporcionan con cada uno de los experimentos realizados.


## EXPERIMENTOS 1-2

En este experimento se va a estudiar el efecto del parámetro TRAIN_INTERVAL en los resultados del entrenamiento. Este parámetro determina cada cuántos pasos de acción se realiza un paso de entrenamiento de la red.

Se evalua el entrenamiento con:

[TRAIN_INTERVAL = 4 (Experimento 1)](https://drive.google.com/drive/folders/1nquB62HOrpGzSW3RK0QuQkLp_HNC7Kvp?usp=drive_link)

[TRAIN_INTERVAL = 14 (Experimento 2)](https://drive.google.com/drive/folders/1EKCU_uxZcq44p0a42pEW7ABt7ikYBitV?usp=drive_link)

[TRAIN_INTERVAL = 24 (Valor por defecto, Experimento 0)](https://drive.google.com/drive/folders/1vcvZ0RpZc-eQkcc56T_O_Vv8VamkydNX?usp=drive_link)



## EXPERIMENTOS 3-5

En este experimento se va a estudiar el efecto del parámetro LEARNING_RATE en los resultados del entrenamiento. Controla cómo de rápido se actualizan los pesos de la red durante el entrenamiento.

Se evalua el entrenamiento con:

[LEARNING_RATE = 0.00001 (Experimento 3)](https://drive.google.com/drive/folders/1WXv8zbBzK21SiL1ehSganBoEYBG42I8m?usp=drive_link)

[LEARNING_RATE = 0.00005 (Experimento 4)](https://drive.google.com/drive/folders/1RZhh8HDF-ZAg83YRtY8rB_0EUABFCert?usp=drive_link)

[LEARNING_RATE = 0.0001 (Experimento 5)](https://drive.google.com/drive/folders/1y6o5PNWUuzcaGxbM76S9wMuZlO6MFKgO?usp=drive_link)

[LEARNING_RATE = 0.00025 (Valor por defecto, Experimento 0)](https://drive.google.com/drive/folders/1vcvZ0RpZc-eQkcc56T_O_Vv8VamkydNX?usp=drive_link)


## EXPERIMENTOS 6-9

En este experimento se va a estudiar el efecto del parámetro GAMMA en los resultados del entrenamiento. Controla cuánto peso se le da a las recompensas futuras en comparación con las inmediatas.

Se evalua el entrenamiento con:

[GAMMA = 0.90 (Experimento 6)](https://drive.google.com/drive/folders/1iujYqNB4_dP6rqstZ7mu6TO9Ra4WUs3X?usp=drive_link)

[GAMMA = 0.92 (Experimento 7)](https://drive.google.com/drive/folders/1hZv1P-P0A7_Q-_3qMsXcC7ygbrkEoPva?usp=drive_link)

[GAMMA = 0.95 (Experimento 8)](https://drive.google.com/drive/folders/1sNbcVKuv7ScGmmDDZ6zS8vxpFQ2OFpGk?usp=drive_link)

[GAMMA = 0.97 (Valor por defecto, Experimento 0)](https://drive.google.com/drive/folders/1vcvZ0RpZc-eQkcc56T_O_Vv8VamkydNX?usp=drive_link)

[GAMMA = 0.99 (Experimento 9)](https://drive.google.com/drive/folders/1FR9csczlr44v5dTB4069hIsne26asJxX?usp=drive_link)


## EXPERIMENTOS 10-11

En este experimento se va a estudiar el efecto del parámetro TARGET_MODEL_UPDATE en los resultados del entrenamiento. Controla la frecuencia con la que se actualiza la red objetivo a partir de los pesos de la red principal.

Se evalua el entrenamiento con:

[TARGET_MODEL_UPDATE = 1000 (Experimento 10)](https://drive.google.com/drive/folders/1-P-9UOKGoEYC2DWayOVE9feJAOFnRIkm?usp=drive_link)

[TARGET_MODEL_UPDATE = 5000 (Experimento 11)](https://drive.google.com/drive/folders/1_XGu0bUjosi_cxQB-Q3yyEc_NpLBgtto?usp=drive_link)

[TARGET_MODEL_UPDATE = 10000 (Valor por defecto, Experimento 0)](https://drive.google.com/drive/folders/1vcvZ0RpZc-eQkcc56T_O_Vv8VamkydNX?usp=drive_link)

## EXPERIMENTO 12

El entorno de SpaceInvaders-v0 presenta 6 posibles acciones:

'NOOP' -> "No hacer nada"

'FIRE' -> "Disparar",

'RIGHT' -> "Mover a la derecha"

'LEFT' -> "Mover a la izquierda"

'RIGHTFIRE' -> "Mover a la derecha y disparar"

'LEFTFIRE' -> "Mover a la izquierda y disparar"

En este experimento se evalua la posibilidad de una estrategia de juego más agresiva en la cuál el agente dispara continuamente en cada una de sus acciones. Esto restringiría las acciones a solo 3, que serían las siguientes:

'FIRE' -> "Disparar",

'RIGHTFIRE' -> "Mover a la derecha y disparar"

'LEFTFIRE' -> "Mover a la izquierda y disparar"

Resumiendo, se evalua el entrenamiento con:

[6 acciones (Valor por defecto, Experimento 0)](https://drive.google.com/drive/folders/1vcvZ0RpZc-eQkcc56T_O_Vv8VamkydNX?usp=drive_link)

[3 acciones (Experimento 12)](https://drive.google.com/drive/folders/1mj0QkndWlR71mzeOCBSmz7x7RlbsN4_W?usp=drive_link)
