# Medidas Apto Jacaranda B3

Planos y medidas de muebles para llevar en el celular. Sin servidor, sin internet después de la primera vez.

## Publicar en GitHub Pages

1. Crea un repositorio nuevo en GitHub (por ejemplo `medidas-apto`).
2. Sube todos los archivos de esta carpeta a la raíz del repositorio (botón **Add file → Upload files**).
3. Ve a **Settings → Pages**. En **Source** elige **Deploy from a branch**, rama `main`, carpeta `/ (root)` y guarda.
4. En un par de minutos la página queda en `https://TU-USUARIO.github.io/medidas-apto/`.

## Instalar en el celular

- **Android (Chrome):** menú ⋮ → **Instalar app**.
- **iPhone (Safari):** Compartir → **Agregar a pantalla de inicio**.

Abre la app una vez con internet. Después funciona en modo avión.

## Qué trae

- **Versión 1 y 2:** el plano con zoom (pellizcar), arrastre y toque en cada mueble.
- **Muebles:** medida recomendada y máxima, en cm o en m.
- **¿Cabe?:** escribe ancho y fondo de lo que viste en la tienda y te dice dónde entra y cuánto sobra o falta.
- **Cotización:** marca, tienda, teléfono, precio y notas por mueble, con total estimado.

## Tus datos

Las cotizaciones y notas se guardan solo en el navegador de cada celular. No se suben a ningún lado.
Para pasarlas a otro teléfono: **Cotización → Guardar respaldo** y luego **Cargar respaldo** en el otro.

## Privacidad

La página no incluye número de unidad ni dirección, y trae la etiqueta `noindex` para que Google no la indexe.
Aun así, si el repositorio es público, cualquiera con el enlace puede verla.

## Actualizar

Si cambias `index.html`, sube también un número nuevo en `VERSION` dentro de `sw.js` (por ejemplo `medidas-v2`).
Así los celulares que ya la instalaron reciben la versión nueva.
