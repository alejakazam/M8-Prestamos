# Préstamos Lab

Proyecto desarrollado por Alejandra Duarte.

Préstamos Lab es un sistema que permite gestionar una base de datos de computadores disponibles y no disponibles para préstamo, considerando su antigüedad.
Incluye un sistema de usuarios con jerarquías que permite a los encargados acceder y administrar el inventario.

---

## I. Tecnologías utilizadas

* Python
* Django
* HTML5 y CSS3
* Bootstrap 5

---

## II. Descripción del sistema

El sistema permite:

* Registrar computadores disponibles para préstamo
* Controlar disponibilidad de equipos
* Gestionar antigüedad de los dispositivos
* Administrar usuarios con distintos niveles de acceso
* Acceder al inventario según permisos

---

## III. Instalación

### a. Clonar el repositorio

```bash id="j4k9dp"
git clone https://github.com/tu-usuario/tu-repo.git
cd tu-repo
```

### b. Crear entorno virtual

```bash id="p8s2mx"
python -m venv venv
```

Activar entorno:

```bash id="r5n7vt"
# Linux / Mac
source venv/bin/activate

# Windows
venv\Scripts\activate
```

### c. Instalar dependencias

```bash id="w1q6zb"
pip install -r requirements.txt
```

### d. Aplicar migraciones

```bash id="x3c8lf"
python manage.py migrate
```

### e. Ejecutar servidor

```bash id="k7d2ya"
python manage.py runserver
```

---

## IV. Información adicional

Proyecto de uso educativo.
Desarrollado por Alejandra Duarte.
