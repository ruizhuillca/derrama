# 🗺️ Mapa Interactivo de Colegios y Cuadrillas

## 🎯 Características principales
- **Sistema de semáforo de 3 colores** activado
- **Colegios:** 477 puntos
- **Cuadrillas:** 45 polígonos
- **Generado:** 23/12/2025 09:08:58

## 🎨 Sistema de Semáforo (3 COLORES)
Las cuadrillas se colorean automáticamente según su prioridad:

- 🔴 **ROJO:** Alta prioridad
- 🟠 **ANARANJADO:** Media prioridad  
- 🟡 **AMARILLO:** Baja prioridad

## 🔍 Cómo funciona el sistema de colores
1. El script busca automáticamente campos como: `prioridad`, `riesgo`, `nivel`, `color`, `estado`, `semáforo`
2. Detecta valores como: `alta`, `media`, `baja`, `alto`, `medio`, `bajo`
3. También reconoce colores: `rojo`, `amarillo`, `anaranjado`, `naranja`
4. También detecta valores numéricos: `1`, `2`, `3` (1=Alta, 2=Media, 3=Baja)
5. Asigna el color correspondiente según tu especificación

## 🚀 Cómo publicar en GitHub Pages

### Paso 1: Crear repositorio en GitHub
1. Ve a [github.com](https://github.com)
2. Haz clic en **"+"** → **"New repository"**
3. Nombre: `mapa-colegios` (o el que prefieras)
4. **IMPORTANTE:** Selecciona **"Public"**
5. Haz clic en **"Create repository"**

### Paso 2: Subir archivos
**Método fácil (Arrastrar y soltar):**
1. En tu repositorio, haz clic en **"Add file"** → **"Upload files"**
2. Arrastra TODOS los archivos de esta carpeta
3. Haz clic en **"Commit changes"**

### Paso 3: Activar GitHub Pages
1. En tu repositorio, ve a **Settings** → **Pages**
2. En **"Source"**, selecciona **"main"** branch
3. En **"Folder"**, selecciona **"/"** (root)
4. Haz clic en **Save**

### Paso 4: Obtener tu URL
1. Espera 1-2 minutos
2. Refresca la página de Settings → Pages
3. Verás: **"Your site is published at..."**
4. ¡Comparte esa URL! (Ej: `https://tunombre.github.io/mapa-colegios/`)

## 📱 Características del mapa
- ✅ Mapa interactivo con Leaflet.js
- ✅ **Sistema de semáforo de 3 colores** (funcionando)
- ✅ Panel de control minimizable
- ✅ Geolocalización del usuario
- ✅ Pantalla completa
- ✅ Popups informativos
- ✅ Control de capas (mostrar/ocultar)
- ✅ Responsive design

## 🔧 Depuración de colores
Si los colores no se muestran correctamente:

1. **Abre la consola del navegador** (F12)
2. **Busca mensajes que empiecen con**:
   - 🔍 Buscando color para prioridad...
   - ✅ Coincidencia exacta encontrada...
   - 🎨 Color asignado: #color...
3. **Verifica** que tus datos tengan un campo de prioridad

## 📄 Estructura de archivos

## 📞 Problemas comunes
1. **❌ No se ven colores:** 
   - Verifica que tus cuadrillas tengan un campo de prioridad
   - Revisa la consola del navegador para mensajes de error
   
2. **❌ GPS no funciona:**
   - Solo funciona con HTTPS (GitHub Pages tiene HTTPS)
   - No funciona localmente (file://)

3. **❌ GitHub Pages no carga:**
   - Espera 2-3 minutos después de activarlo
   - Verifica que subiste todos los archivos

---
*Generado automáticamente desde QGIS - 2025-12-23*

**NOTA:** Sistema de semáforo configurado según: ROJO=Alta, ANARANJADO=Media, AMARILLO=Bajo
