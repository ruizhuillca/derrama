# Mapas QGIS con Filtro por Oficina

## 🎨 Colores personalizados

| Capa | Color Normal | Color Filtrado |
|------|--------------|----------------|
| Oficina | ![](https://via.placeholder.com/15/FF0000/000000?text=+) `#FF0000` | ![](https://via.placeholder.com/15/FF6B6B/000000?text=+) `#FF6B6B` |
| Zonas | ![](https://via.placeholder.com/15/00FF00/000000?text=+) `#00FF00` | ![](https://via.placeholder.com/15/00CC00/000000?text=+) `#00CC00` |
| Territorio | ![](https://via.placeholder.com/15/0000FF/000000?text=+) `#0000FF` | ![](https://via.placeholder.com/15/0066CC/000000?text=+) `#0066CC` |

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

## 🎯 Cómo usar

1. **Mostrar/ocultar capas:** Checkboxes
2. **Filtrar por oficina:** Escribe y presiona 'Aplicar Filtro'
3. **Colores cambian** cuando se aplica filtro
4. **Limpiar filtro:** Botón 'Limpiar'

## 🌐 Para probar
```bash
python -m http.server 8000
```
http://localhost:8000

