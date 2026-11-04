# Circuitos Lab

Aplicación educativa para practicar análisis de circuitos eléctricos.

## Uso local

Abre `index.html` en un navegador moderno. No requiere instalación, servidor ni dependencias. El progreso, los ejercicios resueltos y los circuitos guardados se conservan en el almacenamiento local del navegador.

## Módulos

- **Simulador:** crea redes con resistencias, fuentes ideales de voltaje o corriente y cables. Edita los terminales para conectarlos a GND, N1, N2 o N3. El análisis nodal DC calcula voltajes, corrientes y potencias; el multímetro mide voltaje entre nodos, corriente, potencia y resistencia nominal.
- **Aprender:** ocho capítulos de fundamentos, ley de Ohm, serie/paralelo, nodos, mallas, Thévenin, Norton y CA. Cada capítulo incluye teoría, ejercicio, editor de procedimiento, pistas y registro del resultado correcto.
- **Exámenes:** cuatro rutas temáticas con preguntas de opción múltiple y explicación paso a paso después de cada respuesta.

El simulador resuelve circuitos DC lineales en estado estacionario. Los capítulos de corriente alterna y transitorios son de práctica guiada, no de simulación de formas de onda.

## Publicar en GitHub Pages

El repositorio incluye un flujo de GitHub Actions que publica el sitio al actualizar la rama `main`.

1. Crea un repositorio en GitHub llamado, por ejemplo, `circuitos-lab`.
2. Sube el contenido de esta carpeta a la raíz del repositorio y usa `main` como rama principal.
3. En GitHub, abre **Settings → Pages** y selecciona **GitHub Actions** como fuente de publicación.
4. Cada actualización enviada a `main` iniciará la publicación. Revisa la pestaña **Actions**; al terminar, GitHub mostrará la dirección del sitio.

La URL habitual para un repositorio de proyecto es `https://TU-USUARIO.github.io/circuitos-lab/`. GitHub Pages está disponible gratuitamente para repositorios públicos en GitHub Free; los repositorios privados requieren un plan compatible.

