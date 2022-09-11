<h1 align="center">Usa Git y Github desde tu móvil</h1>

<p>Usar Git y Github desde mi teléfono se ha vuelto algo muy práctico y fácil de usar. En las siguientes sesiones observarás como tenerlo en tu dispositivo.</p>

<div align="center" style="display: inline_block"><br>
 <img height="55" width="55" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-plain.svg" />        
</div> 


## Vista        

<div align="center">
<img src="https://i.postimg.cc/q73K5Nvz/IMG-20220910-193721.jpg">
</div>

## Instalación 

> Descarga la aplicación `Termux` en su última versión **[aquí.](https://f-droid.org/packages/com.termux/)**
> Una vez de haber `instalado` correctamente la aplicación ingresar los siguientes comandos.

  
 - `termux-setup-storage`
 - `pkg update && pkg upgrade`
 - `pkg i -y git bc`

>  Ahora debes de `clonar` este repositorio en tu terminal, esto hará que tu terminal se vea mucho mejor.
   Fuente del repo **[myTermux](https://github.com/mayTermux/myTermux)**

```bash
   git clone --depth=1 https://github.com/mayTermux/myTermux.git
```
> Por último ingresa los siguientes comandos.
- `cd myTermux`
- `export COLUMNS LINES`
> **Note**
> Antes de ingresar el siguiente comando debes de alejar la pantalla de tu terminal lo más que puedas. ➡️⬅️ O de lo contrario te mostrará un error.
- `./install.sh`
