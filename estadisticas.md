# Estadísticas del Repositorio

## Integrante con mayor cantidad de commits

Comando utilizado:

```bash
git shortlog -sn --all
```

Resultado:

* Agustín (sugga222): 15 commits
* Manuel (ManuDeriver): 8 commits
* Manuel (Manuderiver): 4 commits

Integrante con mayor cantidad de commits: **Agustín**, con **15 commits**.

---

## Cantidad total de merges realizados

Comando utilizado:

```bash
git log --merges --oneline
```

Resultado:

Cantidad total de merges registrados: **13**.

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
