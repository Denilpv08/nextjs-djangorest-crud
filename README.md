# 📝 Task Manager - Django & Next.js

Este proyecto es una **aplicación de gestión de tareas** desarrollada con **Django (backend)** y **Next.js (frontend)**.  
Permite crear, editar, marcar como completadas y eliminar tareas, todo con una interfaz moderna y un backend robusto.

---

## 🚀 Tecnologías utilizadas

### 🔹 Backend

- Python 3.x
- Django
- Django REST Framework
- Django CORS Headers

### 🔹 Frontend

- Next.js 14
- React
- Tailwind CSS
- React Icons

---

## 📦 Requisitos previos

Antes de comenzar, asegúrate de tener instalado:

- [Python 3](https://www.python.org/downloads/)
- [Node.js](https://nodejs.org/) y npm
- Git

---

## ⚙️ Instalación y configuración

### 🔹 Backend (Django API)

Ejecuta los siguientes comandos en orden:

```bash
# Clonar el repositorio (ejemplo)
git clone https://github.com/tuusuario/task-manager.git
cd task-manager/backend

# Crear entorno virtual
python -m venv venv

# Activar entorno virtual
.\venv\Scripts\activate   # En Windows
source venv/bin/activate  # En Linux/Mac

# Instalar dependencias principales
pip install django djangorestframework

# Crear proyecto y aplicación
django-admin startproject taskapi .
python manage.py startapp tasks

# Migraciones
python manage.py makemigrations
python manage.py migrate

# Instalar CORS
python -m pip install django-cors-headers

# Levantar servidor
python manage.py runserver
```
