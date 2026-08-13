# inventario de tamizaje (equipo)

> Mantener en actualizacion. Toda fila sin responsable o sin URL válida se considera **incompleta**.

## Tabla resumen

| Servicio (ID)  | Descripción breve                       | Repo URL                               | Base URL (EC2)             | Swagger UI                            | Responsable               | Estado      |
| -------------- | --------------------------------------- | -------------------------------------- | -------------------------- | ------------------------------------- | ------------------------- | ----------- |
| Violentometro |  tamizaje de la violencia | https:// | http://<ip-o-dominio>:8083 | http://<ip-o-dominio>:8083/swagger-ui | Sara Malaver (saramalaver01-cpu) | En proceso   |
| Tipo de relaciones    | tamizaje de las relaciones              | https://  | http://<ip-o-dominio>:8082 | http://<ip-o-dominio>:8082/swagger-ui | Jaime Jurado (esteban-42) | En proceso |
| Bienestar emocional  |  tamizaje de las emociones | https://github.com/yuliethtrujillo01/oauth2-springboot.git | http://<ip-o-dominio>:8083 | http://<ip-o-dominio>:8083/swagger-ui | Yulieth Trujillo (yuliethtrujillo01) | En proceso  |



> **Ejemplo de llenado real:**  
> - “Base URL (EC2)”: usar IP pública o dominio del servidor.  
> - “Estado”: Pendiente / En progreso / Listo.

---

## Detalle por servicio (plantilla)

  ### (Tipo de relaciones)-Tamizaje
- **Responsable:** Jaime Jurado (Esteban-42) 
- **Repositorio:** https://
- **Base URL (EC2):** http://<ip-o-dominio>:<puerto>  
- **Swagger UI:** http://<ip-o-dominio>:<puerto>/swagger-ui  
- **Entidades principales:**  
  - `<EntidadPrincipal>` (campos clave: …)  
- **Endpoints mínimos:**  
  - `POST /api/<recurso>`  
  - `GET /api/<recurso>`  
  - `GET /api/<recurso>/{id}`  
  - `PUT /api/<recurso>/{id}`  
  - `DELETE /api/<recurso>/{id}`  
- **Checklist de verificación (semanal):**  
  - [ ] Compila y arranca local  
  - [ ] `/actuator/health` **UP** en local  
  - [ ] Swagger accesible en EC2  
  - [ ] Push diario con commits significativos  
  - [ ] Historia/tarea en Jira: **En progreso** → **Terminado** al finalizar


  ### (Violentometro)-Tamizaje
- **Responsable:** Sara Malaver (saramalaver01-cpu) 
- **Repositorio:** https://
- **Base URL (EC2):** http://<ip-o-dominio>:<puerto>  
- **Swagger UI:** http://<ip-o-dominio>:<puerto>/swagger-ui  
- **Entidades principales:**  
  - `<EntidadPrincipal>` (campos clave: …)  
- **Checklist de verificación (semanal):**  
  - [ ] Compila y arranca local  
  - [ ] `/actuator/health` **UP** en local  
  - [ ] Swagger accesible en EC2  
  - [ ] Push diario con commits significativos  
  - [ ] Historia/tarea en Jira: **En progreso** → **Terminado** al finalizar


### (Bienestar emcoional)-Tamizaje
- **Responsable:** Yulieth Trujillo (yuliethtrujillo01) 
- **Repositorio:** https://
- **Base URL (EC2):** http://<ip-o-dominio>:<puerto>  
- **Swagger UI:** http://<ip-o-dominio>:<puerto>/swagger-ui  
- **Entidades principales:**  
  - `<EntidadPrincipal>` (campos clave: …)  
- **Checklist de verificación (semanal):**  
  - [ ] Compila y arranca local  
  - [ ] `/actuator/health` **UP** en local  
  - [ ] Swagger accesible en EC2  
  - [ ] Push diario con commits significativos  
  - [ ] Historia/tarea en Jira: **En progreso** → **Terminado** al finalizar

---

## Responsables (vista rápida)

| Rol | Nombre | Usuario GitHub | Observaciones |
|---|---|---|---|
| Scrum Master | Yulieth Trujillo | yuliethtrujillo01 | entrenador o guía del equipo |
| DevOps | Sara Malaver | saramalaver01-cpu | EC2, puertos, dominios |
| QA |  |  | Revisión básica de respuestas |
| Autor(es) de servicio(s) | Jaime Jurado | esteban-42 | Indicar cuál servicio |

---

## Notas de la semana
- Fecha: AAAA-MM-DD  
- Cambios relevantes:  
  - …  
- Bloqueos/riesgos:  
  - …

