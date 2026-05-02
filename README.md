# Adakademy CRUD

¡Bienvenido a `Adakademy CRUD`! Este proyecto es una aplicación web simple construida con **Django** para gestionar artículos, usuarios y autenticación.

---

## 🚀 Tecnologías usadas

- **Python 3**
- **Django**
- **SQLite** como base de datos ligera por defecto
- **HTML** para las vistas
- **CSS** para estilos personalizados
- **Django Templates** para renderizar páginas dinámicas
- **Bootstrap** (opcional, si lo incluyes en el proyecto más adelante)

---

## 🧱 Estructura del proyecto

- `manage.py` — comando principal de Django
- `base_project/` — configuración global de Django
- `newspaper/` — app para gestionar artículos
- `signup/` — app para registro e inicio de sesión
- `templates/` — plantillas HTML
- `static/` — archivos estáticos como CSS
- `db.sqlite3` — base de datos local

---

## ✨ Características principales

- CRUD completo de artículos
- Registro y login de usuarios
- Vistas listas para crear, editar, eliminar y ver artículos
- Diseño limpio y fácil de mantener

---

## 🧰 Ejecución rápida

1. Crear y activar el entorno virtual
2. Instalar dependencias
3. Migrar la base de datos
4. Ejecutar el servidor

```bash
python -m venv .venv
.\.venv\Scripts\Activate.ps1
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

---

## 💡 Nota

Este proyecto está pensado como una base para aprender Django y construir aplicaciones CRUD con autenticación. Si querés, podés ampliar el front con más estilos y animaciones.
