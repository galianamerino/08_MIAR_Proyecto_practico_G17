# 08_MIAR_Proyecto_práctico_G17

En esta carpeta se muestra un vídeo de demostración de una partida del juego utilizando el entrenamiento obtenido en el **Experimento 0**.

Testing for 1 episodes ...

Episode 1: reward: 33.000, steps: 1336

[VISUALIZAR VIDEO DE DEMOSTRACIÓN](https://drive.google.com/file/d/1AcNBPtPyaLfJa5vPxArUkGR9mi1fp33t/view?usp=drive_link)

                              

## Hiperparámetros
### Valores de referencia

* Tamaño de la imagen de observación

INPUT_SHAPE = (84, 84)        

* Número de observaciones que se agrupan juntas para formar la entrada del agente

WINDOW_LENGTH = 4           

### Hiperparámetros de la red
LEARNING_RATE = 0.00025

### Hiperparámetros del agente

* Factor de descuento para las recompensas futuras. Controla cuánto peso se le da a las recompensas futuras en comparación con las inmediatas

GAMMA = 0.97                  
                             
* Frecuencia con la que se actualiza el modelo objetivo

TARGET_MODEL_UPDATE = 10000   

* Número de pasos iniciales en los que el agente solo explora (elige acciones aleatorias) y no entrena la red.

NB_STEPS_WARMUP = 50000      

* Define cuántas transiciones (experiencias) puede almacenar como máximo el agente durante el entrenamiento.

REPLAY_MEMORY = 1000000 

* Número de muestras que el agente extrae de la memoria para una sola actualización de la red neuronal

BATCH_SIZE = 32             

* Determina cada cuántos pasos de acción se realiza un paso de entrenamiento de la red.

TRAIN_INTERVAL = 24          

* Valor utilizado para recortar los errores TD (diferencia temporal) durante el entrenamiento para evitar fluctuaciones extremas.

DELTA_CLIP = 1.0      

