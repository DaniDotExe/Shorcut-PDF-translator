# Shorcut PDF translator

_Herramienta para crear o editar un shorcut que permite traducir palabras y frases rapidamente de un pdf dentro del navegador_

## Instalación
## 1) Descargar las siguiente extensiones de google chrome
[Instant Multilingual PDF/HTML/TXT Translator](https://chrome.google.com/webstore/detail/instant-multilingual-pdfh/fcbnhmalionocfajdkpnlhmekghnmbii)
[AutoControl: Keyboard shortcut, Mouse gesture](https://chrome.google.com/webstore/detail/autocontrol-keyboard-shor/lkaihdpfpifdlgoapbfocpmekbokmcfd)

Opcional (Tu pdf de color negro usando Ctrl + shift + 9)
[DarkPDF](https://chrome.google.com/webstore/detail/darkpdf/cfemcmeknmapecneeeaajnbhhgfgkfhp)

## 2) Configurar extensiones de google chrome
Extensiones
Administrar extensiones
Activar: permitir el las URL del archivo (Para cada una de las extensiones anteriores)

## 3) Configurar el archivo teclado.py
Este archivo contiene el shorcut de las acciones que se van a realizar, es decir, estan todos los pasos que el programa va a ejecutar cuanto se use el shorcut, en nuestro caso, presiona click derecho y baja 8 veces el cursor (hasta llegar a la opcion del traductor de PDF) y luego presiona enter.

## 4) Convertir teclado.py a teclado.exe
Ejecutamos en nuestro entorno de python los comandos
```
pip install auto-py-to-exe
auto-py-to-exe
```
En la interfaz del sofware configuramos en one file y convertimos a .exe, ese archivo resultante lo guardamos en una carpeta cualquiera y copiamos su path

## 4) Configuración de AutoControl: Keyboard shortcut, Mouse gesture
En la pestaña de trigger agregamos nuestro shorcut 
Q+E 
Mientras que en la pestaña de action
Nos dirigmos a 
Advanced options
Other
Open file/program
finalmente pegamos el path de nuestro archivo .exe 

[Mouse tooltip translator ](https://chrome.google.com/webstore/detail/mouse-tooltip-translator/hmigninkgibhdckiaphhmbgcghochdjc)
