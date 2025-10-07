# 📘 Application Messages and Status Codes

Este documento describe los mensajes de **error** (`ERR`), **informativos** (`INF`) y los **códigos de estado personalizados** (`ApplicationStatusCodes`) utilizados por el sistema. Estos mensajes son retornados por los endpoints de la API para facilitar la interpretación de los resultados.

---

## ✅ Application Status Codes

| Code                            | Description                                                                 |
|---------------------------------|-----------------------------------------------------------------------------|
| `SUCCESS`                       | Operación completada exitosamente.                                          |
| `CREATED`                       | Recurso creado correctamente.                                              |
| `DELETED`                       | Recurso eliminado correctamente.                                           |
| `REQUEST_DELETED`              | Solicitud de eliminación procesada exitosamente.                          |
| `BAD_REQUEST`                  | La solicitud contiene parámetros faltantes o inválidos.                    |
| `NOT_FOUND`                    | El recurso solicitado no fue encontrado.                                   |
| `INVALID_CREDENTIALS`         | Las credenciales proporcionadas son inválidas.                             |
| `INVALID_TOKEN`               | El token proporcionado es inválido.                                        |
| `UNAUTHORIZED`                | El usuario no está autenticado.                                            |
| `UNAUTHORIZED_OR_DISABLED_USER` | El usuario está inactivo o no tiene autorización.                         |
| `RESET_PASSWORD`              | El usuario debe actualizar su contraseña o es su primer ingreso.           |
| `INTERNAL_SERVER_ERROR`       | Error interno del servidor.                                                |
| `INTERNAL_REPOSITORY_ERROR`   | Error interno en la capa de repositorio.                                   |

---

## ❗ Error Codes (`ERRxxx`)

| Code   | Description |
|--------|-------------|
| `ERR001` | Parámetro requerido nulo o vacío. |
| `ERR002` | Error al ejecutar un procedimiento almacenado. |
| `ERR003` | Error general al ejecutar un servicio o una operación. |
| `ERR004` | Las credenciales del usuario son incorrectas. |
| `ERR005` | Identificador proporcionado no válido. |
| `ERR006` | La solicitud o sus parámetros están vacíos. |
| `ERR007` | No se pudo obtener información del usuario autenticado. |
| `ERR008` | Los parámetros enviados no coinciden con el usuario autenticado. |
| `ERR009` | Ya existe un registro con los mismos parámetros. |
| `ERR010` | Token no válido. |
| `ERR011` | El cuerpo o los parámetros están vacíos. |
| `ERR012` | Token inválido o ya utilizado anteriormente. |
| `ERR013` | El aprobador no está autorizado o no es el correcto. |
| `ERR014` | No se pudo crear la notificación para el modelo. |
| `ERR015` | Error en la creación masiva de registros o creación parcial. |
| `ERR016` | No se encontraron registros para la entidad especificada. |
| `ERR017` | No se encontró la entidad por el ID especificado. |
| `ERR018` | No se encontró la entidad con la clave proporcionada. |
| `ERR019` | Error al crear una entidad. |
| `ERR020` | Error al actualizar una entidad. |
| `ERR021` | Error al eliminar una entidad. |

---

## ℹ️ Info Codes (`INFxxx`)

| Code   | Description |
|--------|-------------|
| `INF001` | Ejecución de procedimiento almacenado iniciada. |
| `INF002` | Inicio de sesión exitoso del usuario. |
| `INF003` | Validación de token exitosa. |
| `INF004` | Solicitud eliminada debido a rechazo. |
| `INF005` | Notificación creada exitosamente para el modelo. |
| `INF006` | Registros masivos creados exitosamente. |
| `INF007` | Aprobación masiva completada con éxito. |
| `INF008` | Correo electrónico enviado exitosamente. |
| `INF009` | Registros encontrados exitosamente. |
| `INF010` | Entidad creada exitosamente. |
| `INF011` | Entidad actualizada exitosamente. |
| `INF012` | Entidad eliminada exitosamente. |
| `INF013` | Entidad recuperada exitosamente. |

---

