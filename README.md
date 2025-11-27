# Instructivo de Instalación  
## Mod de Doblaje LATAM – Sonic Riders (GameCube)

Este documento explica cómo instalar manualmente el mod de doblaje al español latinoamericano para **Sonic Riders (GameCube)**.

---

## 📌 Requisitos

- Una copia **legal** de Sonic Riders (versión GameCube).
- Un archivo **GCM/ISO** del juego.
- El mod descargado desde:
  - GitHub: contiene carpeta `mod/`  
  - GameBanana: contiene **un solo archivo comprimido con los archivos del mod** (ignorar instrucciones sobre `mod/` en este caso).
- La herramienta **GCR (GameCube Rebuilder)** o similar.
- **Opcional:** Dolphin Emulator para extraer los archivos del juego.

---

## 🗂️ 1. Extraer archivos del juego original

Puedes hacerlo de dos maneras:

### ✔️ Método A – Usando Dolphin
1. Abre **Dolphin**.
2. Haz clic derecho en tu copia de **Sonic Riders**.
3. Selecciona **"Extraer archivo del disco"** o **"Properties" → "Filesystem" → "Extract Files"**.
4. Guarda los archivos extraídos en una carpeta.

### ✔️ Método B – Usando GCR (GameCube Rebuilder)
1. Abre **GCR**.
2. Ve a **File → Open** y selecciona el ISO/GCM de Sonic Riders.
3. Haz clic en **Root → Extract** para extraer todos los archivos.

---

## 📁 2. Reemplazar archivos con el mod

### Si descargaste el mod desde **GitHub**
El repositorio incluye una carpeta llamada **`files/`**.  
Debes:

1. Abrir la carpeta del juego ya extraído.
2. Copiar y **reemplazar** los archivos con los de la carpeta `files/` del mod.
   - Respeta la estructura de carpetas.

### Si descargaste el mod desde **GameBanana**
La descarga incluye **un solo archivo comprimido que contiene directamente los archivos del mod**, sin carpeta `files/`.

En este caso:

1. Extrae el archivo comprimido.
2. Copia los archivos extraídos **directamente** dentro de la carpeta del juego ya extraído.
3. Permite que se **reemplazen** los archivos originales.

---

## 🔧 3. Reconstruir el juego (ISO/GCM)

Puedes reconstruir la ISO modificada **tanto con GCR como con Dolphin**.

---

### ✔️ MÉTODO A – Reconstruir usando Dolphin

Dolphin permite reconstruir el ISO automáticamente si vuelves a empaquetarlo:

1. Ve a **Dolphin → Tools → Load GameCube Main Menu** *(opcional)*.
2. En la barra superior, abre **Tools → Build GameCube ISO**.
3. Selecciona la carpeta donde tienes el juego con los archivos modificados.
4. Dolphin generará un nuevo **ISO reconstruido** listo para usar.

> Nota: En algunas versiones, esta función aparece como **"Generate GameCube Disc Image"**.

---

### ✔️ MÉTODO B – Reconstruir usando GCR (GameCube Rebuilder)

1. Abre **GCR**.
2. Ve a **File → Open** y selecciona tu ISO/GCM original.
3. En el panel de archivos, asegúrate de que los archivos modificados están cargados.
4. Si hace falta, usa **Root → Import** para importar archivos modificados manualmente.
5. Ve a **Image → Rebuild**.
6. GCR generará una nueva ISO/GCM.

---

## 🎮 4. Ejecutar el juego

Puedes usar:

- **Dolphin Emulator** – Abre el ISO modificado y juega.
- **Hardware real (GameCube/Wii)** usando:
  - Swiss  
  - SD Gecko  
  - ODE (GC Loader / WiiKey Fusion)  

---

## ✔️ ¡Listo!

Ya tendrás Sonic Riders con **doblaje al español latinoamericano** funcionando correctamente.
