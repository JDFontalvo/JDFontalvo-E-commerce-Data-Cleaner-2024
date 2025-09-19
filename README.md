# Biblioteca Modular para Procesamiento de Datos en E-commerce

## modularización del codigo:

```
my_data_cleaner/
├── __init__.py
├── cleaning.py  # Funciones para limpiar y normalizar datos
├── deduplication.py  # Eliminación de duplicados
├── saving.py  # Guardado en CSV, JSON, o bases de datos
├── utils.py  # Funciones auxiliares
├── tests/  # Pruebas unitarias
├── setup.py  # Configuración para instalar como paquete
```

## Descripción:
my_data_cleaner es una biblioteca de Python diseñada para la limpieza, normalización y preprocesamiento de datos estructurados en entornos de e-commerce. Ofrece funciones modulares para la eliminación de duplicados, estandarización de formatos, imputación de valores nulos y exportación en múltiples formatos (CSV, JSON, SQL). Su diseño flexible permite integrarse en pipelines de procesamiento de datos, automatizando tareas críticas y reduciendo la intervención manual.

## Características clave:
- ✔️ Limpieza y normalización de datos con métodos configurables.
- ✔️ Eliminación de duplicados y manejo de valores faltantes.
- ✔️ Compatibilidad con múltiples formatos de entrada y salida.
- ✔️ Integración sencilla con Pandas y bases de datos SQL.
