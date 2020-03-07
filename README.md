## Klipper <3

Incluye una serie de apuntes redactados por maketo3D y una personalización del menu de la impresora en Klipper.

Hay tres archivos de printer.cfg, **leer con mucha atención**:

- printerA.cfg

Tal cual te viene la impresora, con extrusor de serie, fusor de serie, con todos los sensores de serie. Si no has personalizado nada en tu impresora Anycubic Kossel, ese es tu archivo.

- printerB.cfg

Para quienes hayan puesto los TMC2130 por SPI, pero el extrusor y el fusor es de serie.

- printerC.cfg

Es para aquella impresora que hayan instalado el termistor PT1000 y extrusor Bondtech y sonda es la de espuma, cuya separación es de 0.2 mm.

**Recordad**: a la hora de instalarlo en Klipper, el directorio debe ser /home/pi, y el archivo debe ser renombrado a printer.cfg.
