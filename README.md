# Leyes de Costa Rica

Repositorio de leyes de Costa Rica en formato Markdown: constitución política, códigos y leyes especiales. Diseñado para facilitar su procesamiento con agentes de inteligencia artificial, búsqueda de texto y análisis automatizado.

## ¿Por qué Markdown?

- **Legible por humanos y máquinas** — fácil de leer directamente o de procesar con herramientas de IA.
- **Compatible con control de versiones** — cada cambio en el texto legal queda registrado en el historial de Git.
- **Portable** — no requiere software propietario ni licencias especiales.

## Contenido

| Directorio | Descripción |
|---|---|
| `codigos/` | Códigos legales (Familia, Niñez y Adolescencia, Procesal de Familia) |
| `constituciones/` | Constitución Política de la República de Costa Rica |
| `leyes/` | Leyes especiales (Pensiones Alimentarias, Notificaciones Judiciales) |

Para el detalle de cada archivo, consulta [`AGENTS.md`](./AGENTS.md).

## Fuente de los Textos

Todos los documentos provienen del sitio oficial de la Procuraduría General de la República ([pgrweb.go.cr](https://pgrweb.go.cr)) en su versión más reciente, convertidos a Markdown con [`markitdown`](https://github.com/microsoft/markitdown) y normalizados para eliminar caracteres especiales del español.



Los archivos en formato Markdown pueden cargarse directamente como contexto en modelos de lenguaje (LLMs) o pipelines RAG para consultas legales, resúmenes y análisis de texto normativo.

## Contribuciones

¿Encontraste un error en el texto o quieres agregar o actualizar una ley? Revisa [`CONTRIBUTING.md`](./CONTRIBUTING.md).

## Licencia

Consulta el archivo [`LICENSE`](./LICENSE) para más información.
