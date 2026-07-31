# 7. Diseño e implementación de base de datos

## Etapas

### Modelo conceptual

Representa entidades, atributos y relaciones sin depender de un gestor específico.

### Modelo lógico

Define tablas, claves primarias, claves foráneas, cardinalidades y restricciones.

### Modelo físico

Implementa el diseño en MySQL u otro gestor aprobado.

## Entregables

- Diagrama conceptual.
- Modelo lógico.
- Modelo físico.
- Script de creación.
- Script de datos de demostración.
- Diccionario de datos cuando sea necesario.

## Revisión mínima

- Cada tabla tiene clave primaria.
- Las relaciones necesarias usan claves foráneas.
- Los tipos de datos son adecuados.
- Los campos obligatorios están definidos.
- Se evita duplicación innecesaria.
- Existen datos de prueba.
- El script puede ejecutarse desde una base vacía.

## Seguridad

- No guardar contraseñas reales.
- Evitar usar la cuenta administrativa para todo.
- No publicar credenciales.
- Utilizar datos ficticios.

## Demostración

El equipo debe poder explicar:

- Por qué existe cada tabla.
- Cómo se relacionan.
- Qué datos se almacenan.
- Qué restricciones evitan errores.
- Cómo se restaura la base de datos.
