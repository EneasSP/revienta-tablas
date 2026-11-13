# ¡Revienta Tablas!

Juego para aprender las tablas de multiplicar reventando pompas de jabón.
Cada pompa sube con una cuenta; si tocás el resultado correcto antes de que llegue al techo, ¡revienta!

**Jugar:** https://eneassp.github.io/revienta-tablas/

Funciona en el navegador del celular, la tablet o la compu. No hay que instalar nada.

## Versiones

La versión actual está en `VERSION` y los cambios de cada una en [CHANGELOG.md](CHANGELOG.md).
Cada versión queda como tag `vX.Y.Z` y como release en GitHub con el .zip.

## Nueva versión

1. Cambiar el número en `VERSION` (por ejemplo `0.2.0`).
2. Anotar los cambios arriba de todo en `CHANGELOG.md`.
3. Correr `./build.ps1` (pone la versión en el juego y arma `dist/revienta-tablas-vX.Y.Z.zip`).
4. Commit, tag `vX.Y.Z`, push y `gh release create vX.Y.Z dist/revienta-tablas-vX.Y.Z.zip`.
