# Actividad 1 - Backend 2 (Miércoles)
**Nombre Completo:** Irwin Colmenarez Castillo
**Institución:** Cesde

---

## 1. Instancia de Base de Datos
* **Enlace a la instancia:** [Prisma Studio - Base de Datos] (https://console.prisma.io/cmln3al2d08p8w8effynh830b/cmln3g2v008pfw8efqj1tica5/cmln3g2v008pdw8eflvu9qvof/studio)
* **Configuración de Base de Datos en Prisma.io:**
![Configuración Base de Datos - URL y Usuario (sin contraseña)](prismaBd.png)

* **Cadena de Conexión:**
```
postgresql://usuario:****@db.prisma.io:5432/postgres?sslmode=require
```
*(URL y usuario visibles, contraseña oculta por seguridad)*

---

## 2. Conexión desde Spring Boot
![Log de Conexión Exitosa en Spring Boot](conexionSprintBoot.png)

---

## 3. Pruebas de la API (CRUD)

### [POST] Crear Registro
*Captura de la solicitud (Request) y la respuesta (Response) en Postman/Insomnia:*
![POST Request and Response](apiPost.png)
### [GET] Obtener Todos (All)
![GET All Request and GET All Response](apiGetAll.png)
### [GET] Obtener por ID
![GET by ID Request and GET by ID Response](apiGetId.png)


### [GET] Obtener por Email
![GET by Email Request and GET by Email Response](apiGetemail.png)

### [PUT] Actualizar Registro
![PUT Request and PUT Response](apiPut.png)
### [DELETE] Eliminar Registro
![DELETE Request and DELETE Response](apiDelete.png)

---

## 4. Pruebas Internas del Proyecto
![Resultados de Pruebas Internas](testInternal.png)

> **Estado final:** Todas las pruebas pasaron exitosamente.

---
*Este repositorio es un fork del proyecto original para la asignatura de Backend 2.*