# pong-analogico-ie0408
Este es un repositorio dedicado al proyecto final del curso Laboratorio de Electrónica II IIIS2024, Universidad de Costa Rica, Escuela de Ingeniería Eléctrica.

## Descripción

**Ω–Pong** es una implementación analógica del clásico juego Pong utilizando circuitos electrónicos. El juego se visualiza en un osciloscopio en modo XY, utilizando señales sinusoidales generadas por un oscilador en cuadratura. Los circuitos controlan la pelota, las paletas, las colisiones, y el cambio de turno entre los jugadores, además de incluir indicadores visuales con LEDs.

Este proyecto fue desarrollado en el **Laboratorio de Electrónica II (IE-0408)** como parte del curso en el **III semestre de 2024**.

## Integrantes

- **Jose Andrés Guerrero Álvarez** - B63162
- **Roger Daniel Piovet García** - C15990

## Objetivos

### Objetivo General

Diseñar e implementar un circuito electrónico que permita jugar una versión analógica del clásico juego Pong utilizando la pantalla de un osciloscopio en modo XY.

### Objetivos Específicos

- Desarrollar un oscilador en cuadratura que genere las señales sinusoidales necesarias para representar la pelota y las paletas en el osciloscopio.
- Integrar circuitos de control de colisiones y dirección para simular el rebote de la pelota en las paletas y los límites de la pantalla.
- Implementar un sistema de control de turnos e indicadores visuales mediante LEDs para identificar el turno de cada jugador durante el juego.

## Diagrama de Bloques

El diagrama de bloques muestra los componentes y cómo interactúan para hacer funcionar el juego de Pong. Se incluye un oscilador en cuadratura, circuitos de desfasadores, comparadores, flip-flops, y más, para controlar la dirección de la pelota, las paletas, y la visualización en la pantalla.

## Diseño

El diseño del circuito incluye varias etapas, desde la generación de las señales sinusoidales hasta el control de las colisiones y la dirección de la pelota:

1. **Oscilador en cuadratura:** Genera las señales necesarias para la visualización de la pelota y las paletas.
2. **Circuitos desfasadores y comparadores ajustables:** Controlan la dirección y las colisiones de la pelota con las paletas y los límites de la pantalla.
3. **Control de dibujo de paletas:** Permite el control de las paletas por los jugadores.
4. **Multiplexores analógicos y sumadores:** Para seleccionar las señales y sumarlas adecuadamente.
5. **Control de turnos e indicadores con LEDs:** Muestra el turno del jugador actual.

## Referencias

- **[1]** "Manual de Diseño de Circuitos Electrónicos," Profesor Víctor H. Granados, 2024.
- **[2]** “Analog Oscilloscope Pong,” *Electronixandmore*. J. Stanley (2024), [https://www.electronixandmore.com/projects/scopepong/index.html](https://www.electronixandmore.com/projects/scopepong/index.html).

## Instalación

Para replicar el proyecto, necesitarás los siguientes materiales y herramientas:

1. Un osciloscopio con modo XY.
2. Los componentes electrónicos listados en la documentación del proyecto.
3. Herramientas básicas de electrónica (protoboard, cables, etc.).

