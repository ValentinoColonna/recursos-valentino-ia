# SKILL · Pasá tu GPT a una skill antes del 11/12 · Valentino IA

OpenAI retira los GPT personalizados el 11 de diciembre de 2026. Lo dice el FAQ oficial, leído en noviembre de 2026: tus conversaciones quedan, el GPT no.

## Cómo pasarlo

1. **Abrí tu GPT en ChatGPT** (Mis GPT › Editar) y copiá el nombre, la descripción, las instrucciones, los «conversation starters» y los nombres de los archivos de conocimiento.
2. **Pegá el pedido de abajo en Claude** (o en la IA que uses), completando cada [pegar].
3. **Claude te devuelve el SKILL.md** y la carpeta. Cargala en claude.ai › Customize › Skills, subiendo la carpeta como ZIP.
4. **Probá los dos con la misma tarea** antes de soltar el viejo.

```
Vas a convertir la configuración de un GPT personalizado en una skill portable que siga la especificación abierta Agent Skills (https://agentskills.io/specification).

Te paso:
- Nombre del GPT: [pegar]
- Descripción: [pegar]
- Instrucciones completas: [pegar]
- Conversation starters: [pegar]
- Archivos de conocimiento (solo los nombres): [pegar]
- Capacidades y acciones que usaba: [pegar]

Devolveme:
1. Un archivo SKILL.md completo, listo para copiar:
   - arriba, un frontmatter YAML con `name` y `description`;
   - `name`: de 1 a 64 caracteres, solo letras minúsculas (a-z), números (0-9) y guiones, sin guiones al inicio, al final ni dobles; tiene que coincidir con el nombre de la carpeta de la skill;
   - `description`: hasta 1024 caracteres; dice qué hace la skill y cuándo usarla (y cuándo no);
   - después del frontmatter, las instrucciones en Markdown, ordenadas en secciones claras (objetivo, pasos, formato de salida, qué no hacer), sin perder ninguna regla del GPT original;
   - si el GPT usaba archivos de conocimiento, indicá en las instrucciones cuándo consultar cada uno dentro de la carpeta references/.
2. La estructura de carpetas: una carpeta con el mismo nombre que el `name`, con el SKILL.md y references/ con los archivos.
3. La lista de lo que NO se pudo trasladar (acciones, integraciones, modelo elegido) y qué haría falta para reconstruirlo (una app conectada o un servidor MCP).
4. Una tarea de prueba para comparar la respuesta del GPT original con la de la skill.

No inventes reglas, datos ni ejemplos que no estén en lo que te pasé. Si algo es ambiguo, preguntame antes de escribir el SKILL.md.
```

**Lo que no se pasa:** las acciones y las integraciones del GPT. El pedido te las lista para que sepas qué falta.

*Valentino IA*
