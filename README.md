# Practica-2
Sistema de Control Ambiental con Arduino

Este proyecto implementa un sistema de monitoreo y control ambiental automatizado usando un Arduino. Está diseñado para gestionar la temperatura, humedad e iluminación de un entorno cerrado mediante sensores, actuadores y una pantalla LCD.

🔧 Funcionalidades principales:

Sensor DHT22: Mide temperatura y humedad.

LDR (fotoresistor): Mide el nivel de luz ambiente.

Control de temperatura: Enciende un sistema de calefacción o refrigeración según la temperatura medida, usando un sistema de control ON-OFF con zona muerta (±3 °C). Se basa en dos leds, uno rojo para la calefacción y una azul para la refrigeración.

Control de humedad: Activa un servomotor que abre o cierra una compuerta según los niveles de humedad (A partir del 80 % de humedad).

Control de iluminación: Usa un registro de desplazamiento (74HC595) para encender entre 0 y 8 LEDs dependiendo del nivel de luz (más LEDs cuando hay menos luz).

Pantalla LCD I2C: Muestra en tiempo real los valores de temperatura, humedad, luz y apertura de compuerta.

Interfaz Serial: Muestra por el monitor serie el ángulo de apertura de la compuerta para diagnóstico o registro.
