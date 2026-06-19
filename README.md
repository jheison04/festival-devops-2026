# Festival DevOps Music Fest

![CI Status](https://github.com/jheison04/festival-devops-2026/actions/workflows/ci.yml/badge.svg)

## Integración Continua con GitHub Actions

Este proyecto utiliza GitHub Actions para validar automáticamente los archivos del proyecto.

### ¿Qué valida?

- ✅ index.html
- ✅ style.css  
- ✅ README.md

### Workflow Configurado

Archivo: `.github/workflows/ci.yml`

El workflow se ejecuta cuando:
- Se hace push a la rama main
- Se crea un Pull Request

### Estado Actual

El badge verde indica que todas las validaciones pasaron correctamente.

### Commits Realizados

- `84db60d` - ci: configurar workflow de validación
- `57ca53e` - docs: agregar badge de estado

---

**Instructor:** Efrén Moreno Valoyes - emorenov@sena.edu.co
