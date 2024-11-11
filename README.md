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
