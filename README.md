
-----
### 🌟 (OPCIÓN 1) INSTALACIÓN AUTOMÁTICA 🫰
[![blog](https://img.shields.io/badge/Instalacion-Automatica-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtube.com/shorts/PESW8LXXlOI?feature=share)
> **Note** Comandos para instalar de forma automática en Termux  
```bash
termux-setup-storage
```
```bash
apt update -y && yes | apt upgrade && pkg install -y bash wget mpv && wget -O - https://raw.githubusercontent.com/colombiahack/UnixBot-MD/master/gata.sh | bash
```
```js
// PERSONALIZAR INSTALACIÓN AUTOMÁTICA (En caso de una Bifurcación)
// Parámetros editables

// REFERENCIA
"wget -O - https://raw.githubusercontent.com/colombiahack/UnixBot-MD/master/gata.sh | bash"

// PARÁMETROS QUE PUEDE SER MODIFICADOS --> "[...]"
"wget -O - https://raw.githubusercontent.com/[usuario]/[repositorio]/[rama]/gata.sh | bash"
```
#### MODIFICAR ARCHIVO [`gata.sh`](https://github.com/GataNina-Li/GataBot-MD/blob/master/gata.sh)
```js
//LÍNEAS A MODIFICAR
205 --> "git clone https://github.com/[user]/[repositorio].git"
//Ejemplo: git clone https://github.com/GataNina-Li/GataBot-MD.git

209 --> "cd [repositorio]"
//Ejemplo: cd UnixxBot-MD

//Una vez hecho estos cambios ejecute los nuevos comandos en Termux
```
-----
### 🪄 (OPCIÓN 2) INSTALACIÓN MANUAL POR TERMUX - GITHUB 
> **Note** Comandos para instalar de forma manual
```bash
termux-setup-storage
```
```bash
apt update && apt upgrade && pkg install -y git nodejs ffmpeg imagemagick yarn
```
```bash
git clone https://github.com/colombiahack/UnixxBot-MD  && cd UnixxBot-MD
```
```bash
yarn install && npm install
```
```bash
npm start
```
> **Warning** Si aparece (Y/I/N/O/D/Z) [default=N] ? use la letra "y" + "ENTER" para continuar con la instalación 
------------------
### 📁 (OPCIÓN 3) INSTALACIÓN POR TERMUX - ARCHIVOS
> **Note** Descargué y Descomprime
### [`GataBot-MD ~ Archivos`](https://github.com/GataNina-Li/GataBot-MD/archive/refs/heads/master.zip)
[![blog](https://img.shields.io/badge/Termux-GataBotMD-FF0000?style=for-the-badge&logo=youtube&logoColor=white)
](https://youtu.be/UcWlyQ8u5HE)
```bash
termux-setup-storage
```
```bash
apt update && apt upgrade && pkg install -y git nodejs ffmpeg imagemagick yarn
```
```bash
cd storage/downloads/GataBot-MD-master/GataBot-MD-master 
```
```bash
yarn install
```
```bash
npm install
```
```bash
npm start
```
* #### APLICACIÓN RECOMENDADA PARA [`DESCOMPRIMIR`](https://play.google.com/store/apps/details?id=com.rarlab.rar)
* #### APLICACIÓN RECOMENDADA PARA EDITAR [`NÚMERO DE OWNER`](https://play.google.com/store/apps/details?id=com.rhmsoft.code)
> **Note** Guardar los archivos en la ubicación: storage/downloads/GataBot-MD-master/GataBot-MD-master   
----
### 🚀 USAR GATABOT 24/7 EN TERMUX 
> Ejecutar estos comandos dentro de la carpeta GataBot-MD
```bash
termux-wake-lock && npm i -g pm2 && pm2 start index.js && pm2 save && pm2 logs 
``` 
#### ⬇️ Opciones Disponibles
> **Warning** Esto eliminará todo el historial que hayas establecido con PM2:
```bash 
pm2 delete index
``` 
> Si tienes cerrado Termux y quiere ver de nuevo la ejecución use:
```bash 
pm2 logs 
``` 
> Si desea detener la ejecución de Termux use:
```bash 
pm2 stop index
``` 
> Si desea iniciar de nuevo la ejecución de Termux use:
```bash 
pm2 start index
``` 
---- 
### `🟢 ACTIVAR EN CASO DE DETENERSE EN TERMUX`
> **Note** Si despues que ya instalastes tu bot y termux te salta en blanco, se fue tu internet o reiniciaste tu celular, solo realizaras estos pasos :
```bash
cd
```
```bash
cd UnixxBot-MD
```
```bash
npm start
```
----
### `🔵 OBTENER OTRO CODIGO QR EN TERMUX`
> **Warning** deten el bot, haz click en el símbolo (ctrl) [default=z] usar la letra "z" + "ENTER" hasta que salga algo verdes similar a : GataBot-MD $
> escribe los siguientes comando uno x uno :
```bash 
cd UnixxBot-MD
```
```bash
rm -rf UnixxBotSession
```
```bash
npm start
```
----

----
### 😼 ACTUALIZAR GATABOT
> **Note** Comandos para actualizar GataBot-MD de forma automática
```bash
grep -q 'bash\|wget' <(dpkg -l) || apt install -y bash wget &&wget -O - https://raw.githubusercontent.com/colombiahack/UnixxBot-MD/master/update.sh | bash
```
#### Para que no pierda su progreso en GataBot, estos comandos realizarán un respaldo de su `database.json` y se agregará a la versión más reciente.
> **Warning** Estos comandos solo funcionan para TERMUX, REPLIT, LINUX                           
----





                        
----
### 🟣 ACTIVAR EN HEROKU 
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/GataNina-Li/GataBotMD-Heroku) 
### 👇 Añada lo siguente al Buildpack: 
```bash
heroku/nodejs
```
```bash
https://github.com/jonathanong/heroku-buildpack-ffmpeg-latest.git
```
```bash
https://github.com/clhuang/heroku-buildpack-webp-binaries.git
```
- [x] Resultado <details><summary>Buildpack</summary><img src="https://i.imgur.com/t3Xzgnh.jpeg"></details>
-----

### ⚡ REPLIT - GATABOT
[![blog](https://img.shields.io/badge/Replit-GataBotMD-FF0000?style=for-the-badge&logo=youtube&logoColor=white)
](https://youtu.be/pQYkq4xv37o)

<a target="_blank" href="https://replit.com/github/GataNina-Li/GataBot-MD"><img alt="Run on Replit" src="https://binbashbanana.github.io/deploy-buttons/buttons/remade/replit.svg"></a> <a href="https://replit.com/github/GataNina-Li/GataBot-MD"> <img src="https://media0.giphy.com/media/lMwu8EJAnv9kmn51KQ/giphy.gif" height="29px"></a>

- [x] Configuración <details><summary>Importar Repositorio - GataBot-MD</summary><img src="https://i.imgur.com/GQyRnMf.jpg"></details>
-----
