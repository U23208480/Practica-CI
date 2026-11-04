# Practica-CI

Practica de Integracion Continua con GitHub Actions.

El workflow `.github/workflows/ci.yml` se ejecuta en cada `push` y en cada `pull_request` hacia `main`:
1. Descarga el codigo del repositorio.
2. Configura Node.js.
3. Compila (verifica sintaxis).
4. Ejecuta las pruebas.
