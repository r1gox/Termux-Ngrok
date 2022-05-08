# Termux-Ngrok
    Created by: Rigo Jimenez
    Instagram: @d4rkgh0st3
    Termux-Ngrok es una herramienta que automatiza la instación de ngrok.

# ¿What is ngrok?
> Ngrok es una herramienta útil que crea una URL de túnel segura y de acceso público a una aplicación que se ejecuta desde la red local (localhost).

# ¿What is it for?
* Demostración de sitios web sin implementar .
* Ejecución de servicios en la nube personal desde el hogar.
* Probar aplicaciones móbiles conectadas al backend ejecutado localmente.
* Direcciones estables para dispositivos conectados que se implementan en el campo.

# ¿How does it work?
> Cuando se ejecuta un programa en la maquina se proporcina un puerto de un servidor web. Luego se conecta al servicio en la nube de ngrok que acepta el tráfico en una dirección pública y transmite ese trafico al proceso ngrok que se ejecuta en la maquina y de ahi a la dirección local que se especificó.

# Download Termux F-Droid
> NOTA: No se recomienda usar la aplicación Termux que está disponible en "Google Play Store", ya que los desarrolladores ya no mantienen la aplicación, así que descargué la aplicación sin errores con el siguiente enlace:
[Link Downlaod Termux](https://f-droid.org/en/packages/com.termux)

# Preview in Termux
![Termux ngrok](https://github.com/Rigo-Jimenez/Termux-Ngrok/blob/main/.Screen/Screenshot_Termux-Ngrok.png)

# Installation
    pkg update && pkg upgrade -y
    pkg install -y git
    git clone https://github.com/Rigo-Jimenez/Termux-Ngrok
    cd Termux-Ngrok
    ls
    bash install.sh
    bash Termux-ngrok.sh

# Authtoken ngrok
> Antes de ejecutar ngrok debes de agregar tu authtoken, para eso debes de registrarte en la pagina oficial de ngrok copiar tu token y pegarlo en termux. Enlace de Ngrok:
[Ngrok](https://ngrok.com)

# Video de Instalación
https://youtu.be/YgYep2E-WNQ

# Usage
    ngrok http [port]
    ngrok http 8080

# Preview ngrok Screenshot
![Screenshot_Ngrok](https://github.com/Rigo-Jimenez/Termux-Ngrok/blob/main/.Screen/Screenshot_ngrok.png)

# Social Media Links
* [Telegram](https://t.me/D4rkGh0st3)
* [YouTube](https://youtube.com/channel/UCjiVJAYDeaE2eIlRUTgcfYg)
* [TikTok](https://tiktok.com/@d4rk_security)
