# Taller Integrador Individual — Buenas Prácticas de Desarrollo de Software
**Autor:** Santiago Guerra Pérez

## Sitio publicado
https://santiagoguerraperez.github.io/taller-integrador-Guerra/

| Defecto encontrado | Por qué era un problema | Cómo lo corrigió |
|---|---|---|
| Archivos con espacios y extensión en mayúscula | Obliga a codificar la ruta en el href; mala práctica | Se renombraron a index.html y estilos.css |
| Variable `x` | No indica qué almacena | Se renombró a `totalNotas` |
| Variable `TempValue2` | PascalCase inconsistente, nombre poco claro | Se renombró a `promedio` |
| Variables `a`, `b`, `c` | No describen que son las tres notas | Se renombraron a `nota1`, `nota2`, `nota3` |
| `data1` sin uso | Código muerto que confunde | Se eliminó |
| Función `calc()` | Nombre abreviado, poco descriptivo | Se renombró a `calcularPromedio()` |
| IDs `n1,n2,n3,r,r2` sin `label for` | Poco descriptivos y sin accesibilidad | Se renombraron y se asociaron con `for`/`id` |
| `<title>pagina</title>` | Genérico, no describe la página | Se cambió a "Calculadora de Promedio" |
| Código comentado y `console.log` de depuración | Código muerto/basura en el archivo final | Se eliminaron |


## Calculadora de Promedio


Página web simple que calcula el promedio de tres notas y muestra si el resultado es aprobado o reprobado.

## Cómo usarla
Abre `index.html` en el navegador, ingresa las tres notas y presiona "Calcular".

## Archivos
- `index.html`: estructura y lógica de la calculadora.
- `estilos.css`: estilos de la página.