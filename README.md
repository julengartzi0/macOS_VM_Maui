# MAUI macOS makina birtual batean instalatzeko:

## Hasiera
Maquina birtualaren instalazioa eta hasierako konfigurazioa egiteko hurrengo tutoriala jarraituko dugu:
https://github.com/luiscoco/macOS_Sonoma_VMWare/blob/main/README.md?plain=1

## Visual Studio Code
macOS-en Visual Studio kendu egin dutenez, Visual Studio Code erabili beharko dugu eta bertan maui-ren extensioak gehitu.

Visual Studio Code descargatzeko: 
https://code.visualstudio.com/docs/setup/mac

Behin deskargatuta aplikazioa "Aplicaciones" carpetara mugitu beharko dugu.

# Extensioak gehitu
Visual Studio Coderen barruan MAUI-ren extensioak gehitu beharko ditugu.

![maui](https://github.com/user-attachments/assets/1a2ffbdb-3c9b-4e41-94a5-01d8305f314d)

# dotnet-sdk instalatu
MAUI erabili ahal izateko dotnet-sdk instalatu beharko dugu, horretarako: 
https://dotnet.microsoft.com/es-es/download/dotnet/8.0
Azken bertsioa deskargatuko dugu, kasu honetan, SDK 8.0.404 eta x64 bertsioa, gure prozesagailua intel bat da eta.
![sdk](https://github.com/user-attachments/assets/e4f57b12-1188-460b-8e5a-5c28e07418e4)
Deskargatu ondoren instaladorea iriko dugu, eta aurrera egingo dugu.
![insta](https://github.com/user-attachments/assets/76f7eb80-e3f7-430b-83e3-80a6cada314c)

Honekin gure proiektuak mahaigain moduan exekutatu ahal izango ditugu.
Gogoratu macos-en fitxategiak deskonprimitzeko, hortarako The Unarchiver erabili dezakegu.

# The Unarchiver instalatzeko.
Apple storea ezin izango dugunez erabili danak Apple ID berdina partekatzen dugulako, hurrengo pausuak jarraitu ditzakegu: 

Puedes instalar The Unarchiver en macOS usando Homebrew, que es un gestor de paquetes popular para macOS. Sigue estos pasos:

1. Instalar Homebrew (si no lo tienes instalado)
Abre la Terminal y ejecuta el siguiente comando:

bash
Copiar código
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
Sigue las instrucciones en pantalla para completar la instalación.

2. Instalar The Unarchiver
Una vez que Homebrew esté instalado, ejecuta este comando para instalar The Unarchiver:

bash
Copiar código
brew install --cask the-unarchiver
3. Verificar la Instalación
Para asegurarte de que The Unarchiver está instalado correctamente, puedes buscarlo en tu carpeta de aplicaciones o ejecutar:

bash
Copiar código
open /Applications/The\ Unarchiver.app
4. Configurar The Unarchiver
Abre The Unarchiver desde la carpeta de aplicaciones, configura los formatos que quieres que maneje (como .rar, .7z, etc.), y estará listo para usarse.



