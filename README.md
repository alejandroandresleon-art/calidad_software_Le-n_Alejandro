# Calidad de Software
# Autor: Alejandro Leon

Este repositorio tiene como finalidad documentar y practicar conceptos básicos de calidad de software, con énfasis en la importancia de la validación y la mejora continua de los sistemas.

## ¿Qué es la calidad de software?

La calidad de software se refiere al grado en que un sistema cumple con los requisitos esperados, es confiable, mantenible, fácil de usar y adecuado para su propósito.

Entre los principales aspectos de calidad se encuentran:

- Funcionalidad: que el sistema haga lo que debe hacer.
- Confiabilidad: que el software funcione de forma estable.
- Mantenibilidad: que pueda modificarse y mejorar con facilidad.
- Usabilidad: que sea comprensible y sencillo de usar.
- Eficiencia: que use recursos de forma adecuada.
- Seguridad: que proteja la información y evite fallos críticos.

## Importancia de la calidad

Un software de calidad reduce errores, mejora la experiencia del usuario, facilita el mantenimiento y disminuye costos asociados a correcciones tardías. Además, ayuda a entregar productos más confiables y escalables.

## Pruebas unitarias

Las pruebas unitarias verifican componentes o funciones individuales del código de forma aislada.

### Objetivo

- Validar que cada unidad cumple con su comportamiento esperado.
- Detectar errores en lógica y validaciones tempranamente.
- Facilitar la refactorización sin romper funcionalidades existentes.

### Características

- Son rápidas de ejecutar.
- Se enfocan en una sola parte del sistema.
- Generalmente se automatizan con frameworks de prueba.

Ejemplo de enfoque:

- Probar una función de suma.
- Verificar que devuelve el resultado correcto para distintos casos.
- Comprobar validaciones y errores esperados.

## Pruebas end-to-end (E2E)

Las pruebas E2E validan el comportamiento del sistema completo desde la perspectiva del usuario. Simulan escenarios reales, como iniciar sesión, completar un formulario o realizar una compra.

### Objetivo

- Verificar que los flujos principales funcionan correctamente.
- Comprobar la integración entre diferentes módulos.
- Detectar fallos que pueden aparecer solo en la aplicación completa.

### Características

- Son más lentas que las pruebas unitarias.
- Cubren escenarios más reales y completos.
- Ayudan a garantizar que el producto final funciona para el usuario.

## Relación entre pruebas unitarias y E2E

Las pruebas unitarias y las pruebas E2E no son sustitutas entre sí; son complementarias.

- Las pruebas unitarias detectan fallos a nivel de lógica y componentes.
- Las pruebas E2E validan el flujo real del sistema.

En general, una estrategia de calidad recomienda combinar ambas para lograr una cobertura más sólida y una mayor confianza en el producto.

## Conclusión

La calidad de software no depende solo de escribir código funcional, sino también de asegurar que ese código sea confiable, verificable y sostenible en el tiempo. Las pruebas unitarias y E2E son herramientas fundamentales para lograr este objetivo.

---

## Repositorio

Este repositorio sirve como espacio para estudiar y aplicar conceptos relacionados con la calidad de software, con foco en pruebas y validación de sistemas.
