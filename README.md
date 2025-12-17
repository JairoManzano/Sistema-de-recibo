# Sistema Automatizado de Cobros del ISTSGA

## 📌 Descripción del Proyecto

El **Sistema Automatizado de Cobros del ISTSGA** es una solución informática diseñada para modernizar y optimizar el proceso de registro, control y reporte de los pagos realizados por los estudiantes del Instituto Superior Tecnológico San Gabriel **ISTSGA**.

Actualmente, los procesos manuales de cobro pueden generar errores, retrasos y dificultades en la consulta de información histórica. Este sistema busca resolver dichas limitaciones mediante una plataforma digital segura, eficiente y accesible desde cualquier navegador web.

## 🧩 Funcionalidades Principales

* Registro de estudiantes y pagos.
* Clasificación de pagos por tipo y fecha.
* Emisión automática de comprobantes de pago.
* Búsqueda y filtrado de pagos históricos.
* Generación de reportes en formato digital.
* Control de accesos mediante roles de usuario.

## 🛠️ Tecnologías Sugeridas

* **Frontend:** HTML, CSS, JavaScript (opcional: React, Vue o Bootstrap)
* **Backend:** PHP / Python (Flask o Django) / Node.js
* **Base de Datos:** MySQL / PostgreSQL
* **Servidor:** Apache o Nginx

> *Las tecnologías pueden adaptarse según los requerimientos institucionales.*

## 📁 Estructura del Proyecto

```
/istgsa-cobros
│── /src            # Código fuente del sistema
│── /database       # Scripts de base de datos
│── /docs           # Documentación del proyecto
│── /tests          # Pruebas del sistema
│── README.md       # Documento descriptivo del proyecto
```

## ⚙️ Requisitos del Sistema

* Servidor web (Apache o Nginx)
* PHP 8.x / Python 3.x / Node.js (según backend elegido)
* Gestor de base de datos MySQL o PostgreSQL
* Navegador web actualizado

## 🚀 Instalación

1. **Clonar el repositorio**

```bash
git clone https://github.com/usuario/istgsa-cobros.git
```

2. **Acceder al directorio del proyecto**

```bash
cd istgsa-cobros
```

3. **Configurar la base de datos**

* Crear una base de datos en MySQL/PostgreSQL.
* Importar el archivo ubicado en `/database/cobros.sql`.

4. **Configurar variables de entorno**

* Definir credenciales de base de datos y parámetros del sistema.

5. **Iniciar el servidor**

* Colocar el proyecto en el directorio del servidor web.
* Acceder desde el navegador mediante `http://localhost/istgsa-cobros`.

## 📊 Uso del Sistema

* Iniciar sesión como administrador o usuario autorizado.
* Registrar pagos de estudiantes.
* Consultar pagos históricos.
* Generar y descargar reportes.

## 🔒 Seguridad

* Validación de usuarios y contraseñas.
* Control de roles (administrador / operador).
* Registro de actividades para auditoría.

## 📈 Resultados Esperados

* Mayor eficiencia en el proceso de cobros.
* Reducción de errores humanos.
* Acceso rápido y confiable a la información financiera.
* Mejora en la transparencia y control administrativo.

## 👥 Autores

Jairo Manzano  

## 📄 Licencia

Este proyecto es de uso académico e institucional.
