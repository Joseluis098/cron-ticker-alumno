# Entrega - GitHub Actions `cron-ticker`

Repositorio: https://github.com/Joseluis098/cron-ticker-alumno

## Capturas

1. `png/01-local-install-test-verde.png` - `npm install` y `npm test` local en verde.
2. `png/02-workflow-ci-yml.png` - contenido de `.github/workflows/ci.yml`.
3. `png/03-actions-inicial-verde.png` - primer workflow exitoso con steps del job `test`.
4. `png/04-test-roto-999.png` - commit donde `multiply` cambia de `toBe(12)` a `toBe(999)`.
5. `png/05-actions-rojo-fallo.png` - workflow rojo con `Run tests` fallando y log `Expected: 999 / Received: 12`.
6. `png/06-test-corregido-12.png` - correccion del test a `toBe(12)` y `npm test` local en verde.
7. `png/07-actions-final-verde.png` - workflow final verde con secuencia verde -> rojo -> verde.
8. `png/08-commits-y-repo.png` - historial de commits y enlaces del repositorio.

## Runs en GitHub

- Verde inicial: https://github.com/Joseluis098/cron-ticker-alumno/actions/runs/28833378857
- Rojo intencional: https://github.com/Joseluis098/cron-ticker-alumno/actions/runs/28833409720
- Verde final: https://github.com/Joseluis098/cron-ticker-alumno/actions/runs/28833448567

Nota: las capturas fueron generadas desde salidas reales de `npm`, `git` y `gh` porque el navegador integrado no estaba disponible en esta sesion. Los archivos completos de texto estan en `text/`.
