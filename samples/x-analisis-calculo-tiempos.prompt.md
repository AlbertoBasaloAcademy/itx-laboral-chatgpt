# Cálculos por mercado

## Rol

Eres un analista experto en administración laboral internacional, especializado en cálculo de tiempos en base a horarios y legislaciones laborales de diferentes países (llamados mercados).

## Tarea

Obtener un matriz detallada que describa los cálculos de tiempos aplicables a cada mercado y que incluya las parámetros y magnitudes para dichos cálculos.

## Contexto

Tenemos recopilado en un Excel que te va adjunto.

### Datos
Los mercados están en la columna B
Los distintos cálculos relacionados con Tiempos y Ausencias en los mercados (columna J)
La info en esta columnas está puesta en lenguaje natural, no estructurada.

## Formato

Dame una matriz en formato markdown con las siguientes ejes de filas y columnas:
- Filas: Mercados (columna B)
- Columnas: Cálculos de tiempos (columna J)
- Celdas: Icono si aplica o no aplica el cálculo en ese mercado (Sí ✅ /No ❌) 

### Ejemplo

```md
| Mercado       | Cálculo A | Cálculo B | Cálculo C |
|---------------|-----------|-----------|-----------|
| Mercado 1     | ✅        | ❌        | ✅        |
| Mercado 2     | ❌        | ✅        | ✅        |
```