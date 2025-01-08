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

Homebrew instalatu (ez baduzu instalatuta) Ireki Terminala eta exekutatu hurrengo komandoa:

/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

Jarraitu pantailan agertzen diren argibideak instalazioa amaitzeko.

The Unarchiver instalatu Behin Homebrew instalatuta, exekutatu komando hau The Unarchiver instalatzeko:

brew install --cask the-unarchiver

Instalazioa egiaztatu Ziurtatzeko The Unarchiver behar bezala instalatu dela, bilatu aplikazioen karpetan edo exekutatu hau:

open /Applications/The\ Unarchiver.app

The Unarchiver konfiguratu Ireki The Unarchiver aplikazioen karpetatik, hautatu kudeatu nahi dituzun formatuak (adibidez, .rar, .7z, etab.), eta erabilgarri egongo da.

Pausu hauek jarraituta fitxategiak deskonprimitu ahal izango ditugu.

# XCODE deskargatzeko

Deskargartzeko link-a: https://drive.google.com/file/d/1TK02h3_HE6vZFyfyCcAR6sSl2sIBY_IE/view?usp=sharing

Deskargatu eta deskonpromitu ondoren XCODE instalatuko dugu.



