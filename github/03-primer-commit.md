# 03 · Tu primer commit, sin usar la terminal

[← Índice](README.md) · [Anterior: tu primer issue](02-primer-issue.md) · [Siguiente: ramas y pull requests →](04-ramas-y-pull-requests.md)

**Meta:** crear `ejemplo.md` y encontrar el cambio guardado en el historial. **Tiempo estimado:** 5 minutos. Usa tu repositorio privado `mi-primer-proyecto`.

## En palabras simples

Un **commit** es un punto guardado en el historial del proyecto. Lleva un mensaje que cuenta qué cambió. Es como guardar una versión de tu trabajo con una etiqueta que luego puedes reconocer.

![Maqueta de tres pasos: crear ejemplo.md, guardarlo con el mensaje Agregar lista de estudio y encontrar ese mensaje en History.](../assets/ejemplo-commit.svg)

## 1. Crear y previsualizar el archivo

- **¿Por qué?** Ver cómo quedará el texto antes de guardarlo ayuda a detectar una lista mal escrita.
- **¿Para qué?** Para preparar una lista de estudio en un archivo de ejemplo sin tocar el README.
- **¿Cómo?** En **Code → Add file → Create new file**, nombra el archivo `ejemplo.md`. Copia la lista de abajo y pulsa **Preview** para ver las casillas.
- **¿Cuándo usarlo?** Cuando agregues una nota o un ejemplo en Markdown y quieras revisar cómo se leerá.

```markdown
# Lista de estudio

- [x] Crear mi primer repositorio
- [ ] Repasar GitHub
```

## 2. Guardar el cambio (commit)

- **¿Por qué?** Un mensaje como «Agregar lista de estudio» se reconoce mejor que «Cambios» semanas después.
- **¿Para qué?** Para dejar en el historial un registro de qué se añadió y cuándo.
- **¿Cómo?** Pulsa **Commit changes…** y escribe `Agregar lista de estudio`. En tu repositorio privado de práctica, elige guardar en la rama actual (normalmente `main`) si GitHub lo permite. Confirma con **Commit changes**. En un proyecto compartido, sigue sus reglas de revisión.
- **¿Cuándo usarlo?** Al terminar un cambio con sentido propio, como añadir un ejemplo o corregir una instrucción.

## 3. Consultar el historial del archivo

- **¿Por qué?** Ver el archivo actual no siempre te dice en qué cambio apareció cada parte.
- **¿Para qué?** Para identificar qué commit añadió el archivo y comprobar las líneas guardadas.
- **¿Cómo?** Abre `ejemplo.md`, pulsa **History**, busca **Agregar lista de estudio** y abre el commit para ver el archivo y sus líneas nuevas.
- **¿Cuándo usarlo?** Después de guardar un cambio para comprobarlo, o más adelante cuando necesites saber qué se modificó.

## Comprueba que funcionó

- [ ] `ejemplo.md` aparece en **Code** y muestra la lista.
- [ ] **History** contiene **Agregar lista de estudio**, y el cambio corresponde a ese archivo.

**¿No ves el archivo?** Comprueba que estés mirando la misma rama en la que guardaste el commit. Confirma también que escribiste el nombre con la extensión `.md`.

Deja abierto el issue **Agregar un ejemplo al README** de la guía anterior: ya creaste el archivo de ejemplo, pero todavía no lo explicaste en el README. Ese será el trabajo de la próxima guía.

[Documentación oficial de GitHub: crear archivos desde el navegador](https://docs.github.com/es/repositories/working-with-files/managing-files/creating-new-files)
