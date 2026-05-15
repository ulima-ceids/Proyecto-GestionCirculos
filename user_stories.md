# Historias de Usuario (Formato Connextra)

## HU-01 · Inicio de sesión

**Como** miembro registrado del sistema  
**Quiero** iniciar sesión con mis credenciales  
**Para** acceder a las funcionalidades de los círculos a los que pertenezco y mantener mi sesión activa.

### Criterios de aceptación
- El usuario puede ingresar correo/usuario y contraseña.
- El sistema valida las credenciales ingresadas.
- Si las credenciales son válidas, el sistema inicia sesión y redirige al panel principal.
- La sesión permanece activa hasta que el usuario cierre sesión o expire por inactividad.
- Si las credenciales son inválidas, el sistema muestra un mensaje de error.

---

## HU-02 · Registro en un círculo

**Como** usuario autenticado  
**Quiero** registrarme en un círculo disponible  
**Para** participar en sus actividades y acceder a sus recursos.

### Criterios de aceptación
- El sistema muestra la lista de círculos disponibles.
- El usuario puede seleccionar un círculo y solicitar su inscripción.
- El sistema valida si el usuario cumple los requisitos de inscripción.
- El sistema confirma el registro exitoso.
- El círculo aparece en la lista de membresías activas del usuario.

---

## HU-03 · Sugerencias de inscripción

**Como** usuario autenticado  
**Quiero** recibir sugerencias de círculos según mis intereses  
**Para** encontrar comunidades afines a mis preferencias.

### Criterios de aceptación
- El sistema analiza los intereses registrados del usuario.
- El sistema muestra una lista de círculos sugeridos.
- Las sugerencias incluyen información descriptiva de cada círculo.
- El usuario puede acceder directamente al proceso de inscripción desde la sugerencia.

---

## HU-04 · Registro de actividades

**Como** administrador o coordinador de círculo  
**Quiero** registrar actividades  
**Para** difundirlas entre los miembros.

### Criterios de aceptación
- El sistema permite ingresar título, descripción, lugar, fecha y hora.
- El sistema valida campos obligatorios.
- La actividad registrada queda visible para los miembros.
- El sistema notifica a los miembros sobre la nueva actividad.

---

## HU-05 · Visualización del calendario de actividades

**Como** miembro del círculo  
**Quiero** visualizar un calendario de actividades programadas  
**Para** organizar mi participación.

### Criterios de aceptación
- El calendario muestra actividades ordenadas por fecha.
- Cada actividad muestra información resumida.
- El usuario puede consultar el detalle de cada actividad.
- El calendario se actualiza automáticamente al registrar cambios.

---

## HU-06 · Visualización del calendario de reuniones

**Como** miembro del círculo  
**Quiero** visualizar el calendario de reuniones  
**Para** conocer las fechas y horarios de encuentro.

### Criterios de aceptación
- El sistema muestra reuniones programadas.
- Cada reunión incluye fecha, hora y modalidad.
- Los cambios de horario se reflejan inmediatamente.
- El usuario puede consultar detalles adicionales.

---

## HU-07 · Registro de asistencia

**Como** coordinador de sesión  
**Quiero** registrar la asistencia de participantes  
**Para** llevar control de participación.

### Criterios de aceptación
- El sistema muestra la lista de participantes inscritos.
- El coordinador puede marcar asistencia o ausencia.
- La asistencia queda almacenada en el historial.
- El sistema confirma el registro exitoso.

---

## HU-08 · Retroalimentación de sesiones

**Como** participante  
**Quiero** registrar feedback sobre una sesión  
**Para** contribuir a la mejora continua.

### Criterios de aceptación
- El usuario puede registrar comentarios y calificación.
- El feedback se asocia a la sesión correspondiente.
- El sistema valida que el usuario haya asistido.
- El coordinador puede consultar el feedback recibido.

---

## HU-09 · Carga de materiales

**Como** coordinador de actividad  
**Quiero** subir materiales relacionados  
**Para** compartir recursos con los miembros.

### Criterios de aceptación
- El sistema permite cargar archivos compatibles.
- El archivo se asocia a una actividad específica.
- El sistema valida tamaño y formato.
- El material queda disponible en el repositorio.

---

## HU-10 · Consulta del repositorio de materiales

**Como** miembro del círculo  
**Quiero** acceder al repositorio de materiales  
**Para** consultar recursos compartidos.

### Criterios de aceptación
- El sistema muestra todos los materiales disponibles.
- Los materiales pueden filtrarse por actividad o fecha.
- El usuario puede descargar o visualizar materiales.
- Solo miembros autorizados pueden acceder.

---

## HU-11 · Publicación en foro

**Como** miembro del círculo  
**Quiero** publicar entradas en el foro  
**Para** compartir ideas y discutir temas relevantes.

### Criterios de aceptación
- El sistema permite crear nuevas publicaciones.
- Las entradas muestran autor y fecha.
- Otros miembros pueden visualizar las publicaciones.
- El sistema valida contenido no vacío.

---

## HU-12 · Publicación de anuncios

**Como** coordinador del círculo  
**Quiero** publicar anuncios  
**Para** informar novedades importantes a los miembros.

### Criterios de aceptación
- El sistema permite crear anuncios con título y contenido.
- Los anuncios aparecen en una lista ordenada.
- Los miembros reciben notificación.
- Los anuncios publicados pueden consultarse posteriormente.

---

## HU-13 · Mensajería dirigida

**Como** coordinador del círculo  
**Quiero** enviar mensajes a miembros específicos  
**Para** comunicar información personalizada.

### Criterios de aceptación
- El sistema permite seleccionar destinatarios.
- El mensaje se entrega únicamente a los seleccionados.
- El destinatario recibe notificación.
- El sistema registra el historial de mensajes enviados.

---

## HU-14 · Consulta de perfiles de miembros

**Como** miembro del círculo  
**Quiero** consultar perfiles de otros miembros  
**Para** conocer su información relevante.

### Criterios de aceptación
- El sistema muestra información básica del perfil.
- Solo miembros del mismo círculo pueden visualizar perfiles.
- La información se muestra actualizada.
- Se respeta la configuración de privacidad.

---

## HU-15 · Consulta de información de círculos

**Como** usuario  
**Quiero** visualizar información general de los círculos  
**Para** evaluar mi interés en participar.

### Criterios de aceptación
- El sistema muestra descripción, objetivos y requisitos.
- La información está disponible antes de registrarse.
- El usuario puede explorar múltiples círculos.
- Los datos se mantienen actualizados.

---

## HU-16 · Notificación de desvinculación

**Como** miembro de un círculo  
**Quiero** recibir una notificación cuando sea desvinculado  
**Para** estar informado sobre cambios en mi membresía.

### Criterios de aceptación
- El sistema genera una notificación automática en base a no asistencia.
- La notificación indica el círculo afectado.
- El usuario puede consultar el motivo si está registrado.
- La desvinculación actualiza el estado de membresía.

---

## HU-17 · Registro de convocatorias

**Como** coordinador de círculo  
**Quiero** registrar convocatorias  
**Para** invitar nuevos miembros.

### Criterios de aceptación
- El sistema permite registrar título, descripción y vigencia.
- Las convocatorias quedan visibles públicamente.
- El sistema valida fechas de apertura y cierre.
- Las convocatorias expiran automáticamente al finalizar su vigencia.