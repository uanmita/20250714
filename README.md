# 20250714 - Proyecto Django Blog

¡Bienvenido/a al repositorio del proyecto **20250714**!

Este proyecto es una aplicación web desarrollada con Django que implementa un blog sencillo, ideal para aprender y practicar los conceptos fundamentales del framework.

## 🚀 Características principales

- Gestión de publicaciones de blog (crear, editar, eliminar, listar y ver detalles)
- Panel de administración de Django
- Uso de modelos, vistas, formularios y plantillas
- Estructura de proyecto profesional

## 📁 Estructura del proyecto

```
20250714/
├── blog/                # Aplicación principal del blog
│   ├── models.py        # Modelos de datos
│   ├── views.py         # Lógica de vistas
│   ├── forms.py         # Formularios personalizados
│   ├── urls.py          # Rutas de la app
│   └── templates/       # Plantillas HTML
├── myproject/           # Configuración global de Django
│   ├── settings.py      # Configuración del proyecto
│   └── urls.py          # Rutas globales
├── db.sqlite3           # Base de datos SQLite
├── manage.py            # Script de gestión de Django
└── README.md            # Este archivo
```

## 🛠️ Instalación y uso rápido

1. Clona el repositorio:
   ```bash
   git clone https://github.com/uanmita/20250714.git
   cd 20250714
   ```
2. Instala las dependencias (se recomienda usar un entorno virtual):
   ```bash
   python -m venv venv
   venv\Scripts\activate  # En Windows
   pip install django
   ```
3. Aplica las migraciones y ejecuta el servidor:
   ```bash
   python manage.py migrate
   python manage.py runserver
   ```
4. Accede a la app en [http://localhost:8000](http://localhost:8000)

## ✨ Créditos

Desarrollado por uanmita · Curso Django 2025

---
¡Si te resulta útil, dale una estrella al repo y contribuye con tus mejoras!
