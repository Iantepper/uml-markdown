# uml-markdown
| Campo                      | Descripción                                                                                                                                                                     |
|----------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Nombre del caso de uso** | Consultar Calificaciones                                                                                                                                                        |
| **ID única**               | estudiante_uc_010                                                                                                                                                              |
| **Área**                   | Sistema de estudiantes                                                                                                                                                          |
| **Descripción**            | Permite al estudiante consultar sus calificaciones de todas las materias en las que está inscrito a través de un sitio web seguro.                                             |
| **Evento desencadenador**  | El estudiante accede al sitio web, introduce su ID y contraseña, y hace clic en "Consultar Calificaciones".                                                                    |
| **Tipo de desencadenador** | X Externo   _ Temporal                                                                                                                                                         |
| **Pasos realizados (ruta principal)**                               | **Información de los pasos**                                                                                                                                           |
| 1. El estudiante inicia sesión en el sitio web seguro               | ID de estudiante, contraseña                                                                                                                                            |
| 2. El sistema verifica la identidad del estudiante                  | Registro del estudiante, ID de estudiante, contraseña                                                                                                                  |
| 3. El sistema recupera el registro académico del estudiante         | Registro académico del estudiante                                                                                                                                      |
| 4. Las calificaciones se muestran en una página web                 | Registro académico del estudiante                                                                                                                                      |
| **Precondiciones**         | El estudiante se encuentra en la página web de consultar calificaciones                                                                                                        |
| **Postcondiciones**        | El estudiante consulta sus calificaciones de manera exitosa                                                                                                                    |
| **Suposiciones**           | El estudiante tiene un navegador y cuenta con ID de usuario y contraseña válidos                                                                                               |
| **Requerimientos cumplidos** | Permitir que los estudiantes puedan consultar sus calificaciones mediante un sitio web seguro                                                                            |
| **Cuestiones pendientes**  | ¿Se deben mostrar las calificaciones por período académico o todas juntas?                                                                                                     |
| **Prioridad**              | Alta                                                                                                                                                                           |
| **Riesgos**                | Bajo                                                                                                                                                                           |




| Campo                      | Descripción                                                                                                                                                                         |
|----------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Nombre del caso de uso** | Registrar Solicitud de Tutoría                                                                                                                                                     |
| **ID única**               | estudiante_uc_015                                                                                                                                                                 |
| **Área**                   | Sistema de tutorías                                                                                                                                                                |
| **Descripción**            | Permite al estudiante registrar una solicitud de tutoría para resolver dudas sobre una asignatura específica.                                                                     |
| **Evento desencadenador**  | El estudiante accede a la sección de tutorías, introduce sus datos y la materia, y hace clic en "Solicitar Tutoría".                                                              |
| **Tipo de desencadenador** | X Externo   _ Temporal                                                                                                                                                            |
| **Pasos realizados (ruta principal)**                                 | **Información de los pasos**                                                                                                                                            |
| 1. El estudiante inicia sesión en el sitio web seguro                 | ID de estudiante, contraseña                                                                                                                                           |
| 2. El sistema muestra la página para registrar una solicitud de tutoría | ID de estudiante, lista de asignaturas inscritas                                                                                                                       |
| 3. El estudiante selecciona la asignatura y completa el formulario    | Formulario de solicitud de tutoría                                                                                                                                     |
| 4. El sistema valida la solicitud y la almacena en el registro        | Formulario de solicitud de tutoría, registro de tutorías                                                                                                               |
| 5. Se envía una confirmación al estudiante                            | Registro de solicitud, página de confirmación                                                                                                                          |
| **Precondiciones**         | El estudiante se encuentra en la página de registro de tutoría                                                                                                                    |
| **Postcondiciones**        | La solicitud de tutoría queda registrada y el estudiante recibe confirmación                                                                                                      |
| **Suposiciones**           | El estudiante tiene un navegador y cuenta con ID de usuario y contraseña válidos                                                                                                 |
| **Requerimientos cumplidos** | Permitir que los estudiantes puedan registrar solicitudes de tutoría para asignaturas específicas                                                                          |
| **Cuestiones pendientes**  | ¿Es necesario asignar de inmediato un tutor para la solicitud, o se confirma luego?                                                                                               |
| **Prioridad**              | Alta                                                                                                                                                                              |
| **Riesgos**                | Medio                                                                                                                                                                             |
