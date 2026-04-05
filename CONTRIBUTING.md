# Contribuciones

¡Gracias por ayudar a expandir este repositorio de textos legales costarricenses!

## Fuente oficial

Todos los textos legales deben corresponder a su **versión más reciente** y obtenerse desde el sitio oficial de la Procuraduría General de la República:

👉 [https://pgrweb.go.cr](https://pgrweb.go.cr)

## Metodología para obtener un texto legal

1. Busca la ley, código o constitución en [pgrweb.go.cr](https://pgrweb.go.cr) y abre su texto completo.
2. Usa la opción **"Guardar"** del navegador para guardar la página en formato HTML plano (`.html`).
3. Convierte el archivo a Markdown con el comando `markitdown`:
   ```bash
   markitdown archivo.html > Nombre_de_la_Ley.md
   ```
4. Limpia el nombre del archivo resultante:
   - Elimina caracteres especiales del español: tildes (`á é í ó ú`), eñes (`ñ`), diéresis (`ü`) y replazar espacios con guión bajo.

## Agregar un Nuevo Documento

1. **Coloca el archivo** en el directorio correspondiente:
   - `codigos/` — para códigos (Código de Familia, Código Procesal, etc.)
   - `constituciones/` — para la constitución
   - `leyes/` — para leyes especiales
   - Crea un nuevo directorio si el documento no encaja en ninguna categoría.

2. **Nombra el archivo** usando guiones bajos en lugar de espacios, siguiendo el patrón:
   ```
   Nombre_de_la_Ley.md
   ```

3. **Registra el archivo** en [`AGENTS.md`](./AGENTS.md) agregándolo al árbol de estructura del proyecto con una breve descripción en línea que incluya el número de ley (ej. `Ley N° XXXX`).

## Formato de los Archivos

- Los archivos deben estar en Markdown (`.md`).
- Conserva el texto original de la manera más fiel posible.
- Usa el título oficial de la ley como nombre del archivo.
