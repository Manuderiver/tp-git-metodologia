# Historial y recuperación

## git diff

Permite visualizar las diferencias entre versiones de archivos. Es útil para revisar los cambios realizados antes de realizar un commit o para comparar distintas versiones de un mismo archivo.

### Ejemplo

```bash
git diff
```

Muestra los cambios que aún no fueron agregados al área de preparación.

---

## git show

Muestra información detallada sobre un commit específico, incluyendo autor, fecha y cambios realizados.

### Ejemplo

```bash
git show
```

Muestra información del último commit realizado.

---

## git restore

Permite restaurar archivos a un estado anterior, descartando cambios que todavía no fueron confirmados mediante un commit.

### Ejemplo

```bash
git restore archivo.txt
```

Restaura el archivo indicado a su última versión guardada.

---

## git revert

Crea un nuevo commit que deshace los cambios realizados por un commit anterior, manteniendo el historial del repositorio.

### Ejemplo

```bash
git revert a1b2c3d
```

Genera un nuevo commit que revierte los cambios del commit indicado.

---

## git reset

Permite mover la referencia de la rama actual a un commit anterior. Dependiendo de la opción utilizada, también puede modificar el área de preparación y los archivos del directorio de trabajo.

### Ejemplo

```bash
git reset --soft HEAD~1
```

Deshace el último commit manteniendo los cambios preparados para un nuevo commit.
