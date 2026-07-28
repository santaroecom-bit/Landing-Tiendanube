# Landing-Tiendanube

Landings de producto para la tienda **SÁNTARO** (Tiendanube).

## 📁 Estructura

```
Landing-Tiendanube/
├── landings/        ← LAS 14 LANDINGS FINALES (esto es lo que se pega en Tiendanube)
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

| Archivo | Producto | Precio |
|---|---|---|
| `cama-moises-negra.html` | Cama Moisés negra (lona tracker + peluche negro, 80x50) | $70.000 → $55.000 |
| `cama-moises-beige.html` | Cama Moisés peluche beige (80x50) | $70.000 → $55.000 |
| `cama-moises-alaska.html` | Moisés Alaska 57x57, interior gris oscuro | $100.000 → $40.000 |
| `cama-moises-alaska-beige.html` | Moisés Alaska 57x57, interior beige | $100.000 → $40.000 |
| `cama-moises-alaska-grande.html` | Moisés Alaska 80x60, interior beige | $200.000 → $75.000 |
| `cama-moises-alaska-grande-gris.html` | Moisés Alaska 80x60, interior gris oscuro | $200.000 → $75.000 |
| `cama-puff-gris.html` | Cama puff redonda 60 cm, pelo gris | $80.000 → $50.000 |
| `cama-puff-beige.html` | Cama puff redonda 60 cm, pelo beige | $80.000 → $50.000 |
| `cama-puff-nordica-xl.html` | Puff nórdica XL 100x100, beige | $200.000 → $100.000 |
| `cama-puff-nordica-xl-gris.html` | Puff nórdica XL 100x100, gris | $200.000 → $100.000 |
| `cama-colchoneta-negra.html` | Colchoneta 80x50x15, microfibra negra | $150.000 → $65.000 |
| `cama-colchoneta-beige.html` | Colchoneta 80x50x15, microfibra beige | $150.000 → $65.000 |
| `rascador-multinivel-peluche-beige.html` | Rascador multi-nivel peluche beige | $200.000 → $160.000 |
| `rascador-multinivel-alfombra-marron.html` | Rascador multi-nivel alfombra marrón | $200.000 → $160.000 |

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
