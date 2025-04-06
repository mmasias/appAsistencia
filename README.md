# appAsistencia

## Requisitos funcionales

### Gestión de alumnos

- Registrar información básica de los estudiantes (nombres, apellidos)
- Asignar identificadores únicos a cada estudiante
- Permitir visualizar la lista completa de alumnos

### Registro de asistencia

- Marcar asistencia por alumno en cada sesión (presente/ausente)
- Registrar fechas específicas de las sesiones
- Vincular cada sesión con un tema o contenido específico

### Cálculo automático de estadísticas

- Calcular porcentaje de asistencia individual por alumno
- Calcular porcentaje de asistencia general del grupo
- Calcular porcentaje de asistencia por sesión

### Organización de sesiones

- Numerar o identificar cada sesión secuencialmente
- Registrar la fecha de cada sesión
- Asociar cada sesión con un tema o contenido específico
- Identificar sesiones especiales (exámenes, charlas, etc.)

### Visualización de datos

- Mostrar vista de resumen general (porcentajes globales)
- Permitir ver el historial completo de asistencias
- Usar formato condicional para destacar visualmente información relevante

### Gestión de accesos y permisos

- Permitir acceso de solo lectura a los estudiantes para consultar su propia asistencia
- Diferenciar perfiles de acceso (administrador/profesor con permisos totales, estudiantes con acceso limitado)
- Implementar mecanismos de autenticación básicos para identificar el tipo de usuario
- Mostrar vistas personalizadas según el tipo de usuario (vista completa para docentes, vista individual para estudiantes)

## Requisitos no funcionales

|Usabilidad|Rendimiento|Almacenamiento|Flexibilidad|Seguridad|
|-|-|-|-|-|
|Interfaz simple|Actualización automática de cálculos al registrar nuevas asistencias|Persistencia de datos a lo largo del periodo académico|Adaptación a diferentes formatos de curso (frecuencia de sesiones variable)|Control de acceso por perfil de usuario|
|Visualización clara mediante colores para facilitar la interpretación|Capacidad para manejar grupos grandes de estudiantes|Capacidad para registrar múltiples sesiones durante un semestre/curso|Posibilidad de marcar diferentes tipos de sesiones|Protección de datos modificables|
|Acceso rápido a la información||||Registro de cambios realizados|
