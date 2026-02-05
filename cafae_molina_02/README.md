# 🗺️ Mapa Interactivo de Colegios y Cuadrillas

## 🎯 Características principales
- **Sistema de semáforo de 3 colores** basado en campo 'semaforo'
- **🔍 Buscador AVANZADO** en ambas capas
- **Colegios:** 1036 puntos
- **Cuadrillas:** 38 polígonos
- **Generado:** 05/02/2026 11:40:46

## 🎨 Sistema de Semáforo (3 COLORES) - BASADO EN CAMPO 'SEMAFORO'
Las cuadrillas se colorean automáticamente según el campo 'semaforo':

- 🔴 **ROJO:** Valor 'rojo' en campo semaforo
- 🟠 **ANARANJADO:** Valor 'anaranjado' o 'naranja'  
- 🟡 **AMARILLO:** Valor 'amarillo' en campo semaforo

### Campos detectados en cuadrillas:
1. **semaforo** - Principal para coloreado
2. **id** - Identificador de cuadrilla
3. **ratio** - Valor numérico
4. **fid** - ID interno

## 🔍 BUSCADOR AVANZADO (NUEVO)
¡Busca en AMBAS CAPAS simultáneamente!

### ¿Qué puedes buscar?
**🏫 En COLEGIOS (dom_san_isidro):**
- Nombres de colegios/instituciones
- Códigos o IDs
- Direcciones
- Cualquier campo de texto

**📊 En CUADRILLAS (area_san_isidro):**
- **SEMÁFORO:** 'rojo', 'amarillo', etc.
- **ID:** identificador de cuadrilla
- **RATIO:** valores numéricos
- **FID:** ID interno

### Características del buscador:
1. **🔤 Búsqueda en tiempo real** - Resultados mientras escribes
2. **🎯 Filtrado por tipo** - Busca solo colegios, solo cuadrillas, o ambos
3. **🌈 Identificación visual** - Badges de colores para cada tipo
4. **📍 Navegación inteligente** - Clic en resultado para ir directamente
5. **💡 Resultados detallados** - Muestra información relevante

### Cómo usar:
1. Escribe en el campo de búsqueda 🔍
2. Usa los botones para filtrar por tipo
3. Los resultados aparecen automáticamente
4. Haz clic en un resultado para:
   - **Colegios:** Marcar con ícono azul especial
   - **Cuadrillas:** Resaltar polígono en púrpura

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
- ✅ **Sistema de semáforo basado en campo 'semaforo'**
- ✅ **🔍 Buscador avanzado en ambas capas**
- ✅ Panel de control minimizable
- ✅ Geolocalización del usuario
- ✅ Pantalla completa
- ✅ Popups informativos detallados
- ✅ Control de capas (mostrar/ocultar)
- ✅ Responsive design

## 🔧 Depuración y troubleshooting

### Si los colores no se muestran correctamente:
1. **Abre la consola del navegador** (F12)
2. **Busca mensajes que empiecen con**:
   - 🔍 Buscando color para: [valor del semáforo]
   - ✅ SEMÁFORO ROJO detectado -> ROJO
   - 🎨 Cuadrilla #[número]: "[valor]" -> Color: #[color]

### Si el buscador no encuentra resultados:
1. Verifica que hayas escrito al menos 2 caracteres
2. Prueba con diferentes términos:
   - Para cuadrillas: "rojo", "amarillo", "1", "2", etc.
   - Para colegios: nombres o códigos
3. Revisa la consola para mensajes de error

## 📄 Estructura de archivos
- `index.html` - Mapa principal con buscador avanzado
- `README.md` - Este archivo
- `.gitignore` - Archivos a ignorar

## 📞 Problemas comunes
1. **❌ No se ven colores:** 
   - Verifica que el campo 'semaforo' tenga valores válidos
   - Revisa la consola del navegador para mensajes de debug
   
2. **❌ Buscador no encuentra resultados:**
   - Espera a que se cargue completamente el mapa
   - Verifica que hayas escrito al menos 2 caracteres
   
3. **❌ GPS no funciona:**
   - Solo funciona con HTTPS (GitHub Pages tiene HTTPS)
   - No funciona localmente (file://)

4. **❌ GitHub Pages no carga:**
   - Espera 2-3 minutos después de activarlo
   - Verifica que subiste todos los archivos

---
*Generado automáticamente desde QGIS - 2026-02-05*

**NOTA IMPORTANTE:** 
- El sistema de colores usa el campo **'semaforo'** de las cuadrillas
- Valores reconocidos: 'rojo', 'amarillo', 'anaranjado', 'naranja'
- El buscador busca en todos los campos de ambas capas

**¡NUEVO!** Buscador avanzado que busca en colegios y cuadrillas simultáneamente.
