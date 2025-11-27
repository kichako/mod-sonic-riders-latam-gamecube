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
- Dolphin Emulator para extraer los archivos del juego.

---

## 🗂️ 1. Extraer archivos del juego original

Puedes hacerlo de dos maneras:

### ✔️ Usando Dolphin
1. Abre **Dolphin**.
2. Haz clic derecho en tu copia de **Sonic Riders**.
3. Selecciona **"Properties" → "Sistema de archivos" → seleccionas el "disco" y le das a "Extraer archivos"**.
4. Guarda los archivos extraídos en una carpeta dentro de tu carpeta de juegos de Dolphin.

---

## 📁 2. Reemplazar archivos con el mod

### Si descargaste el mod desde **GitHub**
El repositorio incluye una carpeta llamada **`mod/`**.  
Debes:

1. Abrir la carpeta del juego ya extraído.
2. Copiar y **reemplazar** los archivos con los de la carpeta `mod/` del mod.
   - Respeta la estructura de carpetas.

### Si descargaste el mod desde **GameBanana**
La descarga incluye **un solo archivo comprimido que contiene directamente los archivos del mod**, sin carpeta `mod/`.

En este caso:

1. Extrae el archivo comprimido.
2. Copia los archivos extraídos **directamente** dentro de la carpeta del juego ya extraído.
3. Permite que se **reemplazen** los archivos originales.

---

## 🔧 3. Reconstruir el juego (ISO/GCM)

Dolphin permite reconstruir el ISO automáticamente si vuelves a empaquetarlo:

1. Asegurate que tengas agregada la ruta donde tengas tus juegos en **Dolphin**. y activada la opción de "Buscar en subcarpetas".
2. Te deberia salir el juego descomprimido, este suele aparecer con un tamaño de 000B.
3. Selecciona el juego descomprido en Dolphin y haz clic derecho.
4. Selecciona "Covertir archivo", selecciona "ISO" o "GCM" y guarda el archivo en la misma carpeta.
5. Dolphin generará un nuevo **ISO reconstruido** listo para usar.

---

## 🎮 4. Ejecutar el juego

Puedes usar:

- **Dolphin Emulator** – Abre el ISO modificado y juega.
- **Hardware real (GameCube/Wii)**

---

## ✔️ ¡Listo!

Ya tendrás Sonic Riders con **doblaje al español latinoamericano** funcionando correctamente.
