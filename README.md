
```markdown
# 🚀 Píldora Django y Proyecto Task Manager

¡Bienvenido al repositorio del proyecto **Task Manager**! Este proyecto es una aplicación web desarrollada con Django que permite gestionar tareas,
marcarlas como completadas y visualizarlas en una interfaz sencilla. A continuación, te explico todo lo que encontrarás en este repositorio.

---

## 📂 Estructura del Repositorio

- **`taskmanager/`**: Proyecto Django con la configuración base.
- **`tasks/`**: Aplicación Django que gestiona las tareas.
- **`docs/`**: Documentos relacionados con el proyecto.
  - 📄 [Presentación en PDF](docs/ai-django-pill-slides.pdf)
  - 📄 [Notas Complementarias en PDF](docs/ai-django-pill-notes.pdf)
- **`README.md`**: Este archivo, que describe el proyecto.

---

## 🛠️ Funcionalidades del Proyecto

El proyecto **Task Manager** incluye las siguientes funcionalidades:

- **Añadir tareas**: Permite crear nuevas tareas con un título y un estado (completado o no).
- **Marcar tareas como completadas**: Cambia el estado de las tareas.
- **Visualizar tareas**: Muestra una lista de todas las tareas en una página HTML.
- **Panel de administración**: Acceso a un panel de administración para gestionar las tareas (crear, editar, eliminar).

---

## 🖥️ Cómo Ejecutar el Proyecto

Sigue estos pasos para ejecutar el proyecto en tu máquina local:

### 1. Clona el Repositorio

```bash
git clone https://github.com/tu-usuario/tu-repositorio.git
cd tu-repositorio
```

### 2. Crea y Activa el Entorno Virtual

#### En Linux/macOS:
```bash
python3 -m venv .venv
source .venv/bin/activate
```

#### En Windows:
```bash
python -m venv .venv
.venv\Scripts\activate
```

### 3. Instala las Dependencias

```bash
pip install django
```

### 4. Aplica las Migraciones

```bash
python manage.py migrate
```

### 5. Crea un Superusuario (Opcional)

Si deseas acceder al panel de administración, crea un superusuario:

```bash
python manage.py createsuperuser
```

### 6. Ejecuta el Servidor

```bash
python manage.py runserver
```

### 7. Accede a la Aplicación

- **Lista de tareas**: Visita [http://127.0.0.1:8000/](http://127.0.0.1:8000/).
- **Panel de administración**: Visita [http://127.0.0.1:8000/admin/](http://127.0.0.1:8000/admin/).

---

## 📸 Capturas de Pantalla

### Lista de Tareas
![Lista de Tareas](imgs/task-list.png)

### Panel de Administración
![Panel de Administración](imgs/admin-panel.png)

---

## 📚 Documentación Adicional

En la carpeta `docs/` encontrarás dos archivos PDF que te ayudarán a entender mejor el proyecto:

1. **Presentación en PDF**: Explica los conceptos clave de Django y cómo se aplican en este proyecto.
2. **Notas Complementarias en PDF**: Contiene información detallada sobre la implementación y configuración del proyecto.

---

## 🛠️ Tecnologías Utilizadas

- **Django**: Framework de desarrollo web en Python.
- **SQLite**: Base de datos ligera utilizada para almacenar las tareas.
- **HTML/CSS**: Para la interfaz de usuario.
- **Git**: Control de versiones.

---

## 🌟 Contribuciones

¡Las contribuciones son bienvenidas! Si deseas mejorar este proyecto, sigue estos pasos:

1. Haz un fork del repositorio.
2. Crea una rama con tu nueva funcionalidad (`git checkout -b feature/nueva-funcionalidad`).
3. Realiza tus cambios y haz commit (`git commit -m 'Añade nueva funcionalidad'`).
4. Haz push a la rama (`git push origin feature/nueva-funcionalidad`).
5. Abre un Pull Request.

---

## 📄 Licencia

Este proyecto está bajo la licencia **MIT**. Para más detalles, consulta el archivo [LICENSE](LICENSE).

---

## 🙏 Agradecimientos

- **Django**: Por proporcionar un framework tan potente y fácil de usar.
- **Factoria F5**: Por la formación y el apoyo en el desarrollo de este proyecto.

---

¡Gracias por visitar este repositorio! Si tienes alguna pregunta o sugerencia, no dudes en abrir un issue o contactarme.

```
