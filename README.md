# Curso de Git & Github
![git](img/git_github.jpg)
## Descripción del curso 🚀 
📝 Este documento contiene mis notas personales sobre el curso de git y github para las configuraciones iniciales de git como los comandos que se utilizan para trabajar con proyectos de software, del mismo modo revisaremos las mejores practicas que se utilizan en git.

 ## 📋 Índice
> 1. [**Introducción a Git** 🚀](#introducción-a-git)



## Introducción a Git


### ¿Qué es Git? 🤔
Git es un sistema distribuido de control de versiones, gratuito y de código abierto bajo licencia GPLv2. Fue diseñado originalmente por Linus Torvalds12, el creador de Linux.
Git, al ser un sistema distribuido, aloja una copia completa del repositorio en cada máquina local que está trabajando en el código.
![git](img/git.png)

### Instalación Git

**➊ Linux(Ubuntu\Debian) 🐧**

* Lo instalamos desde el repositorio de software de nuestra distrubución ejecutamos los siguientes comandos en nuestra terminal:

    ```
    sudo apt update
    sudo apt install git
    ```
* Verificamos la version de git que se instalo:
    ```
    git --version
    ```
Con eso ya tenemos git funcionando en nuestro Debian 💯

**➋ MacOS 🍏**

 En macOS la forma de instalar git es con **Homebrew** a continuación te dejo los pasos para la instalación correctamente:
* Instalar **Homebrew** si aún no lo tienes instalado 🔧
* Instalar git con brew 🔥
* Verificamos la versión de git que se instalo 💯

    ```
    xcode-select --install/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

    brew install git

    git --version
    ```

**➌ Windows 💻**

En Windows es más sencillo descargar el instalador oficial y seguir los pasos del
asistente:

* Descargarga el instalador de 👉[https://git-scm.com/download/win](https://git-scm.com/download/win)

* Ejecuta el instalador 🔥

* Finaliza la instalación 💯

### Configuración de Git 🛠️

Para hacer que tus commits se asocien a tu nombre y aparezca correctamente tu
avatar en la plataforma de GitHub, necesitamos realizar la siguiente configuración.


1. Configura tu nombre 😀
    ```
    git config --global user.name "<tu nombre>"
    ```
2. Configura tu correo electronico ✉️
    ```
    git config --global user.email "<tu email>"
    ```
📌**NOTA**: El correo electronico tiene que ser el mismo con el que estas registrado en Github

**Otras configuraciones adicionales ⚙️** 

* Para comprobar nuestra configuración de git ejecutamos el siguiente comando
    ```
    git config --list
    ```
* Si necesitamos ayuda y mas opciones de configuración 
    ```
    git config --help
    ```
