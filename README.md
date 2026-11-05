# CER2-MONTEROBENJAMIN
# CER2_MONTEROBENJAMIN - Sistema de Gestión de Lugares Patrimoniales

Aplicación web desarrollada en **Django** para la gestión, visualización y administración segura de un catálogo de bienes y lugares patrimoniales, construida como parte de una evaluación académica.

## 🚀 Características Principales

* **Catálogo Público:** Visualización abierta de los lugares patrimoniales clasificados por categorías con sus respectivas descripciones, ubicaciones, años de construcción e imágenes.
* **Sistema de Autenticación:** Módulos de inicio (`LoginView`) y cierre de sesión seguros para administradores.
* **Panel de Gestión Protegido:** Ruta de administración restringida mediante el decorador `@login_required`.
* **CRUD Completo:** Funcionalidades para **listar, agregar y modificar** registros de lugares patrimoniales utilizando formularios basados en modelos (`ModelForm`).
* **Diseño Responsivo Local:** Interfaces estilizadas utilizando archivos de **Bootstrap** descargados e integrados directamente en la carpeta de recursos estáticos de la aplicación.

---

## 🛠️ Tecnologías y Dependencias

El proyecto se encuentra construido con el siguiente stack tecnológico:

* **Python** (versión 3.10 o superior recomendada)
* **Django** (versión 4.x / 5.x)
* **SQLite** (Base de datos por defecto de desarrollo)
* **Bootstrap** (Archivos CSS alojados localmente en `core/static/core/css/`)

### Dependencias de Python (`requirements.txt`)
Para ejecutar el proyecto, solo se requiere instalar Django:
```text
asgiref==3.x.x
Django==5.x.x
sqlparse==0.x.x
