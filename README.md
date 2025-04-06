# appAsistencia

|![](/images/profesorAsistencia.png)||
|-|-|
||Lo que necesitamos es una herramienta que nos facilite el control de asistencia de nuestros cursos. Cada día pierdo demasiado tiempo pasando lista y luego calculando manualmente quién está en riesgo de reprobar por inasistencias.
||Necesito poder tener mi lista de estudiantes bien organizada, con sus nombres completos y algún identificador único para cada uno. Cuando estoy en clase, quiero marcar rápidamente quién asistió y quién no, sin complicaciones.
||Es importante que cada sesión tenga su fecha y que pueda indicar qué tema vimos ese día, especialmente para distinguir clases normales de exámenes o actividades especiales.
||Lo que más me ayudaría es poder ver de un vistazo los porcentajes de asistencia: quiero saber qué estudiantes están faltando demasiado, cuáles son las sesiones con mayor ausentismo y cuál es la tendencia general del grupo.
||No necesito nada complicado, debe ser sencillo de usar y entender a simple vista. Uso mucho los colores para identificar rápidamente situaciones (rojo para ausencias, verde para presencias). Y como llevo varios grupos, debe funcionar bien aunque tenga listas grandes.
||Mis estudiantes siempre me preguntan sobre su asistencia, así que sería útil que ellos pudieran consultar esta información, pero sin poder modificarla, claro está. Solo yo debo poder actualizar los datos.
||Y lo más importante: necesito que esto me sirva durante todo el semestre y que pueda adaptarse a mis diferentes cursos, algunos tienen dos sesiones por semana, otros solo una, y las fechas pueden variar si hay suspensiones o recuperaciones de clase.
||![](/images/profesorAsistenciaConApp.png)|

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
