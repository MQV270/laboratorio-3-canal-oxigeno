# Laboratorio N.° 3: Canal de medición de oxígeno

## Descripción

Este repositorio corresponde al desarrollo del Laboratorio N.° 3 del curso Taller de Equipos Biomédicos II.

El trabajo consiste en implementar una celda de oxígeno simulada mediante un ESP32 y un circuito amplificador con el integrado TL084N, como parte del estudio del canal de medición de oxígeno de una máquina de anestesia.

## Código fuente

El archivo disponible es:

- `simulador_o2.ino`: programa utilizado para generar la señal de la celda de oxígeno simulada mediante el ESP32.

## Hardware utilizado

- ESP32 DevKit V1 (ESP32-WROOM-32 con DAC).
- Resistencias para el divisor de tensión.
- Amplificador operacional TL084N.
- Capacitores cerámicos de 100 nF.
- Protoboard y cables jumper.

## Entorno de desarrollo

- Arduino IDE.
- Placa: ESP32 Dev Module.

## Comandos de simulación

El ESP32 se controla mediante el Monitor Serie del Arduino IDE, configurado a 115 200 baudios y con el final de línea «Nueva línea».

Los comandos utilizados durante la práctica son:

| Comando | Porcentaje de O₂ simulado |
|---|---:|
| `f0` | 0 % |
| `f21` | 21 % |
| `f50` | 50 % |
| `f100` | 100 % |

## Propósito del repositorio

Poner a disposición el archivo de código fuente utilizado durante la práctica, de manera que pueda consultarse como parte de la documentación del montaje experimental.

## Contexto académico

Curso: Taller de Equipos Biomédicos II.

Práctica: Laboratorio N.° 3 — Canal de medición de oxígeno de una máquina de anestesia: celda de O₂ y amplificador.
