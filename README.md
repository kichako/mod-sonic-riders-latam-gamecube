# Mod de Sonic Riders (GameCube) – Doblaje Español Latino  
## Guía de Instalación

---

## 📁 Estructura del repositorio

Este repositorio se organiza de la siguiente manera:

```
mod-sonic-riders-latam-gamecube/
├─ README.md
└─ files/
   ├─ *.DAT
   ├─ *.ADX
   ├─ *.AFS
   └─ *.SFD
```

- `files/` contiene todos los archivos del mod listos para reemplazar en la carpeta del juego extraído.
- `*.DAT` incluye paquetes de datos utilizados por personajes y recursos del juego.
- `*.ADX` contiene audios (diálogos, música, efectos) en formato ADX.
- `*.AFS` son bancos de audio empaquetados.
- `*.SFD` almacena videos del juego (formato Sofdec).

Si solo quieres aplicar el mod, copia el contenido de `files/` dentro de la carpeta del juego que extrajiste siguiendo los pasos de esta guía.

Esta guía explica cómo aplicar correctamente el mod de doblaje al español latino a una ISO limpia de **Sonic Riders (Nintendo GameCube)** utilizando **GC Rebuilder**, con la alternativa de hacer la extracción desde **Dolphin Emulator**.

---

## ✅ Requisitos

Antes de comenzar, asegúrate de contar con:

1. **Una ISO limpia de Sonic Riders (GameCube)**  
   - Debe ser una copia legal y sin modificaciones previas.

2. **GC Rebuilder**  
   - Herramienta para abrir, extraer y reconstruir ISOs de GameCube.  
   - Descarga: https://www.romhacking.net/utilities/619/

3. **El mod descargado desde GitHub**  
   - En el repositorio, haz clic en **Code** → **Download ZIP**  
   - Extrae el archivo ZIP en tu PC.

4. **(Opcional)** Dolphin Emulator  
   - Puede usarse para extraer los archivos del juego si no deseas hacerlo desde GC Rebuilder.

---

## 🟩 Paso 1 — Descargar el mod

1. Entra al repositorio:  
   https://github.com/kichako/mod-sonic-riders-latam-gamecube
2. Haz clic en **Code** (botón verde).
3. Selecciona **Download ZIP**.
4. Extrae el contenido del ZIP en una carpeta.

---

## 🟩 Paso 2 — Preparar tu ISO original

1. Ubica tu archivo del juego, por ejemplo:  
   `Sonic Riders (USA).iso`
2. Colócalo en una carpeta separada.
3. Verifica que sea una ISO limpia (sin modificaciones).

---

## 🟩 Paso 3 — Extraer los archivos del juego

### 🔵 Opción A: Extraer usando GC Rebuilder

1. Abre **GCR.exe**.
2. Selecciona:  
   **Image → Open…**  
   y elige tu ISO original.
3. Luego selecciona:  
   **Image → Extract…**
4. Crea una carpeta nueva, por ejemplo:  
   `Riders_EXTRACTED`
5. Espera a que finalice la extracción.

### 🔵 Opción B: Extraer usando Dolphin Emulator

1. Abre **Dolphin**.
2. Agrega tu ISO de Sonic Riders si no aparece en la lista.
3. Haz clic derecho sobre el juego.
4. Selecciona **"Extract Files…"**  
   *(en algunas versiones aparece como "Extract Disc Contents")*.
5. Elige una carpeta para extraer los archivos.
6. Espera a que Dolphin termine la extracción.

Ambos métodos generan una carpeta con la estructura interna del juego necesaria para aplicar el mod.

---

## 🟩 Paso 4 — Reemplazar los archivos originales con los del mod

1. Abre la carpeta extraída del juego (desde Dolphin o GC Rebuilder).
2. Abre la carpeta que contiene el contenido del mod.
3. Copia **todos** los archivos dentro de `files/`.
4. Pégalos en la carpeta extraída del juego.
5. Cuando Windows pregunte si deseas reemplazar archivos, selecciona:  
   ✔️ **Reemplazar los archivos en el destino**

---

## 🟩 Paso 5 — Reconstruir la ISO modificada (solo con GC Rebuilder)

> **Nota:** Dolphin NO puede reconstruir ISOs.  
> Para este paso **es obligatorio usar GC Rebuilder**.

1. Abre **GC Rebuilder**.
2. Selecciona:  
   **Root → Open…**
3. Elige la carpeta donde reemplazaste los archivos del juego.
4. Luego selecciona:  
   **Image → Rebuild…**
5. Elige una ubicación y un nombre para la nueva ISO, por ejemplo:  
   `Sonic Riders LATAM.iso`
6. Espera a que termine el proceso.

Una vez finalizado, la ISO estará lista con el doblaje aplicado.

---

## 🟦 Paso 6 — Cargar el juego

Puedes usar cualquier método compatible con ISOs de GameCube, como:

### 🟢 Dolphin Emulator
1. Abre Dolphin.  
2. Arrastra la ISO reconstruida (`Sonic Riders LATAM.iso`).  
3. Selecciónala y ejecútala.

### 🟢 Wii con Homebrew (Nintendont / Swiss)
1. Copia la ISO a tu tarjeta SD o dispositivo USB.
2. Cárgala con tu cargador de GameCube preferido.

---

## 🟣 Notas importantes

- No elimines ni renombres archivos dentro de la estructura del juego.  
- Asegúrate de realizar el reemplazo de archivos correctamente.  
- Si el rebuild falla, usa rutas cortas como:  
  `C:/Riders/`
- Dolphin solo sirve para **extraer**, no para reconstruir la ISO.

---

## ✔️ Instalación completada

Tu copia del juego debería funcionar correctamente con el doblaje al español latino aplicado.
