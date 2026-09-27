# Contribuir a FunshiEngine

Gracias por tu interés en contribuir a FunshiEngine.

FunshiEngine es un proyecto de código abierto y las contribuciones de la comunidad son bienvenidas.

Antes de realizar cambios importantes, se recomienda comprender la arquitectura actual del proyecto y revisar la documentación disponible.

## Antes de comenzar

Antes de crear una issue o pull request:

1. Comprueba si el problema ya fue reportado.
2. Revisa la documentación existente.
3. Comprende el funcionamiento de la parte del proyecto que deseas modificar.
4. Evita realizar cambios no relacionados con el objetivo de tu contribución.

## Issues

Utiliza las issues para:

- Reportar errores reproducibles.
- Proponer nuevas funcionalidades.
- Comunicar problemas técnicos.
- Solicitar mejoras relacionadas con el proyecto.

Antes de abrir una issue, busca si existe una issue similar.

### Reportes de errores

Los reportes de errores deben incluir, cuando sea posible:

- Sistema operativo.
- Compilador utilizado.
- Versión de CMake.
- Configuración de compilación.
- Pasos necesarios para reproducir el problema.
- Mensajes de error.
- Logs relevantes.
- Información adicional que pueda ayudar a reproducirlo.

## Solicitudes de funcionalidades

Las nuevas funcionalidades deben explicar:

- Qué problema intentan solucionar.
- Qué comportamiento se espera.
- Por qué la funcionalidad puede ser útil.
- Ejemplos de uso cuando sea posible.

Las propuestas que impliquen cambios importantes en la arquitectura deberían discutirse antes de comenzar una implementación completa.

## Pull Requests

Una pull request debe:

- Tener un objetivo claro.
- Mantenerse enfocada en un cambio concreto.
- Evitar modificaciones no relacionadas.
- Respetar la arquitectura existente.
- Mantener o mejorar la calidad del código.
- Incluir pruebas cuando sea apropiado.
- Actualizar la documentación cuando sea necesario.

Las pull requests pueden solicitar cambios antes de ser aceptadas.

## Estilo de código

Respeta las convenciones existentes del proyecto.

Evita introducir cambios masivos de formato o estilo que no estén relacionados con el objetivo de la contribución.

Las modificaciones deben priorizar:

- Claridad.
- Mantenibilidad.
- Compatibilidad.
- Simplicidad.
- Coherencia con la arquitectura existente.

## Arquitectura

FunshiEngine posee diferentes sistemas y subsistemas que deben mantenerse separados cuando corresponda.

Antes de modificar una abstracción existente, analiza cómo afecta a:

- Escenas.
- Objetos.
- Componentes.
- Física.
- Renderizado.
- Scripting.
- Editor.
- Sistemas de construcción.
- Tests.

No se recomienda introducir dependencias o acoplamientos innecesarios.

## Pruebas

Las modificaciones deben probarse localmente siempre que sea posible.

Cuando una modificación pueda afectar funcionalidades existentes:

- Ejecuta las pruebas correspondientes.
- Comprueba que la compilación continúe funcionando.
- Evita desactivar pruebas para hacer que una contribución pase.
- Añade nuevas pruebas cuando resulte apropiado.

## Cambios incompatibles

Los cambios que puedan modificar una API pública, comportamiento existente, formato de datos o arquitectura deben documentarse claramente.

## Revisión

Todas las pull requests están sujetas a revisión.

Los mantenedores pueden solicitar modificaciones, rechazar cambios o pedir una implementación diferente cuando sea necesario para mantener la calidad, estabilidad o arquitectura del proyecto.

## Gracias

Toda contribución, desde una corrección pequeña hasta una funcionalidad importante, ayuda al desarrollo de FunshiEngine.
