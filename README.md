# Actividad-2.Python

# 📚 Biblioteca Personal CLI (Command Line Interface)

Este proyecto es una aplicación de línea de comandos desarrollada en Python que permite a un usuario administrar una biblioteca personal. Utiliza SQLite para el almacenamiento persistente de los datos, cumpliendo con los requisitos de las operaciones CRUD (Crear, Leer, Actualizar, Eliminar).

## 🚀 Requisitos

Para ejecutar esta aplicación, solo necesitas tener instalado:
* Python 3.x

La aplicación utiliza la librería estándar `sqlite3`, por lo que no se requiere ninguna instalación adicional (`pip install`).

## ⚙️ Estructura de la Base de Datos

La aplicación crea automáticamente una base de datos llamada `biblioteca.db` con la siguiente tabla:

### Tabla: `libros`

| Columna | Tipo de Dato | Restricciones | Descripción |
| :--- | :--- | :--- | :--- |
| **id** | INTEGER | PRIMARY KEY | Identificador único del libro. |
| **titulo** | TEXT | NOT NULL | Título del libro. |
| **autor** | TEXT | NOT NULL | Autor del libro. |
| **genero** | TEXT | | Género o categoría. |
| **leido** | BOOLEAN | CHECK (0 o 1) | Estado de lectura (0: No Leído, 1: Leído). |

## 📖 Instrucciones de Ejecución

1.  **Guarda el Código:** Guarda el código Python proporcionado en un archivo llamado `biblioteca_cli.py`.
2.  **Ejecuta el Programa:** Abre tu terminal (Símbolo del sistema, PowerShell, Git Bash o la Terminal de VS Code) en la carpeta donde guardaste el archivo y ejecuta el siguiente comando:

    ```bash
    python biblioteca_cli.py
    ```

3.  **Primer Uso:** Al ejecutarlo por primera vez, se creará automáticamente el archivo `biblioteca.db`. Sigue las instrucciones del menú interactivo para empezar a gestionar tus libros.

## 📸 Captura del Programa en Uso (Opcional)

[Aquí puedes añadir una captura de pantalla de la terminal mostrando el listado o el menú.]

---
