Ngrok para Termux 🚀  

Este repositorio permite instalar y usar Ngrok en Termux de forma rápida y directa. Para instalarlo, primero clona el repositorio con  

git clone https://github.com/tu-usuario/termux-ngrok.git  

y entra en la carpeta con  

cd termux-ngrok  

Una vez dentro, ejecuta  

sh install.sh  

para instalar Ngrok en tu dispositivo; este script se encarga de instalar todo automáticamente. Después de la instalación, puedes usar Ngrok ejecutando  

ngrok http 8080  

para exponer tu servidor local a Internet, lo que te dará una URL pública tipo https://abcd1234.ngrok.io accesible desde cualquier lugar.  

Este repositorio está diseñado para ser ultra simple, sin pasos adicionales ni configuraciones complicadas, ideal para desarrolladores o testers que necesitan túneles rápidos y seguros en Termux. Funciona en Termux sobre Android 9+ y ha sido probado en SM-A32 y otros dispositivos ARM64, funcionando tanto en $PREFIX como en la carpeta home de Termux. Todo está listo para usar inmediatamente después de ejecutar sh install.sh.  

Si este repositorio te sirve, dale ⭐ en GitHub para mantenerlo actualizado y ayudar a otros usuarios. Disfruta exponiendo tus servidores locales con Ngrok de manera inmediata y sin complicaciones.
