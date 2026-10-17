# Excavando Pozo Nieve

Juego de excavación arqueológica en primera persona, ambientado en un alero de granito de Pampa de Achala (Sierras Grandes de Córdoba, Argentina).

Excavás cuatro cuadrículas de 1 × 1 m por niveles artificiales de 5 cm. Las piezas se limpian con pincel, se registran y se levantan antes de seguir bajando, y el sedimento se cierne en zaranda. La libreta de campo y el plano de la excavación se descargan en PDF.

## Cómo jugar

| Acción | Computadora | Celular |
|---|---|---|
| Caminar | W A S D (Shift para apurar el paso) | Joystick a la izquierda |
| Mirar | Mouse (clic para fijar el puntero) | Arrastrar a la derecha |
| Usar herramienta | Clic (mantener para seguir) | Botón **Usar** |
| Cucharín / pincel / zaranda | 1 / 2 / 3 | Barra inferior |
| Agacharse | C | Botón **Agachar** |
| Libreta / colección | L / V | Barra inferior |

La regla de oro: si excavás por debajo de una pieza sin registrarla, se pierde su contexto.

La partida se guarda sola en el navegador de cada jugador.

## Publicarlo con GitHub Pages

1. Creá una cuenta en https://github.com (si no tenés).
2. Arriba a la derecha: **+** → **New repository**. Nombre sugerido: `pozo-nieve`. Dejalo **Public** y tocá **Create repository**.
3. En la página del repositorio nuevo: **Add file** → **Upload files**. Arrastrá `index.html` y este `README.md`. Abajo, **Commit changes**.
4. Andá a **Settings** → **Pages** (menú de la izquierda).
5. En **Build and deployment** → **Source**, elegí **Deploy from a branch**. En **Branch**, elegí `main` y la carpeta `/ (root)`. **Save**.
6. Esperá uno o dos minutos y recargá esa página: arriba aparece el enlace, del tipo `https://TU-USUARIO.github.io/pozo-nieve/`.

Para actualizar el juego, volvé a subir un `index.html` nuevo con **Add file → Upload files**: reemplaza al anterior y el sitio se actualiza solo.

## Requisitos técnicos

- Funciona en cualquier navegador actual con WebGL (Chrome, Firefox, Edge, Safari), en computadora o celular.
- Necesita conexión a internet para cargar las librerías desde cdnjs (three.js r128 y jsPDF 2.5.1) y las tipografías de Google Fonts.
- No usa servidor ni base de datos: es un único archivo `index.html`.

## Créditos y fuentes

- Modelos de piezas líticas tomados de las láminas del Trabajo Final de Grado de Matías Álvarez (UNC).
- Puntas óseas, artefacto de hematita, fragmentos óseos decorados y pendiente de filita: fotografías de Rivero et al. (2024), reproducidas en el TFG. **Antes de publicar el repositorio de forma abierta, conviene confirmar el permiso de uso de esas imágenes.**
- Materialidad lítica: Sario et al. (2022), *Relaciones de la Sociedad Argentina de Antropología* 47(1); Recalde (2009), *Anales de Arqueología y Etnología* 63-64.
- Cerámica de las Sierras de Córdoba: Figueroa, Pautassi y Dantas (2011), *ArqueoWeb* 13.

El sitio "Pozo Nieve", su estratigrafía y la distribución de hallazgos son ficticios y tienen fines didácticos.
