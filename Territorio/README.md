# 🗺️ Mapas QGIS - Filtro Múltiple por Oficinas

## 🎯 Características

✅ **Filtro múltiple:** Puedes filtrar por varias oficinas a la vez
✅ **Separar por comas:** Ej: `trujillo, otuzco, huamachuco`
✅ **Case insensitive:** No distingue mayúsculas/minúsculas
✅ **Sin acentos:** Puedes escribir con o sin acentos

## 📋 Capas exportadas

### Oficina
- **Elementos:** 64
- **Archivo:** `data/oficina.geojson`
- **Ejemplos de oficinas:** OFICINA_ACP, CHOTA, AYACUCHO, TINGO MARIA, CASMA, PAMPAS, NAZCA, HUANCAYO, DM MINKA, ATE

### Zonas
- **Elementos:** 280
- **Archivo:** `data/zonas.geojson`
- **Ejemplos de oficinas:** CHOTA, AYACUCHO, TINGO MARIA, CASMA, PAMPAS, NAZCA, HUANCAYO, DM MINKA, ATE, LAMBAYEQUE

### Territorio
- **Elementos:** 320
- **Archivo:** `data/territorio.geojson`
- **Ejemplos de oficinas:** CAMANA, HUARI, CHOTA, AYACUCHO, TINGO MARIA, CASMA, CHANCHAMAYO, NAZCA, HUANCAYO, PAMPAS

## 🚀 Cómo usar

### 📝 Ejemplos de búsqueda:
```
trujillo, otuzco
huamachuco, cajabamba
trujillo, otuzco, huamachuco, cajabamba
TRUJILLO, Otuzco, Huamachuco  # Case insensitive
```

### 🔧 Funciones avanzadas:
1. **Búsqueda parcial:** `truji` encontrará `trujillo`, `trujillano`, etc.
2. **Sin acentos:** `huamachuco` y `huamáchuco` funcionan igual
3. **Espacios automáticos:** Se ignoran espacios extras

## 🌐 Para probar localmente
```bash
cd D:\2026\Nueva Zonificacion\GitHub
python -m http.server 8000
```
Luego navega a: **http://localhost:8000**

## 📤 Para GitHub Pages
1. Sube toda la carpeta a un repositorio GitHub
2. Ve a **Settings > Pages**
3. Configura: Source: main, Folder: / (root)
4. Tu mapa estará en: `https://tuusuario.github.io/repositorio/`

## 🔍 Ejemplos prácticos
```
# Filtrar por varias ciudades de La Libertad:
trujillo, otuzco, huamachuco, sanchez carrion

# Filtrar por ciudades principales:
trujillo, chiclayo, piura, tumbes

# Filtrar por zonas específicas:
centro, norte, sur, este
```

## 🛠️ Solución de problemas
- **No encuentra resultados:** Verifica que los nombres estén escritos correctamente
- **Loading no desaparece:** Abre la consola (F12) para ver errores
- **CORS errors:** Usa un servidor local como indicado arriba

---
*Sistema de filtro múltiple por oficinas - Exportado desde QGIS*
