
# Prompt Engineering

## Patrones y estructuras

### 📊 Resumen rápido de patrones

| Patrón                       | Para qué va bien                                                      |
|------------------------------|-----------------------------------------------------------------------| 
| **Role-Task-Format (RTF)**   | Posts, emails y descripciones claras y profesionales.                 |
| **Chain-of-Thought (CoT)**   | Problemas que requieren razonamiento paso a paso.                     |
| **CARE**                     | Mensajes consistentes en marketing, educación o comunicación interna. |
| **Sequential Instructions**  | Tareas largas que conviene dividir en pasos numerados.                |
| **Persona-Based Prompting**  | Adaptar el tono a un rol específico (profesor, influencer, experto).  |
| **Problem-Solution**         | Pedir soluciones accionables a un problema concreto.                  |
| **Comparison and Pros-Cons** | Comparar opciones y decidir entre herramientas o productos.           |

> **Recuerda:** Elige el patrón según el tipo de tarea y el nivel de control que necesitas sobre la respuesta.

---

## 1. Role-Task-Format (RTF)

- **Idea clave:** Define el **rol**, la **tarea** y el **formato** de salida.
- **Úsalo para:** Contenido enfocado y profesional (posts, emails, descripciones).

**Ejercicio:** Pide a la IA que actúe como community manager.

**Prompt inicial:** "Escribe un post sobre un nuevo café orgánico."

**Prompt mejorado:** 

```md
Actúa como community manager. Tu tarea es redactar un post para Instagram sobre un nuevo café orgánico. El formato debe ser un texto breve y atractivo con hashtags.
```

> **Tip:** Si la respuesta no tiene el tono adecuado, ajusta solo el **rol** y mantén tarea y formato.

## 2. Chain-of-Thought (CoT)

- **Idea clave:** Pide que la IA **piense paso a paso** para hacer explícito el razonamiento.
- **Úsalo para:** Resolución de problemas, análisis, guías y tutoriales.

**Ejercicio:** Resolver un problema paso a paso.

**Prompt inicial:** "Explica cómo organizar un evento."

**Prompt mejorado:** 
```md
Explica cómo organizar un evento de empresa. Vamos a pensarlo paso a paso.
```

> **Tip:** Añade frases como *"piensa en voz alta"* o *"razona paso a paso antes de responder"* para más detalle.

## 3. Context-Ask-Rules-Examples (CARE)
- **Idea clave:** Estructura el prompt en **Context**, **Ask**, **Rules** y **Examples**.
- **Úsalo para:** Mantener consistencia en marketing, educación y comunicación corporativa.

**Ejercicio:** Crear un email de marketing.

**Prompt mejorado:** 
```md
- Context: Empresa SaaS que lanza nueva función.
- Ask: Redactar un email promocional.
- Rules: 150 palabras, tono cercano, incluir CTA.
- Examples: Mostrar un email anterior exitoso.
``` 

> **Tip:** Cuando algo “no suena a la marca”, revisa primero **Context** y **Rules** antes de cambiar el resto.

## 4. Sequential Instructions
- **Idea clave:** Descomponer la tarea en **pasos numerados** y asignarles extensión o foco.
- **Úsalo para:** Artículos largos, campañas de email, guías detalladas.

**Ejercicio:** Redactar un artículo en pasos.

**Prompt mejorado:** 
```md 
Escribe un artículo de 600 palabras sobre productividad remota. 
- Paso 1: Introducción (100 palabras). 
- Paso 2: Tres consejos prácticos (400 palabras). 
- Paso 3: Conclusión (100 palabras).
```


> **Tip:** Añade siempre límites de palabras por paso para evitar que un apartado se coma al resto.

## 5. Persona-Based Prompting
- **Idea clave:** Fijar una **persona** clara (rol, tono, nivel técnico).
- **Úsalo para:** Ajustar el discurso a diferentes públicos.

**Ejercicio:** Cambiar el tono según el rol.

**Prompt mejorado:** 
```md 
Explica qué es blockchain como si fueras un profesor universitario.
```

Variación: "...como si fueras un influencer de TikTok."

> **Tip:** Si el tono sigue sin encajar, especifica también **audiencia objetivo** y **canal** (email, TikTok, LinkedIn, etc.).

## 6. Problem-Solution
- **Idea clave:** Enmarcar un **problema concreto** y pedir soluciones prácticas.
- **Úsalo para:** Estrategia, educación, soporte o ideas de mejora continua.

**Ejercicio:** Identificar y resolver un reto.

**Prompt mejorado:** 
```md 
Los estudiantes se distraen en clases online. Da tres soluciones prácticas.
```

> **Tip:** Añade criterios como *"que sean baratas de implementar"* o *"ordenadas de más a menos impacto"*.

## 7. Comparison and Pros-Cons
- **Idea clave:** Pedir una **comparación estructurada** y pros/contras claros.
- **Úsalo para:** Evaluar herramientas, productos o enfoques.

**Ejercicio:** Comparar herramientas.

**Prompt mejorado:** 
```md 
Compara Trello y Asana para gestión de proyectos. Haz una tabla con pros y contras.
```

> **Tip:** Pide siempre una **recomendación final** basada en un contexto (equipo pequeño, enterprise, no técnico, etc.).
