# Estadísticas del Repositorio

## Integrante con mayor cantidad de commits

Comando utilizado:

```bash
git shortlog -sne --all
```

Resultado obtenido:

Agustín:

* 10 commits (correo GitHub)
* 6 commits (correo personal)

Total: 16 commits

Manuel:

* 9 commits (correo personal)
* 4 commits (correo GitHub)

Total: 13 commits

Integrante con mayor cantidad de commits: **Agustín**, con **16 commits**.

---

## Cantidad total de merges realizados

Comando utilizado:

```bash
git log --merges --oneline
```

Resultado:

Cantidad total de merges registrados en el repositorio: **13**.

---

## Cantidad de conflictos producidos

Comando utilizado:

```bash
git log --merges --oneline
```

Resultado:

Cantidad de conflictos producidos: **1**.

Hash asociado a la resolución del conflicto:

```text
52cb777
```

Captura disponible en:

```text
capturas/captura conflicto.png
```

---

## Cantidad de ramas

Comando utilizado:

```bash
git branch -a
```

Resultado actual:

* main
* manuel
* prueba-rebase

Cantidad de ramas existentes actualmente: **3**.

Durante el desarrollo del trabajo también se utilizó la rama:

* agustin

Total de ramas utilizadas durante el proyecto: **4**.

---

## Commit con mayor cantidad de archivos modificados

Comando utilizado:

```bash
git log --stat --oneline
```

Resultado:

Hash del commit:

```text
37e72b7
```

Descripción:

```text
feat: agregar estructura inicial y comandos basicos
```

Cantidad de archivos modificados: **5**.

Archivos modificados:

* comandos-basicos.md
* estadisticas.md
* historial-y-recuperacion.md
* indice.md
* ramas-y-sincronizacion.md

Captura del diff disponible en:

```text
capturas/captura diff.png
```

---

## Observaciones

Durante el desarrollo del trabajo se utilizaron ramas, Pull Requests, revisiones, merges, resolución de conflictos, revert y rebase para aplicar los conceptos vistos en la cursada y mantener un flujo de trabajo colaborativo.

Las evidencias solicitadas por la consigna se encuentran almacenadas en la carpeta `capturas`.
