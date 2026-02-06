# Mapas QGIS con Filtro por Oficina

## 📋 Capas exportadas

### Oficina
- **Elementos:** 64
- **Tipo:** Punto
- **Archivo:** `data/oficina.geojson`

### Zonas
- **Elementos:** 280
- **Tipo:** Polígono
- **Archivo:** `data/zonas.geojson`

### Territorio
- **Elementos:** 320
- **Tipo:** Polígono
- **Archivo:** `data/territorio.geojson`

## 🎯 Cómo usar el filtro

1. **Mostrar/ocultar capas:** Usa los checkboxes
2. **Filtrar por oficina:** Escribe en el campo de búsqueda
3. **Aplicar filtro:** Presiona 'Aplicar Filtro'
4. **Limpiar filtro:** Presiona 'Limpiar Filtro'

## 🌐 Para probar localmente

Debido a restricciones CORS, usa un servidor local:
```bash
# En la carpeta del proyecto:
python -m http.server 8000
```
Luego navega a: http://localhost:8000

## 📤 Para GitHub Pages

1. Sube toda la carpeta a GitHub
2. Ve a Settings > Pages
3. Configura: Source: main, Folder: / (root)

