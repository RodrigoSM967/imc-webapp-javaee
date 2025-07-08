# IMCWebApp — Cálculo del Índice de Masa Corporal

Aplicación Java Web que permite calcular el IMC de un usuario, registrar su historial y visualizar sus resultados a través de vistas JSP. Desarrollada con Java EE, servlets, modelo controlador y Jersey para servicios REST.

## 🧩 Funcionalidades

- Registro y validación de usuarios
- Inicio de sesión
- Cálculo automático de IMC
- Registro y despliegue de historial
- Vistas en JSP
- API REST (en desarrollo)

## 🚀 Tecnologías utilizadas

- Java EE / JSP / Servlets
- Jersey REST Framework
- Apache Tomcat
- Maven (estructura y empaquetado)
- Git y GitHub

## 📦 Estructura del proyecto

- `model/`: clases como `Usuario`, `IMCRegistro`
- `controller/`: servlets para registro, login, IMC
- `rest/`: servicios REST `IMCApplication`, `HistorialService`
- `webapp/`: vistas JSP

## 🛠 Estado actual

El proyecto se despliega correctamente en Tomcat y las vistas JSP son funcionales. El endpoint REST `/api/historial` presenta un error 404 persistente que fue documentado y se encuentra pendiente de solución.

## 📚 Wiki

La documentación técnica puede consultarse en el área Wiki del repositorio (pendiente de activación).

## 📸 Capturas y evidencia

Ver carpeta `Capturas/` en el repositorio principal.

## ✏️ Autor

Rodrigo Sánchez Morales — T03106719
