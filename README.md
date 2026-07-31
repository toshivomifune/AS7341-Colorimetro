# Colorímetro Espectral AS7341 + ESP32 + TFT ST7796

## Descripción

Proyecto de un colorímetro espectral basado en un **ESP32**, el sensor
**DFRobot AS7341** y una pantalla **TFT SPI ST7796 de 4 pulgadas
(480x320)**.

### Funciones

-   Lectura de los 10 canales espectrales.
-   Detección aproximada de colores.
-   Visualización del color detectado.
-   Barras espectrales F1--F8.
-   Valores Clear y NIR.
-   Consola serial.

## Hardware

### ESP32

-   ESP32 DevKit V1 (30 pines)

### Sensor

-   DFRobot AS7341

### Pantalla

-   ST7796 SPI
-   480 × 320
-   4.0"

## Conexiones

### AS7341

  Señal   ESP32
  ------- --------
  VCC     3V3
  GND     GND
  SDA     GPIO21
  SCL     GPIO22

### TFT

  Señal   ESP32
  ------- --------
  VCC     5V
  GND     GND
  CS      GPIO5
  RESET   GPIO4
  DC      GPIO2
  MOSI    GPIO23
  MISO    GPIO19
  SCK     GPIO18
  LED     3V3

## Software

-   Arduino IDE 2.x
-   GFX Library for Arduino
-   DFRobot_AS7341

## Próximas etapas

-   Calibración con patrones de color.
-   Algoritmo CIE Lab.
-   Registro en microSD.
-   Exportación CSV.
-   Interfaz gráfica mejorada.

## Licencia

MIT (recomendado) o la que el autor decida.

------------------------------------------------------------------------

Autor: Gustavo Adolfo Ramírez Piedrahita
