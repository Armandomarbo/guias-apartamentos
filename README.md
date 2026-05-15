# Guías de apartamentos

Guías para huéspedes de los apartamentos turísticos gestionados por Armando.

Cada apartamento (o bloque de apartamentos) tiene su propia carpeta con un `index.html`. GitHub Pages las sirve en:

`https://armandomarbo.github.io/guias-apartamentos/<carpeta>/`

## Guías disponibles

| Apartamento(s) | URL |
|---|---|
| Gran Via 657 (A, 1º 2ª, 2º 1ª, 2º 2ª) | [/gran-via-657/](https://armandomarbo.github.io/guias-apartamentos/gran-via-657/) |
| Sants 158 | [/sants-158/](https://armandomarbo.github.io/guias-apartamentos/sants-158/) |
| Calle Mas 62 | [/mas-62/](https://armandomarbo.github.io/guias-apartamentos/mas-62/) |
| Calle Llull 16 (Poblenou) | [/llull-16/](https://armandomarbo.github.io/guias-apartamentos/llull-16/) |
| Amposta 1 (Font de la Guatlla) | [/amposta-1/](https://armandomarbo.github.io/guias-apartamentos/amposta-1/) |
| Prat de la Manta (Plz. Europa, L'Hospitalet) | [/prat-de-la-manta/](https://armandomarbo.github.io/guias-apartamentos/prat-de-la-manta/) |
| Natzaret Rooms (L'Hospitalet) | [/natzaret-rooms/](https://armandomarbo.github.io/guias-apartamentos/natzaret-rooms/) |
| Blas Fernández Lirola 38 (L'Hospitalet) | [/blas-fernandez-38/](https://armandomarbo.github.io/guias-apartamentos/blas-fernandez-38/) |
| Martí i Julià 199 (L'Hospitalet) | [/marti-julia-199/](https://armandomarbo.github.io/guias-apartamentos/marti-julia-199/) |
| Valencia 38 (Sant Adrià de Besòs) | [/valencia-38/](https://armandomarbo.github.io/guias-apartamentos/valencia-38/) |
| Mare de Déu del Carme 121 (Sant Adrià) | [/mare-de-deu-121/](https://armandomarbo.github.io/guias-apartamentos/mare-de-deu-121/) |
| Mare de Déu del Carme 123 (Sant Adrià) | [/mare-de-deu-123/](https://armandomarbo.github.io/guias-apartamentos/mare-de-deu-123/) |

Todas las guías están disponibles en versión bilingüe (español / inglés).

## Cómo añadir una nueva guía

1. Crear una carpeta nueva con un nombre descriptivo en kebab-case (`mare-de-deu-121`, `sants-llull`, etc.)
2. Subir el HTML autocontenido como `index.html` dentro de esa carpeta
3. Hacer commit & push a main — GitHub Pages despliega automáticamente en 1-2 minutos
4. En la app Lodgify Reservas → Pisos (checkin) → pegar la URL en el campo "Link de guía web" del piso correspondiente

Las guías son páginas HTML autocontenidas (todo el CSS y JS embebido) — no requieren build ni dependencias.
