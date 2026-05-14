# Guías de apartamentos

Guías para huéspedes de los apartamentos turísticos gestionados por Armando.

Cada apartamento (o bloque de apartamentos) tiene su propia carpeta con un `index.html`. GitHub Pages las sirve en:

`https://armandomarbo.github.io/guias-apartamentos/<carpeta>/`

## Guías disponibles

| Apartamento(s) | URL |
|---|---|
| Gran Via 657 (A, 1º 2ª, 2º 1ª, 2º 2ª) | [/gran-via-657/](https://armandomarbo.github.io/guias-apartamentos/gran-via-657/) |
| Sants 158 | [/sants-158/](https://armandomarbo.github.io/guias-apartamentos/sants-158/) |

## Cómo añadir una nueva guía

1. Crear una carpeta nueva con un nombre descriptivo en kebab-case (`mare-de-deu-121`, `sants-llull`, etc.)
2. Subir el HTML autocontenido como `index.html` dentro de esa carpeta
3. Hacer commit & push a main — GitHub Pages despliega automáticamente en 1-2 minutos
4. En la app Lodgify Reservas → Pisos (checkin) → pegar la URL en el campo "Link de guía web" del piso correspondiente

Las guías son páginas HTML autocontenidas (todo el CSS y JS embebido) — no requieren build ni dependencias.
