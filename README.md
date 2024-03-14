<p align="center"> 
<img src="https://i.imgur.com/q7j9OHz.jpeg" alt="SharksBot-MD" width="500"/>
</p>
<p align="center">
<a href="https://github.com/brayan2019/SharksBot-MD"><img title="SharksBot-MD" src="https://img.shields.io/badge/🦈 Primera versión creada de SharksBot_MD 🦈 -red?colorA=%233CCED8&colorB=%233CCED8&style=for-the-badge"></a>
</p>

<div align="center">
  
[![Gmail](https://img.shields.io/badge/GMAIL-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:xlbrayan30@gmail.com)
[![WhatsApp](https://img.shields.io/badge/CREADOR-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://wa.me/+18298838883)
[![WhatsApp](https://img.shields.io/badge/CONSULTA-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://wa.me/+18295284801)
[![YouTube](https://img.shields.io/badge/YOUTUBE-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@dxxrkgxntel)
[![Instagram](https://img.shields.io/badge/INSTAGRAM-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://instagram.com/soybryant_hdx)
[![PayPal](https://img.shields.io/badge/PayPal-00457C?style=for-the-badge&logo=paypal&logoColor=white)](https://paypal.me/brayanbeltrex)
</div>

### Cuentas Oficiales:
> Al utilizar nuestro bot estás aceptando todos los términos y condiciones que tenemos disponibles. La pagina se estará actualizando cada 2 día para mantenerlos informado en cuanto a las actualizaciones del bot. ¡No te pierdas nada y únete a nuestra comunidad!

<a href="https://www.atom.bio/sharksbot/">
<img src="https://img.shields.io/badge/SharksBot_Accounts-000000%7D?style=for-the-badge&logo=biolink&logoColor=white">
</a>
  
#### DISPONIBLE EN:
> - [x] TERMUX, REPLIT Y WINDOWS 🦈


[`♻️ TERMUX APP DOWNLOAD`](https://f-droid.org/es/packages/com.termux/)
### INSTALACIÓN AUTOMÁTICA 🦈
<a href="https://youtu.be/tzM0f_N8BII">
<img src="https://img.shields.io/badge/Tutorial-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="TUTORIAL"> </a>

```bash
termux-setup-storage
```
```bash
apt update -y && yes | apt upgrade && pkg install -y bash wget && wget -O - https://raw.githubusercontent.com/brayan2019/SharksBot-MD/master/sharksbot.sh | bash
```
#### EN CASO QUE QUIERA USAR ESTE MÉTODO DEBE DE EDITAR (Previo a una Bifurcación)
- [`Repositorio`](https://github.com/brayan2019/SharksBot-MD/blob/14da583cddcf76285988dadb76cfc77f9373d8a8/sharksbot.sh#L155)
- [`Nombre del Bot`](https://github.com/brayan2019/SharksBot-MD/blob/14da583cddcf76285988dadb76cfc77f9373d8a8/sharksbot.sh#L159)
- Actualizar: `https://raw.githubusercontent.com/brayan2019/SharksBot-MD/master/sharksbot.sh`
### INSTALACIÓN MANUAL - TERMUX 🦈
```bash
termux-setup-storage
apt update
apt upgrade
pkg install -y git nodejs ffmpeg imagemagick yarn
git clone https://github.com/brayan2019/SharksBot-MD 
cd SharksBot-MD
yarn install
npm install
npm start
```

### TERMUX 24/7 🦈
> Comandos para realizar una ejecución 24/7
- INICIAR
> Use estos comandos dentro de la carpeta SharksBot-MD
```bash
termux-wake-lock && npm i -g pm2 && pm2 start index.js && pm2 save && pm2 logs 
```
- DETENER PM2
> Detener todos los procesos del bot
```bash
pm2 stop all && pm2 unstartup
```
- REANUDAR 
> Reanudar los procesos, usar dentro de la carpeta SharksBot-MD 
```bash
pm2 start index.js 
```
- VISUALIZAR EL PROCESO
> Usar dentro de la carpeta SharksBot-MD para ver en tiempo real
```bash
pm2 logs 
```
- ELIMINAR PROCESOS PM2
> Eliminar todos los procesos del bot. Para volver a usar PM2 debe volver a usar los comandos de INICIAR
```bash
pm2 delete all
```
> **Note** Demanda consumo de RAM y CPU, el resultado mejora mientras las especificaciones del dispositivo sean moderadas
----
### INSTALACIÓN EN REPLIT 🦈
<a target="_blank" href="https://replit.com/github/brayan2019/SharksBot-MD"><img alt="Run on Replit" src="https://binbashbanana.github.io/deploy-buttons/buttons/remade/replit.svg"></a>
> **Note** Agregue estos comandos en Shell para empezar la instalación automática por Replit:
```bash
npm install -g ffmpeg imagemagick git yarn && npm i && node --no-warnings index.js
```
----

- [x] **Configuración** <details><summary>**Ajustes del Servidor - SharksBot-MD**</summary><img src="https://i.imgur.com/Ly0MffH.jpeg"></details>
----
## 🦈 INSTALACIÓN PARA WINDOWS/VPS/RDP 🦈
<a href="https://youtu.be/SaxYKnnZo3E">
<img src="https://img.shields.io/badge/Tutorial-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="Tutorial"> </a>

* Descargar e instala Git [`Aquí`](https://git-scm.com/downloads)
* Descargar e instala NodeJS [`Aquí`](https://nodejs.org/en/download)
* Descargar e instala FFmpeg [`Aquí`](https://ffmpeg.org/download.html) (**No olvide agregar FFmpeg a la variable de entorno PATH**)
* Descargar e instala ImageMagick [`Aquí`](https://imagemagick.org/script/download.php)
```bash
git clone https://github.com/brayan2019/SharksBot-MD
cd SharksBot-MD
npm install -g yarn
yarn
npm install 
npm start
```
### Instalación de FFmpeg para Windows 
* Descarga la siguiente versión de FFmpeg [`Aquí`](https://www.gyan.dev/ffmpeg/builds/ffmpeg-git-full.7z).
* Extraer FFmpeg con [`7-Zip`](https://www.7-zip.org/download.html)
* Cambie el nombre de la carpeta extraída a `FFmpeg`.
* Mover archivos a `C:\` path.
* Agregar la ruta ejemplo: `C:\ffmpeg\bin` al entorno de variable
* Ejecute el símbolo del sistema como administrador.
* Ejecute el siguiente comando:
```cmd
setx /m PATH "C:\ffmpeg\bin;%PATH%"
```
Si tiene éxito, le dará un mensaje como: `SUCCESS: specified value was saved`.
* Ahora que tiene FFmpeg instalado, verifique que funcionó ejecutando este comando para ver la versión:
```cmd
> ffmpeg -version
```
### Error en usar yarn en PowerShell
* Si usa la consola PowerShell y recibe este mensaje `No se puede cargar el archivo yarn.ps1 o yarn porque la ejecución de scripts está deshabilitada en este sistema.` al intentar usar `yarn` dentro de la carpeta del Bot puede usar estos comandos para cambiar la Política de ejecución de PowerShell en su sistema:
> Debe de ejecutar la consola como Administrador
```cmd
Get-ExecutionPolicy
Set-ExecutionPolicy RemoteSigned
```
> Aparecerá un mensaje de advertencia preguntando si deseas cambiar la Política de ejecución. Confirma con "Y" y presiona Enter. Luego ya puede volver a ejecutar el comando `yarn`

### 💠 [`IDIOMAS DISPONIBLES PARA SharkBotLITE`](https://github.com/brayan2019/SharksBot-MD/blob/f406e0f1bba1ca7cd6ee4ef3208e156135a24dce/config.js#L31) 
> Multi Lenguaje Dinámico GB: Disponibilidad de usar varios idiomas simultáneamente.
#### ✨ Español  [`Editar Idioma`](https://github.com/brayan2019/SharksBot-MD/blob/master/lib/idiomas/espanol.js)
#### ✨ Inglés (English) [`Edit Language`](https://github.com/brayan2019/SharksBot-MD/blob/master/lib/idiomas/ingles.js)
#### ✨ Portugués (Português) [`Idioma de Edição`](https://github.com/brayan2019/SharksBot-MD/blob/master/lib/idiomas/portugues.js)
#### ✨ Indonesio (Bahasa Indonesia) [`Mengedit Bahasa`](https://github.com/brayan2019/SharksBot-MD/blob/master/lib/idiomas/indonesio.js) 
#### ✨ Árabe (عرب) [`عدل اللغة`](https://github.com/brayan2019/SharksBot-MD/blob/master/lib/idiomas/arabe.js)
----
> **Note** The translations are not perfect, it is only a reference, if you want to collaborate with the language or with another that is not on the list, contact me [`Contact me`](https://wa.me/message/C45GXBEFTPONE1)

### 😸 CREADORA 
[![brayan2019](https://github.com/brayan2019.png?size=100)](https://github.com/brayan2019) 

### 😸 DESARROLLADORES
<a href="https://github.com/brayan2019/SharksBot-MD/graphs/contributors">
<img src="https://contrib.rocks/image?repo=brayan2019/SharksBot-MD" /> 
</a>
