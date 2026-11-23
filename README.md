# El alquiler de carpas de la Cooperativa de Carperos de Santa Marta

Trabajo de fin de curso de **Fundamentos de Programación**, Universidad del Magdalena, Alternativa D.

**Integrantes del equipo:** Deivis Iguarán · Juan Osorio · Sebastián Estrada

Programa de consola en Python que lleva el registro diario de carpas alquiladas en las playas de la cooperativa y calcula sus indicadores: alquileres totales, promedio, porcentaje de alquiler, desviación estándar, días de más y de menos carpas, días en cada nivel de alquiler, racha más larga en nivel agotado y días sin registrar. Carga los datos desde dos archivos CSV o desde el teclado, y simula días para practicar.

**Video explicativo:** _(https://www.youtube.com/watch?v=icAiSzj0iy4)_

## Cómo ejecutarlo

Se necesita Python 3.10 o posterior. Desde esta carpeta:

```
python user_interface.py
```

Para probar con los datos del enunciado, elegir la opción 6 y escribir `datos/playas_ejemplo.csv` y después `datos/alquileres_ejemplo.csv`.

## Cómo verificarlo

```
python verificacion/verificar.py
```

Ejecuta los 105 casos de verificación sobre `user_interface.py` y compara la pantalla de cada uno con su salida esperada. `python verificacion/verificar.py R04-01 -v` verifica un solo caso y muestra su pantalla.

## Contenido

| Carpeta o archivo | Qué contiene |
| --- | --- |
| `business_logic.py` | La lógica del negocio: las clases `Playa` y `Cooperativa`, las funciones de apoyo y las constantes. |
| `user_interface.py` | La interfaz de consola: el menú y la lectura y presentación de los datos. |
| `datos/` | Los 20 archivos CSV que usan los casos de verificación. |
| `verificacion/` | Las entradas y las salidas esperadas de los 105 casos, el verificador y `CASOS_DE_VERIFICACION.pdf`. |
| `documentos/DOCUMENTO_DE_ANALISIS.pdf` | La especificación final de cada requisito (producto 1). |
| `documentos/INFORME_INTEGRAL.pdf` | Los siete incrementos con su análisis, diseño, codificación y verificación (producto 2). |
| `documentos/INFORME_USO_IA.pdf` | El uso de la inteligencia artificial generativa, con sus evidencias (producto 5). |
