# Actividad 07 - Encendiendo LED (Arduino) · Python (tkinter)

Programación Avanzada · 3° "N" · LIDTS · UNACH

Ventana de tkinter con dos botones que mandan un carácter por el puerto serie a un Arduino UNO:
**Encender LED** envía `a` y **Apagar LED** envía `b` (pin 13).

## Requisitos
- Python 3 con tkinter
- Librería `pyserial`
- VS Code con la extensión Python (`ms-python.python`)
- Arduino UNO con el sketch de `arduino/led_serial/led_serial.ino`

## Ejecutar
1. Sube el sketch al Arduino y revisa su puerto en el IDE de Arduino (en `led.py` está `COM7`; cámbialo si es otro).
2. Instala la librería y corre el programa (o abre la carpeta en VS Code y pulsa **F5**):

```
python -m venv .venv
.venv\Scripts\pip install -r requirements.txt
.venv\Scripts\python led.py
```
