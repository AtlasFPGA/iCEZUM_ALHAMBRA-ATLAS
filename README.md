# iCEZUM_ALHAMBRA-ATLAS
# Adaptar la placa I/O BOARD ATLAS a la placa iCEZUM ALHAMBRA de 1Kle:

Group ATLAS in Telegram: https://t.me/INICIATIVAATLAS

Se añade el siguiente esquemario de dispositivos para practicar con la iCEZUM ALHAMBRA.

señales ATLAS| aclaración en iCEZUM ALHAMBRA | numero pines
| :--- | ---: | :---:
QPI SPRAM | 6 señales para un Quad SPI de 4 bits| 6
Señal VGA64 |Usamos en la iCEZUM ALHAMBRA un esquema de 8colores 111+HS+VS | 8
Señal JOYSTICK DB9 | En preparación ATARI-PADDLE-ATLAS  | 6
Señal SD SPI | las señales QPI se usan en modo SPI| 4
Señal PS2 TECLADO  | Protocolo PS/2 | 2
Señal PS2 RATÓN | Protocolo PS/2 | 2
Señal Sonido Estereo | sonido delta sigma_(12bits) o un pwm_(10bits)| 2
Señal Transmisión  | TX sin gestión de flujo para MIDI| 1
Señal EAR | Señal de entrada | 1
Señal COMPOSITE | PAL 512Colores | 2

---


## Diseño de la PCB para la iCEZUM ALHAMBRA:

![Diseño de la PCB para la iCEZUM ALHAMBRA](https://github.com/AtlasFPGA/iCEZUM_ALHAMBRA-ATLAS/blob/main/FOTOS/iCEZUM_ALAMBRA-ATLAS-PCB.png)

## Esquema de adaptación para la iCEZUM ALHAMBRA:

![Esquema de adaptación para la iCEZUM ALHAMBRA](https://github.com/AtlasFPGA/iCEZUM_ALHAMBRA-ATLAS/blob/main/FOTOS/iCEZUM_ALAMBRA-ATLAS-ESQUEMA-BETA-I.png)


---
A 23-ABRIL-2023 tenemos los siguientes precios de la memoria QSPI de 64Mbit o 8Mbytes:

Versión a +1V8 166Mhz.

https://www.gridconnect.com/products/esp-psram-64-for-wroom-32-and-esp32

Versión a +3v3 133Mhz.

https://www.gridconnect.com/products/esp-psram-64-for-wroom-32-and-esp32?variant=39313950244887

https://protosupplies.com/product/psram/

Vemos que es la más extendida dado que la presueldan en las placas Teensy:

https://protosupplies.com/product/psram/


---

## Cara superior

![Cara superior](https://github.com/AtlasFPGA/iCEZUM_ALHAMBRA-ATLAS/blob/main/FOTOS/iCEZUM_ALHAMBRA-ATLAS-3D-SUPERIOR.jpg)

---

## Perspectiva inclinada superior

![Perspectiva inclinada superior](https://github.com/AtlasFPGA/iCEZUM_ALHAMBRA-ATLAS/blob/main/FOTOS/iCEZUM_ALHAMBRA-ATLAS-3D-SUPERIOR-3D-PERSPECTIVA-INCLINADA-SUPERIOR.jpg)

---

## Cara inferior

![Cara inferior](https://github.com/AtlasFPGA/iCEZUM_ALHAMBRA-ATLAS/blob/main/FOTOS/iCEZUM_ALHAMBRA-ATLAS-3D-SUPERIOR-3D-INFERIOR.jpg)

---

## Perspectiva inclinada inferior

![Perspectiva inclinada inferior](https://github.com/AtlasFPGA/iCEZUM_ALHAMBRA-ATLAS/blob/main/FOTOS/iCEZUM_ALHAMBRA-ATLAS-3D-SUPERIOR-3D-PERSPECTIVA-INCLINADA-INFERIOR.jpg)

---
