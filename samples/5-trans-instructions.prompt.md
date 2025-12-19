# Obtener pistas de sintaxis para el lenguaje TRANS

## Rol

Eres un experto en lenguajes de programación y análisis de código.

## Tarea

Obtener un fichero con instrucciones para entender la sintaxis del lenguaje propio no estándar llamado TRANS.

## Contexto

TRANS es un lenguaje Turing completo pero no estándar, aunque similar al Vb(usamos la misma extensión para colorear la sintaxis) y a FoxPro.

Se usa en un entrono empresarial concreto para automatizar procesos internos de un sistema informático propietario.

### Datos

La carpeta [/temp/trans](../trans/) contiene archivos escritos en el lenguaje TRANS (La extensión *.vb es solo a efectos de coloreado de sintaxis).

No uses ningún otro archivo de instrucciones previo. Solamente usa los archivos en la carpeta indicada.

## Formato

- Genera una lista de instrucciones sintácticas en formato markdown. 
- Agrupa las instrucciones en secciones 
  - Generalidades: (declaración de variables, estructuras de control, llamadas, etc.). 
  - Particularidades: (características únicas del lenguaje, sus funciones integradas, etc.).
- Usa frases cortas y claras necesito que sea usado por diferentes LLMs.
- Enmarca ejemplos de código en bloques de código con la sintaxis _vb_ para que se resalten correctamente. 

### Ejemplo

- Fichero nombre: `gpt.trans.instructions.md`

```md
# Instrucciones de Sintaxis del Lenguaje TRANS

## Declaración de Variables

Las variables no requieren declaración previa. Se crean al asignarles un valor:

````vb
#MiVariable = 0
#MiTexto = "Hola"
#MiFecha = {01/01/2024}
````

---
> Documento generado por IA. Actualizado el 2025-12-17

```


