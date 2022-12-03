# clean-switch
A simple guide to unhack a switch

0. **Inicio**
- Apaga la switch y extrae la micro SD.
- Mete la SD en el ordenador. 

1. **(Parte PC)**
- Descarga el archivo Clean-switch v1.zip.
- Descomprimelo.

  1.1. hekate
  - Abre la carpeta hekate_ctcaer.
  - Mueve la carpeta `bootloader` a la raíz de la SD.

  1.2. tegra
  - Abre la carpeta TegraRcmGUI.
  - Abre el archivo `TegraRcmGUI.exe`.
  - Pulsa en el boton de Select payload y busca el archivo `hekate_ctcaer_5.9.0.bin` en la carpeta de hekate.
  - Conecta la switch al PC por usb-c.

![tegra](https://i.ibb.co/mv9dk59/Captura-de-pantalla-20221203-131016.png)

2. **(Parte Switch)**
- Una vez inyectado el payload, entra en el apartado Tools y haz click en Arch bit · RCM · Touch · Pkg1/2.
- En el apartado Others desactiva el AutoRCM

![AutoRCM](https://i.ibb.co/TRSbV1v/nyx20190412-193828.png)

- Finalmente reinicia la switch 

**Fin.**
