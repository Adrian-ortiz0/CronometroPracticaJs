# Cronómetro en JavaScript

Esta es una aplicación simple de cronómetro implementada en JavaScript que registra el tiempo transcurrido en horas, minutos, segundos y milisegundos.

## Características

- **Inicio:** Inicia el temporizador del cronómetro.
- **Detener:** Pausa el temporizador del cronómetro.
- **Reiniciar:** Reinicia el temporizador del cronómetro a cero.

## Implementación

La funcionalidad del cronómetro está implementada utilizando JavaScript y actualiza la visualización cada 10 milisegundos.

## Funciones

- **`start()`**
  - Inicia el temporizador del cronómetro si aún no está en ejecución.
  - Registra el tiempo de inicio y comienza a actualizar la visualización cada 10 milisegundos.

- **`stop()`**
  - Pausa el temporizador del cronómetro si está en ejecución.
  - Registra el tiempo transcurrido desde el inicio y detiene la actualización de la visualización.

- **`reset()`**
  - Detiene el temporizador del cronómetro si está en ejecución.
  - Reinicia todas las variables del temporizador (`startTime`, `elapsedTime`) a cero.
  - Establece la visualización de vuelta a "00:00:00:00".

- **`update()`**
  - Actualiza la visualización del cronómetro mostrando horas, minutos, segundos y milisegundos transcurridos.

## Uso

Para utilizar el cronómetro, puedes llamar a las funciones `start()`, `stop()` y `reset()` desde tu código JavaScript o desde eventos en la interfaz de usuario.

Este cronómetro es ideal para medir el tiempo transcurrido con precisión hasta milisegundos, útil para aplicaciones que requieren mediciones precisas de tiempo como competiciones, pruebas de rendimiento o simplemente para tener un temporizador preciso en tu página web.

