Sistema de Gestión de Rutinas de Entrenamiento

Descripción:

El "Gestor de Rutinas de Entrenamiento" es una herramienta diseñada para ayudar a los usuarios a organizar y controlar sus actividades 
físicas diarias. El sistema permite registrar rutinas clasificadas por tipo (fuerza, cardio, flexibilidad), editar rutinas existentes,
eliminar rutinas innecesarias y mostrarlas. Con el objetivo de facilitar la gestión de actividades físicas de manera eficiente 
y personalizada.

Requisitos previos:

- Python 3.12.0

- Equipo de computo con sistema operativo windows 10 u 11

Instrucciones de instalación

1. Clonar el repositorio
Abre la terminal y ejecuta:

bash

git clone https://github.com/Rafael251102/sistema-gestion-rutinas.git
cd sistema-gestion-rutinas

2. Instalar Python (si no lo tienes)
Verifica si ya tienes Python instalado:

bash

python --version

o

bash

python3 --version

Si no está instalado, puedes descargarlo desde:
https://www.python.org/downloads/

3. Instalar dependencias (si aplica)
Este proyecto no requiere librerías externas, ya que utiliza solo módulos
estándar de Python (json, os, etc.). No necesitas instalar nada más.

4. Ejecutar el sistema
En la terminal, dentro del directorio del proyecto, ejecuta:

bash

python Sistema_de_gestion_de_rutinas_de_entrenamiento.py

O si usas Python 3:

bash

python3 Sistema_de_gestion_de_rutinas_de_entrenamiento.py

Guía de uso
Al ejecutar el sistema desde la terminal, verás un menú interactivo que te permitirá:

- Crear una rutina

- Editar una rutina existente

- Eliminar una rutina por ID

- Listar rutinas por categoría

- Mostrar todas las rutinas

Autores: 

Profesor: Ignacio Maldonado

Alumno: Aldir Rafael Garcia Nuñez

N.L: 58637

Documentacion del codigo:

- class Routine:
    """
    Representa una rutina de entrenamiento.

    Atributos:
    - task_id (int): ID único de la rutina.
    - title (str): Título de la rutina.
    - description (str): Descripción de los ejercicios.
    - category (str): Categoría (Fuerza, Cardio, Flexibilidad).
    - status (str): Estado de la rutina ("Pendiente" o "Completada").
    """
    def __init__(self, task_id, title, description, category, status="Pendiente"):
        ...
    
    def mark_complete(self):
        """Marca la rutina como completada."""
        ...

- class RoutineManager:
    """
    Administra la colección de rutinas.

    Atributos:
    - routines (list): Lista de rutinas.

    Métodos:
    - add_routine()
    - edit_routine()
    - delete_routine()
    - list_routines()
    """
    ...




