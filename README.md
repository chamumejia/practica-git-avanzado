# Calculadora en Python — Práctica de Git Avanzado

Proyecto simple de calculadora con operaciones básicas, usado para practicar comandos avanzados de Git.

## Funcionalidades
- Sumar
- Restar
- Multiplicar
- Dividir
- Potencia
- Promedio

## Cómo ejecutar
\\\bash
python calculadora.py
\\\

## Versionado Semántico y Git
- **Major.Minor.Patch**: Major cambia por rupturas, Minor por funciones nuevas compatibles, y Patch por correcciones de errores pequeños.
- **git stash**: Guarda temporalmente los cambios actuales sin hacer commit, dejando tu directorio limpio.
- **git tag**: Crea una etiqueta permanente en un commit específico para identificar versiones clave (como v1.0).

## Investigación adicional (git reflog)
El comando \git reflog\ muestra un registro de todas las referencias (cambios en el HEAD) de tu repositorio local. Es muy útil porque guarda el historial de todos los movimientos, permitiéndote recuperar commits o ramas que parecían borrados por error.