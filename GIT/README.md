## Manual de Configuración Básica de Git

### Índice

1. [Introducción](#introducción)
2. [Instalación de Git](#instalación-de-git)
3. [Configuración Inicial](#configuración-inicial)
4. [Comandos Básicos](#comandos-básicos)
5. [Crear y Clonar Repositorios](#crear-y-clonar-repositorios)
6. [Gestionar Ramas](#gestionar-ramas)
7. [Colaboración y Trabajo Remoto](#colaboración-y-trabajo-remoto)
8. [Conclusión](#conclusión)

### Introducción

Git es un sistema de control de versiones distribuido, diseñado para manejar todo, desde proyectos pequeños hasta proyectos muy grandes con rapidez y eficiencia. Este manual te guiará a través de los pasos básicos para configurar y empezar a usar Git.

### Instalación de Git

#### Windows

1. Descarga el instalador desde [git-scm.com](https://git-scm.com/download/win).
2. Ejecuta el instalador y sigue las instrucciones en pantalla.

#### MacOS

1. Abre la terminal.
2. Instala Git usando Homebrew:
   ```sh
   brew install git
   ```
3. **Método alternativo: Usando Xcode Command Line Tools**
   - Abre la terminal y ejecuta el siguiente comando:
     ```sh
     xcode-select --install
     ```
   - Aparecerá una ventana emergente solicitando la instalación de las herramientas de línea de comandos. Acepta la instalación y sigue las instrucciones en pantalla.

#### Linux

1. Abre la terminal.
2. Instala Git usando el administrador de paquetes de tu distribución:
   ```sh
   sudo apt-get install git      # Ubuntu/Debian
   sudo yum install git          # CentOS/RHEL
   sudo dnf install git          # Fedora
   ```

### Configuración Inicial

Configura tu nombre de usuario y correo electrónico para que Git pueda asociar tus commits con tu identidad.

```sh
git config --global user.name "Tu Nombre"
git config --global user.email "tu.email@ejemplo.com"
```

Para verificar tu configuración:

```sh
git config --list
```

### Comandos Básicos

#### Inicializar un repositorio

Para inicializar un nuevo repositorio Git en tu directorio actual:

```sh
git init
```

#### Añadir archivos

Añade archivos al área de preparación (staging area):

```sh
git add nombre_del_archivo
```

Añade todos los archivos del directorio actual:

```sh
git add .
```

#### Realizar un commit

Guarda los cambios en el repositorio:

```sh
git commit -m "Mensaje del commit"
```

### Crear y Clonar Repositorios

#### Crear un nuevo repositorio en GitHub

1. Crea un nuevo repositorio en [GitHub](https://github.com/).
2. Enlaza tu repositorio local al repositorio remoto:

   ```sh
   git remote add origin https://github.com/tu-usuario/tu-repositorio.git
   ```

#### Clonar un repositorio existente

Para clonar un repositorio desde GitHub:

```sh
git clone https://github.com/usuario/repositorio.git
```

### Gestionar Ramas

#### Crear una nueva rama

Para crear y cambiar a una nueva rama:

```sh
git checkout -b nombre_de_la_rama
```

#### Cambiar entre ramas

Para cambiar a una rama existente:

```sh
git checkout nombre_de_la_rama
```

#### Fusionar ramas

Para fusionar una rama con la rama actual:

```sh
git merge nombre_de_la_rama
```

### Colaboración y Trabajo Remoto

#### Verificar remotos

Para listar todos los repositorios remotos:

```sh
git remote -v
```

#### Enviar cambios al repositorio remoto

Para enviar tus commits al repositorio remoto:

```sh
git push origin nombre_de_la_rama
```

#### Obtener cambios del repositorio remoto

Para obtener los últimos cambios del repositorio remoto:

```sh
git pull origin nombre_de_la_rama
```

### Conclusión

Este manual cubre los aspectos básicos para empezar a trabajar con Git. Existen muchos más comandos y opciones que puedes explorar. Para más información, consulta la [documentación oficial de Git](https://git-scm.com/doc).


# Taller 1.
Actividad en clase.

[Tallerbásico git-github](https://github.com/jaiderospina/HABILIDADES_CIBERNETICAS_20241/blob/main/GIT/TallerGIT.pdf)

# VIDEO - GUÍA
## Agregar Colaboradores/Usuarios/Desarrolladores A Un Repositorio.

Para un paso a paso sobre como agergar colaboradores y aceptar la invitación de clic sobre el texto.

[![(Agregar Colaboradores/Usuarios/Desarrolladores A Un Repositorio)](https://img.youtube.com/vi/G_zKrG2mkrg?si=sYOJprXKoBLAIB0S/0.jpg)](https://www.youtube.com/watch?v=G_zKrG2mkrg?si=sYOJprXKoBLAIB0S)


