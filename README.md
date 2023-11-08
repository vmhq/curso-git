# Guía Rápida de Comandos de Git 🚀

Git es un sistema de control de versiones distribuido que permite a los desarrolladores trabajar juntos y mantener un historial completo de su trabajo.

## Configuración Inicial

- Configurar nombre de usuario y correo electrónico:
  ```
  git config --global user.name "Tu Nombre"
  git config --global user.email "tuemail@example.com"
  ```

- Verificar configuración:
  ```
  git config --list
  ```

## Comandos Básicos

- **git init**: Inicializa un nuevo repositorio de Git.
  ```
  git init
  ```

- **git add**: Añade archivos al área de preparación (staging area).
  ```
  git add <nombre-del-archivo>
  git add .
  ```

- **git commit**: Guarda los cambios en el repositorio.
  ```
  git commit -m "Mensaje descriptivo del commit"
  ```

## Trabajando con Ramas

- **git branch**: Crea una nueva rama o lista todas las ramas.
  ```
  git branch <nombre-de-la-rama>
  git branch
  ```

- **git checkout**: Cambia de rama o restaura archivos del área de trabajo.
  ```
  git checkout <nombre-de-la-rama>
  git checkout -b <nombre-de-la-rama-nueva>
  ```

- **git merge**: Fusiona una rama en tu rama activa actual.
  ```
  git merge <nombre-de-la-rama>
  ```

## Sincronización y Repositorios Remotos

- **git pull**: Actualiza tu rama actual con los últimos cambios del repositorio remoto.
  ```
  git pull
  ```

- **git push**: Sube tus cambios al repositorio remoto.
  ```
  git push origin <nombre-de-tu-rama>
  ```

- **git clone**: Clona un repositorio en tu máquina local.
  ```
  git clone <url-del-repositorio>
  ```

## Integración con VSCode

VSCode tiene una integración directa con Git. Puedes utilizar la mayoría de estos comandos desde la interfaz de usuario, a través del panel de control de versiones.

## Extras

- **git status**: Muestra el estado de los archivos en tu rama actual.
  ```
  git status
  ```

- **git log**: Muestra el historial de commits.
  ```
  git log
  ```

- **git diff**: Muestra las diferencias de archivo que no han sido preparadas.
  ```
  git diff
  ```
