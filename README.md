# Armador automático de 11 - Captación Racing

App web en React + Vite para cargar el Excel original del formulario de inscripción y generar equipos por categoría/año de nacimiento.

## Funciones principales

- Carga archivos `.xlsx` o `.xls` del formulario.
- Calcula la categoría a partir del año de nacimiento.
- Detecta fechas inválidas, por ejemplo fechas cargadas como 2026.
- Permite elegir formación.
- Genera la mayor cantidad posible de 11 completos sin repetir jugadores entre equipos.
- Si un jugador aparece con el mismo nombre y la misma fecha de nacimiento, lo toma como un único jugador y omite las repeticiones.
- Si dos jugadores tienen el mismo nombre pero distinta fecha de nacimiento, los mantiene como jugadores distintos y los muestra en el resumen.
- Muestra jugadores disponibles que no fueron utilizados.
- Exporta los equipos generados como imagen PNG o PDF.

## Instalación

```bash
npm install
```

## Uso

```bash
npm run dev
```

Después entrá al link que muestra Vite, normalmente:

```bash
http://localhost:5173
```

## Nota

Si descargás una versión nueva del proyecto, conviene cerrar la terminal anterior, abrir la carpeta nueva en Visual Studio Code y ejecutar nuevamente `npm install` y `npm run dev`.
