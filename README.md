# Landing-Tiendanube

Landings de producto para la tienda **SÁNTARO** (Tiendanube).

## 📁 Estructura

```
Landing-Tiendanube/
├── landings/        ← LAS 13 LANDINGS FINALES (esto es lo que se pega en Tiendanube)
├── correcciones/    ← Bloques de reseñas sueltos (por si se quiere editar solo esa parte)
├── assets/          ← contador-santaro.gif (el temporizador animado)
└── README.md
```

## ✅ Cómo usar las landings

1. Abrir el producto en Tiendanube → **Descripción** → botón **Fuente HTML (`</>`)**.
2. Borrar lo que haya y **pegar el archivo completo** de `landings/` que corresponda.
3. Reemplazar las imágenes placeholder (`URL_IMAGEN_...`) por las fotos reales:
   - Foto de "Lo que recibís en tu casa" (`..._INCLUYE`)
   - Foto de contexto (`URL_IMAGEN_CONTEXTO_...`)
   - Logos de pago (Mercado Pago + Andreani/Correo)
   - GIF del contador (`URL_GIF_CONTADOR`) — subir `assets/contador-santaro.gif`
4. Guardar.

> ⚠️ Siempre en modo **Fuente HTML**, nunca en el editor visual (lo rompe).
> La foto de portada NO va en la descripción: ya está integrada arriba en Tiendanube.

## 🛏️ Productos (carpeta `landings/`)

Los archivos están nombrados por **medidas** para identificarlos rápido.

| Archivo | Producto | Precio |
|---|---|---|
| `57x57-alaska-gris.html` | Moisés Alaska 57x57x25, interior gris oscuro | $100.000 → $40.000 |
| `57x57-alaska-beige.html` | Moisés Alaska 57x57x25, interior beige | $100.000 → $40.000 |
| `80x60-shelter.html` | Cama Moisés Shelter L 80x60x25 (unificada, color a elección: gris oscuro / beige) | $130.000 → $70.000 (transf. $63.000) |
| `60cm-puff-gris.html` | Cama puff redonda 60 cm, pelo gris | $80.000 → $50.000 |
| `60cm-puff-beige.html` | Cama puff redonda 60 cm, pelo beige | $80.000 → $50.000 |
| `100x100-nordica-beige.html` | Puff nórdica XL 100x100x20, beige | $200.000 → $100.000 |
| `100x100-nordica-gris.html` | Puff nórdica XL 100x100x20, gris | $200.000 → $100.000 |
| `80x50x15-colchoneta-negra.html` | Colchoneta 80x50x15, microfibra negra | $150.000 → $65.000 |
| `80x50x15-colchoneta-beige.html` | Colchoneta 80x50x15, microfibra beige | $150.000 → $65.000 |
| `100x90x15-colchoneta-negra.html` | Colchoneta 100x90x15, microfibra negra (perros grandes) | $200.000 → $93.000 |
| `100x90x15-colchoneta-beige.html` | Colchoneta 100x90x15, microfibra beige (perros grandes) | $200.000 → $93.000 |
| `rascador-peluche-beige.html` | Rascador multi-nivel peluche beige | $200.000 → $160.000 |
| `rascador-alfombra-marron.html` | Rascador multi-nivel alfombra marrón | $200.000 → $160.000 |
| `guia-de-talles.html` | Guía de talles (no es producto: página de referencia de medidas) | — |

## 🎨 Características comunes de todas las landings

- **HTML con estilos inline** (sin `<style>` ni `<script>`), porque el editor de Tiendanube los elimina.
- **Tipografías, colores y layout** de la identidad SÁNTARO (marrón #5C4033 / crema #F8EFE4).
- **Texto centrado** y **responsive** (se adapta a celular y PC).
- **Sin foto de portada** en la descripción (esa va integrada aparte en Tiendanube).
- **50-60 reseñas** por producto, con botón "Ver más opiniones" que despliega de a tandas
  (usa `<details>` nativos, funcionan sin JavaScript).
- **FAQ** desplegable y **logos de pago** parejos.

## 📝 correcciones/

Contiene solo el **bloque de reseñas** de cada producto por separado. Sirve si en vez de
re-pegar la landing entera se quiere reemplazar únicamente la sección de reseñas
(sin tocar el resto ni las imágenes ya cargadas).
